Example of how to use Python with the API
=========================================

Example:

.. code-block:: python

    import urllib.request
    import json
    
    
    school = "UMCP"
    dept = "AASP"
    
    
    url = "http://hackathon.bookholders.com/classdata/{}/{}".format(school,dept)
    
    
    response = urllib.request.urlopen(url)
    data = str(response.read(),'utf-8')
    
    print(data)
    
    response_json = json.loads(data)
    
    for each_class in response_json:
    	print(each_class['title'])
