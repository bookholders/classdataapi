.. _javascript-label:

Example of how to use JavaScript with the API
=============================================

Example:

.. code-block:: javascript

    import urllib.request
    import json
    
    
    school = "UMCP"
    dept = "AASP"
    
    
    url = "http://hackathon.bookholders.com/classdata/{}/{}".format(school,dept)
   
    <!DOCTYPE html>
    <html>
    <head>
	<title>Test Class Data API</title>
	<script type="text/javascript">
		var group = "";
		function post(){
			var parameters = document.getElementById("parameters").value;
			//create xhr
			var postXHR = new XMLHttpRequest();
			postXHR.open('GET', 'http://hackathon.bookholders.com/classdata/' + parameters, true);
			
			try{
				postXHR.send(null);
				document.getElementById('jsonOutput').innerHTML = "Loading...";
			}catch(e){
				document.getElementById('jsonOutput').innerHTML = "Error Exception: "+e;
			}
			
			postXHR.onloadend = function(){
				try {
				var jsonobj = JSON.parse(postXHR.response);
				var stuff;
				if (jsonobj[0] !== undefined) {
					stuff = 'Semester: ' + jsonobj[0].semester + '</br>';
				} else {
					stuff = '';
				}
				stuff += JSON.stringify(jsonobj, null, 2) ;
				document.getElementById("jsonOutput").innerHTML = stuff;
				} catch(e){
				document.getElementById('jsonOutput').innerHTML = "Error Exception: "+e;
				}
			}
		}
	</script>
	</head>
	<body>
	<div>
		<h1 align="center">JS TEST  of CLASS DATA API</h1>
		<p align="center"></p>
		<p align="center" >API Input: </p>
		<form style='text-align: center;'>
			http://hackathon.bookholders.com/classdata/<input type="text" id="parameters" name="parameters" onkeydown="if (event.keyCode == 13) { post(); return false; }"><br/>
			<button type="button" id="submitButton" onclick="post()" accesskey="s">Submit</button>
		</form>
		
		<p id="jsonOutput" align="center" ></p>
	</div>
    </body>
    </html>
