Search Request
==========================


This is example request of search. 

   :url: http://hackathon.bookholders.com/classdata/<school>/search?professor=<professor>&days=<days>&building=<building>&room=<room>&section=<section>
   :school: UMCP,TU,HU,JHU
   :days: m,tu,w,th,f
   :building: chm
   :room: 1407
   :section: 6236


   **Example request**:
   
   .. sourcecode:: http
   
      GET /classdata/UMCP/search?professor=smith&days=tu&building=chm&room=1407&section=6236
   
   **Example response**:
   
   .. code-block:: json 
      [
         {
            "seats":41,
            "semester":"F15",
            "date":"08/31/2015-12/11/2015",
            "starttime":"9:30am",
            "open":0,
            "professor":"Michael Montague-Smith",
            "room":"1407",
            "section":"6236",
            "class":"CHEM241",
            "building":"CHM",
            "days":"TuTh",
            "endtime":"10:45am"
         }
      ]
