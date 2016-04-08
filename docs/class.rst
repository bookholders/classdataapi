.. _class-label:

Class Request
=============


This is example request of class for a certain school. 

  :url: http://hackathon.bookholders.com/classdata/v1/F15/<school>/<class>
  :school: UMCP,TU,HU,JHU,MSU,VT,VCU,WVU,USF,UT,RU
  :class: AASP,ANTH

Here is a working example:
http://hackathon.bookholders.com/classdata/v1/F15/UMCP/AASP


  **Example request**:
  
  .. sourcecode:: http
  
     GET /classdata/UMCP/aasp
  
  **Example response**:
  
  .. code-block:: json 

        [  
        {  
           "department":"AASP",
           "class":"AASP100",
           "semester":"F15",
           "title":"Introduction to African American Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP100H",
           "semester":"F15",
           "title":"Introduction to African American Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP101",
           "semester":"F15",
           "title":"Public Policy and the Black Community"
        },
        {  
           "department":"AASP",
           "class":"AASP187I",
           "semester":"F15",
           "title":"The New Jim Crow: African-Americans, Mass Incarceration and the Prison Industrial Complex"
        },
        {  
           "department":"AASP",
           "class":"AASP200",
           "semester":"F15",
           "title":"African Civilization"
        },
        {  
           "department":"AASP",
           "class":"AASP202",
           "semester":"F15",
           "title":"Black Culture in the United States"
        },
        {  
           "department":"AASP",
           "class":"AASP202H",
           "semester":"F15",
           "title":"Black Culture in the United States"
        },
        {  
           "department":"AASP",
           "class":"AASP274",
           "semester":"F15",
           "title":"Creative Writing Through The Eyes of African Americans: A Beginning Workshop"
        },
        {  
           "department":"AASP",
           "class":"AASP297",
           "semester":"F15",
           "title":"Research Methods in African American Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP298C",
           "semester":"F15",
           "title":"Special Topics in African American Studies; African-American History to 1865"
        },
        {  
           "department":"AASP",
           "class":"AASP298I",
           "semester":"F15",
           "title":"Special Topics in African American Studies; Introduction to Black Women's Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP298L",
           "semester":"F15",
           "title":"Special Topics in Afro-American Studies:  African-American Literature and Culture"
        },
        {  
           "department":"AASP",
           "class":"AASP313",
           "semester":"F15",
           "title":"Black Women in United States History"
        },
        {  
           "department":"AASP",
           "class":"AASP314",
           "semester":"F15",
           "title":"The Civil Rights Movement"
        },
        {  
           "department":"AASP",
           "class":"AASP386",
           "semester":"F15",
           "title":"Experiential Learning"
        },
        {  
           "department":"AASP",
           "class":"AASP395",
           "semester":"F15",
           "title":"Fundamentals of Quantitative Research in Socio-Cultural Perspective"
        },
        {  
           "department":"AASP",
           "class":"AASP396",
           "semester":"F15",
           "title":"Independent Study Non-Thesis Option"
        },
        {  
           "department":"AASP",
           "class":"AASP397",
           "semester":"F15",
           "title":"Senior Thesis"
        },
        {  
           "department":"AASP",
           "class":"AASP398G",
           "semester":"F15",
           "title":"Selected Topics in the African Diaspora; Gender, Labor, and Racial Identify in Diaspora Communities"
        },
        {  
           "department":"AASP",
           "class":"AASP398Q",
           "semester":"F15",
           "title":"Selected Topics in the African Diaspora; Black Baltimore in the Post Racial U.S: African American Urban Culture in the Age of Obama"
        },
        {  
           "department":"AASP",
           "class":"AASP400",
           "semester":"F15",
           "title":"Directed Readings in African American Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP400H",
           "semester":"F15",
           "title":"Directed Readings in African American Studies"
        },
        {  
           "department":"AASP",
           "class":"AASP478N",
           "semester":"F15",
           "title":"Humanities Topics in African American Studies; African-American Literature:  1910-1945"
        },
        {  
           "department":"AASP",
           "class":"AASP498O",
           "semester":"F15",
           "title":"Special Topics in Black Culture; African American and Latino Social, Cultural and Political Relations: 1940 to Present"
        },
        {  
           "department":"AASP",
           "class":"AASP498V",
           "semester":"F15",
           "title":"Special Topics in Black Culture; African American Urban History 1877-Present"
        },
        {  
           "department":"AASP",
           "class":"AASP499N",
           "semester":"F15",
           "title":"Advanced Topics in Public Policy and the Black Community; Gentrification: The Evolution of Urban Neighborhoods"
        },
        {  
           "department":"AASP",
           "class":"AASP499P",
           "semester":"F15",
           "title":"Advanced Topics in Public Policy and the Black Community; African-American Politics from Frederick Douglass to Barack Obama"
        }
     ]
