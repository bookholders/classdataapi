.. _python-label:

Example of how to use Python with the API
=========================================

Example:

.. code-block:: python

    import urllib.request
    import json
    
    
    school = "UMCP"
    dept = "AASP"
    
    
    url = "http://hackathon.bookholders.com/classdata/v1/s16/{}/{}".format(school,dept)
    
    
    response = urllib.request.urlopen(url)
    data = str(response.read(),'utf-8')
    
    print(data)
    
    response_json = json.loads(data)
    
    for each_class in response_json:
    	print(each_class['title'])
    	

**Example request**:
   
   .. sourcecode:: http
   
      http://hackathon.bookholders.com/classdata/v1/s16/UMCP/HIST/HIST245
   
   **Example response**:
   
   .. code-block:: json 
      
         [
            {
               "seats":40,
               "semester":"S16",
               "date":"01/25/2015-05/10/2015",
               "starttime":"9:30am",
               "open":10,
               "professor":"Peter Wien",
               "room":"0126",
               "section":"0101",
               "class":"HIST245",
               "building":"KEY",
               "days":"TuTh",
               "endtime":"10:45am"
            }
         ]
