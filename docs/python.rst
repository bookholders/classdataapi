.. _python-label:

Example of how to use Python with the API
=========================================

Here are a couple Live Demos: 

http://hackathon.bookholders.com/classdata/v1/s16/JHU
http://hackathon.bookholders.com/classdata/v1/s16/JHU/AS.010
http://hackathon.bookholders.com/classdata/v1/s16/JHU/AS.010/AS.010.102

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
