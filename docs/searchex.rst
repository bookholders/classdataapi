.. _search-label:

Search Request
==============


This is example request of search. 

   :url: http://hackathon.bookholders.com/classdata/v1/s16/<school>/search?professor=<professor>&days=<days>&building=<building>&room=<room>&section=<section>
   :school: UMCP,TU,HU,JHU
   :days: m,tu,w,th,f
   :building: key
   :room: 0126
   :section: 0101

   **Example request**:
   
   .. sourcecode:: http
   
      GET /classdata/v1/s16/UMCP/search?professor=wien&days=tu&building=key&room=0126&section=0101
   
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
