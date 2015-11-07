Example of Section Request
==========================


This is example request of department for a certain school. 

   :url: http://hackathon.bookholders.com/classdata/<school>/<class>/<section>
   :school: UMCP,TU,HU,JHU


**Example request**:

.. sourcecode:: http

   GET /classdata/UMCP/aasp/aasp100

**Example response**:

.. code-block:: json 

        [  
        {  
           "endtime":"10:50am",
           "starttime":"10:00am",
           "section":"0101",
           "room":"1114",
           "days":"MWF",
           "building":"WDS",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":0,
           "class":"AASP100",
           "professor":"Shane Walsh",
           "seats":21
        },
        {  
           "endtime":"12:50pm",
           "starttime":"12:00pm",
           "section":"0201",
           "room":"1100",
           "days":"MWF",
           "building":"ITV",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":1,
           "class":"AASP100",
           "professor":"Shane Walsh",
           "seats":21
        },
        {  
           "endtime":"10:45am",
           "starttime":"9:30am",
           "section":"0301",
           "room":"1114",
           "days":"TuTh",
           "building":"TYD",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":0,
           "class":"AASP100",
           "professor":"Jonathan England",
           "seats":21
        },
        {  
           "endtime":"1:45pm",
           "starttime":"12:30pm",
           "section":"0401",
           "room":"0109",
           "days":"TuTh",
           "building":"HBK",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":0,
           "class":"AASP100",
           "professor":"Jonathan England",
           "seats":18
        },
        {  
           "endtime":"12:15pm",
           "starttime":"11:00am",
           "section":"0501",
           "room":"0215",
           "days":"TuTh",
           "building":"SYM",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":0,
           "class":"AASP100",
           "professor":"Jason Nichols",
           "seats":21
        },
        {  
           "endtime":"3:15pm",
           "starttime":"2:00pm",
           "section":"0601",
           "room":"1101",
           "days":"TuTh",
           "building":"TYD",
           "date":"08/31/2015-12/11/2015",
           "semester":"F15",
           "open":0,
           "class":"AASP100",
           "professor":"Jason Nichols",
           "seats":21
        }
     ]
