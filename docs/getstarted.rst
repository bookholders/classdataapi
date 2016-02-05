.. _dept-label:

Example of Department Request
=============================


This is example request of department for a certain school. 

   :url: http://hackathon.bookholders.com/classdata/v1/s16/<school>
   :school: UMCP,TU,HU,JHU

Here is a working example:
http://hackathon.bookholders.com/classdata/v1/s16/JHU


   **Example request**:

   .. sourcecode:: http

      GET /classdata/UMCP

   **Example response**:

   .. code-block:: json 


         [
            {
               "department":"AASP",
               "semester":"S16",
               "name":"African American Studies"
            },
            {
               "department":"AAST",
               "semester":"S16",
               "name":"Asian American Studies"
            },
            {
               "department":"AGNR",
               "semester":"S16",
               "name":"Agriculture and Natural Resources"
            },
            {
               "department":"AMSC",
               "semester":"S16",
               "name":"Applied Mathematics & Scientific Computation"
            },
            {
               "department":"AMST",
               "semester":"S16",
               "name":"American Studies"
            },
            {
               "department":"ANSC",
               "semester":"S16",
               "name":"Animal Science"
            },
            {
               "department":"ANTH",
               "semester":"S16",
               "name":"Anthropology"
            },
            {
               "department":"AOSC",
               "semester":"S16",
               "name":"Atmospheric and Oceanic Science"
            },
            {
               "department":"ARAB",
               "semester":"S16",
               "name":"Arabic"
            },
            {
               "department":"ARCH",
               "semester":"S16",
               "name":"Architecture"
            },
            {
               "department":"AREC",
               "semester":"S16",
               "name":"Agricultural and Resource Economics"
            },
            {
               "department":"ARHU",
               "semester":"S16",
               "name":"Arts and Humanities"
            },
            {
               "department":"ARMY",
               "semester":"S16",
               "name":"Army"
            },
            {
               "department":"ARSC",
               "semester":"S16",
               "name":"Air Science"
            },
            {
               "department":"ARTH",
               "semester":"S16",
               "name":"Art History & Archaeology"
            },
            {
               "department":"ARTT",
               "semester":"S16",
               "name":"Art Studio"
            },
            {
               "department":"ASTR",
               "semester":"S16",
               "name":"Astronomy"
            },
            {
               "department":"BCHM",
               "semester":"S16",
               "name":"Biochemistry"
            },
            {
               "department":"BEES",
               "semester":"S16",
               "name":"Behavior, Ecology, Evolution and Systematics"
            },
            {
               "department":"BIOE",
               "semester":"S16",
               "name":"Bioengineering"
            },
            {
               "department":"BIOL",
               "semester":"S16",
               "name":"Biology"
            },
            {
               "department":"BIOM",
               "semester":"S16",
               "name":"Biometrics"
            },
            {
               "department":"BIPH",
               "semester":"S16",
               "name":"Biophysics"
            },
            {
               "department":"BMGT",
               "semester":"S16",
               "name":"Business and Management"
            },
            {
               "department":"BSCI",
               "semester":"S16",
               "name":"Biological Sciences Program"
            },
            {
               "department":"BSCV",
               "semester":"S16",
               "name":"CIVICUS"
            },
            {
               "department":"BSGC",
               "semester":"S16",
               "name":"Global Communities"
            },
            {
               "department":"BSOS",
               "semester":"S16",
               "name":"Behavioral and Social Sciences"
            },
            {
               "department":"BSST",
               "semester":"S16",
               "name":"Terrorism Studies"
            },
            {
               "department":"BUAC",
               "semester":"S16",
               "name":"Accounting and Information Assurance"
            },
            {
               "department":"BUDT",
               "semester":"S16",
               "name":"Decision and Information Technologies"
            },
            {
               "department":"BUFN",
               "semester":"S16",
               "name":"Finance"
            },
            {
               "department":"BULM",
               "semester":"S16",
               "name":"Logistics, Business, and Public Policy"
            },
            {
               "department":"BUMK",
               "semester":"S16",
               "name":"Marketing"
            },
            {
               "department":"BUMO",
               "semester":"S16",
               "name":"Management and Organization"
            },
            {
               "department":"BUSI",
               "semester":"S16",
               "name":"Part-Time MBA Program"
            },
            {
               "department":"CBMG",
               "semester":"S16",
               "name":"Cell Biology & Molecular Genetics"
            },
            {
               "department":"CCJS",
               "semester":"S16",
               "name":"Criminology and Criminal Justice"
            },
            {
               "department":"CHBE",
               "semester":"S16",
               "name":"Chemical and Biomolecular Engineering"
            },
            {
               "department":"CHEM",
               "semester":"S16",
               "name":"Chemistry"
            },
            {
               "department":"CHIN",
               "semester":"S16",
               "name":"Chinese"
            },
            {
               "department":"CHPH",
               "semester":"S16",
               "name":"Chemical Physics"
            },
            {
               "department":"CLAS",
               "semester":"S16",
               "name":"Classics"
            },
            {
               "department":"CLFS",
               "semester":"S16",
               "name":"Chemical and Life Sciences"
            },
            {
               "department":"CMLT",
               "semester":"S16",
               "name":"Comparative Literature"
            },
            {
               "department":"CMSC",
               "semester":"S16",
               "name":"Computer Science"
            },
            {
               "department":"COMM",
               "semester":"S16",
               "name":"Communication"
            },
            {
               "department":"CONS",
               "semester":"S16",
               "name":"Sustainable Development & Conservation Biology"
            },
            {
               "department":"CPBE",
               "semester":"S16",
               "name":"College Park Scholars-Business, Society, and Economy"
            },
            {
               "department":"CPET",
               "semester":"S16",
               "name":"College Park Scholars-Environment, Technology & Economy"
            },
            {
               "department":"CPGH",
               "semester":"S16",
               "name":"College Park Scholars-Global Public Health"
            },
            {
               "department":"CPJT",
               "semester":"S16",
               "name":"College Park Scholars-Justice and Legal Thought"
            },
            {
               "department":"CPMS",
               "semester":"S16",
               "name":"College Park Scholars-Media, Self and Society"
            },
            {
               "department":"CPPL",
               "semester":"S16",
               "name":"College Park Scholars-Public Leadership"
            },
            {
               "department":"CPSA",
               "semester":"S16",
               "name":"College Park Scholars-Arts"
            },
            {
               "department":"CPSD",
               "semester":"S16",
               "name":"College Park Scholars-Science, Discovery & the Universe"
            },
            {
               "department":"CPSF",
               "semester":"S16",
               "name":"College Park Scholars-Life Sciences"
            },
            {
               "department":"CPSG",
               "semester":"S16",
               "name":"College Park Scholars-Science and Global Change"
            },
            {
               "department":"CPSN",
               "semester":"S16",
               "name":"College Park Scholars-International Studies"
            },
            {
               "department":"CPSP",
               "semester":"S16",
               "name":"College Park Scholars Program"
            },
            {
               "department":"CPSS",
               "semester":"S16",
               "name":"College Park Scholars-Science, Technology and Society"
            },
            {
               "department":"DANC",
               "semester":"S16",
               "name":"Dance"
            },
            {
               "department":"EALL",
               "semester":"S16",
               "name":"East Asian Languages and Literatures"
            },
            {
               "department":"ECON",
               "semester":"S16",
               "name":"Economics"
            },
            {
               "department":"EDCI",
               "semester":"S16",
               "name":"Curriculum and Instruction"
            },
            {
               "department":"EDCP",
               "semester":"S16",
               "name":"Education Counseling and Personnel Services"
            },
            {
               "department":"EDHD",
               "semester":"S16",
               "name":"Education, Human Development"
            },
            {
               "department":"EDHI",
               "semester":"S16",
               "name":"Education Leadership, Higher Ed and International Ed"
            },
            {
               "department":"EDMS",
               "semester":"S16",
               "name":"Measurement, Statistics, and Evaluation"
            },
            {
               "department":"EDPS",
               "semester":"S16",
               "name":"Education Policy Studies"
            },
            {
               "department":"EDSP",
               "semester":"S16",
               "name":"Education, Special"
            },
            {
               "department":"EDUC",
               "semester":"S16",
               "name":"Education"
            },
            {
               "department":"ENAE",
               "semester":"S16",
               "name":"Engineering, Aerospace"
            },
            {
               "department":"ENCE",
               "semester":"S16",
               "name":"Engineering, Civil"
            },
            {
               "department":"ENCH",
               "semester":"S16",
               "name":"Engineering, Chemical"
            },
            {
               "department":"ENCO",
               "semester":"S16",
               "name":"Engineering, Cooperative Education"
            },
            {
               "department":"ENEE",
               "semester":"S16",
               "name":"Electrical & Computer Engineering"
            },
            {
               "department":"ENES",
               "semester":"S16",
               "name":"Engineering Science"
            },
            {
               "department":"ENFP",
               "semester":"S16",
               "name":"Engineering, Fire Protection"
            },
            {
               "department":"ENGL",
               "semester":"S16",
               "name":"English"
            },
            {
               "department":"ENMA",
               "semester":"S16",
               "name":"Engineering, Materials"
            },
            {
               "department":"ENME",
               "semester":"S16",
               "name":"Engineering, Mechanical"
            },
            {
               "department":"ENNU",
               "semester":"S16",
               "name":"Engineering, Nuclear"
            },
            {
               "department":"ENPM",
               "semester":"S16",
               "name":"Engineering, Professional Masters"
            },
            {
               "department":"ENPP",
               "semester":"S16",
               "name":"Engineering and Public Policy"
            },
            {
               "department":"ENRE",
               "semester":"S16",
               "name":"Reliability Engineering"
            },
            {
               "department":"ENSE",
               "semester":"S16",
               "name":"Systems Engineering"
            },
            {
               "department":"ENSP",
               "semester":"S16",
               "name":"Environmental Science and Policy"
            },
            {
               "department":"ENST",
               "semester":"S16",
               "name":"Environmental Science and Technology"
            },
            {
               "department":"ENTM",
               "semester":"S16",
               "name":"Entomology"
            },
            {
               "department":"ENTS",
               "semester":"S16",
               "name":"Telecommunications"
            },
            {
               "department":"EPIB",
               "semester":"S16",
               "name":"Epidemiology and Biostatistics"
            },
            {
               "department":"FILM",
               "semester":"S16",
               "name":"Film Studies"
            },
            {
               "department":"FIRE",
               "semester":"S16",
               "name":"First-Year Innovation & Research Experience"
            },
            {
               "department":"FMSC",
               "semester":"S16",
               "name":"Family Science"
            },
            {
               "department":"FOLA",
               "semester":"S16",
               "name":"Foreign Language"
            },
            {
               "department":"FREN",
               "semester":"S16",
               "name":"French"
            },
            {
               "department":"GEMS",
               "semester":"S16",
               "name":"Gemstone"
            },
            {
               "department":"GEOG",
               "semester":"S16",
               "name":"Geographical Sciences"
            },
            {
               "department":"GEOL",
               "semester":"S16",
               "name":"Geology"
            },
            {
               "department":"GERM",
               "semester":"S16",
               "name":"Germanic Studies"
            },
            {
               "department":"GREK",
               "semester":"S16",
               "name":"Greek"
            },
            {
               "department":"GVPT",
               "semester":"S16",
               "name":"Government and Politics"
            },
            {
               "department":"HACS",
               "semester":"S16",
               "name":"ACES-Cybersecurity"
            },
            {
               "department":"HDCC",
               "semester":"S16",
               "name":"Digital Cultures and Creativity"
            },
            {
               "department":"HEBR",
               "semester":"S16",
               "name":"Hebrew"
            },
            {
               "department":"HEIP",
               "semester":"S16",
               "name":"Entrepreneurship and Innovation"
            },
            {
               "department":"HESI",
               "semester":"S16",
               "name":"Higher Ed, Student Affairs, and International Ed Policy"
            },
            {
               "department":"HESP",
               "semester":"S16",
               "name":"Hearing and Speech Sciences"
            },
            {
               "department":"HHUM",
               "semester":"S16",
               "name":"Honors Humanities"
            },
            {
               "department":"HISP",
               "semester":"S16",
               "name":"Historic Preservation"
            },
            {
               "department":"HIST",
               "semester":"S16",
               "name":"History"
            },
            {
               "department":"HLSA",
               "semester":"S16",
               "name":"Health Services Administration"
            },
            {
               "department":"HLSC",
               "semester":"S16",
               "name":"Integrated Life Sciences"
            },
            {
               "department":"HLTH",
               "semester":"S16",
               "name":"Health"
            },
            {
               "department":"HONR",
               "semester":"S16",
               "name":"Honors"
            },
            {
               "department":"IMMR",
               "semester":"S16",
               "name":"Immigration Studies"
            },
            {
               "department":"INAG",
               "semester":"S16",
               "name":"Institute of Applied Agriculture"
            },
            {
               "department":"INFM",
               "semester":"S16",
               "name":"Information Management"
            },
            {
               "department":"INST",
               "semester":"S16",
               "name":"Information Studies"
            },
            {
               "department":"ISRL",
               "semester":"S16",
               "name":"Israel Studies"
            },
            {
               "department":"ITAL",
               "semester":"S16",
               "name":"Italian"
            },
            {
               "department":"JAPN",
               "semester":"S16",
               "name":"Japanese"
            },
            {
               "department":"JOUR",
               "semester":"S16",
               "name":"Journalism"
            },
            {
               "department":"JWST",
               "semester":"S16",
               "name":"Jewish Studies"
            },
            {
               "department":"KNES",
               "semester":"S16",
               "name":"Kinesiology"
            },
            {
               "department":"KORA",
               "semester":"S16",
               "name":"Korean"
            },
            {
               "department":"LARC",
               "semester":"S16",
               "name":"Landscape Architecture"
            },
            {
               "department":"LASC",
               "semester":"S16",
               "name":"Certificate in Latin American Studies"
            },
            {
               "department":"LATN",
               "semester":"S16",
               "name":"Latin"
            },
            {
               "department":"LBSC",
               "semester":"S16",
               "name":"Library Science"
            },
            {
               "department":"LGBT",
               "semester":"S16",
               "name":"Lesbian Gay Bisexual Transgender Studies"
            },
            {
               "department":"LING",
               "semester":"S16",
               "name":"Linguistics"
            },
            {
               "department":"MATH",
               "semester":"S16",
               "name":"Mathematics"
            },
            {
               "department":"MEES",
               "semester":"S16",
               "name":"Marine-Estuarine-Environmental Sciences"
            },
            {
               "department":"MIEH",
               "semester":"S16",
               "name":"Maryland Institute for Applied Environmental Health"
            },
            {
               "department":"MLAW",
               "semester":"S16",
               "name":"MPower Undergraduate Law Programs"
            },
            {
               "department":"MOCB",
               "semester":"S16",
               "name":"Molecular and Cell Biology"
            },
            {
               "department":"MUED",
               "semester":"S16",
               "name":"Music Education"
            },
            {
               "department":"MUSC",
               "semester":"S16",
               "name":"School of Music"
            },
            {
               "department":"MUSP",
               "semester":"S16",
               "name":"Music Performance"
            },
            {
               "department":"NACS",
               "semester":"S16",
               "name":"Neuroscience & Cognitive Science"
            },
            {
               "department":"NFSC",
               "semester":"S16",
               "name":"Nutrition and Food Science"
            },
            {
               "department":"PERS",
               "semester":"S16",
               "name":"Persian"
            },
            {
               "department":"PHIL",
               "semester":"S16",
               "name":"Philosophy"
            },
            {
               "department":"PHSC",
               "semester":"S16",
               "name":"Public Health Science"
            },
            {
               "department":"PHYS",
               "semester":"S16",
               "name":"Physics"
            },
            {
               "department":"PLSC",
               "semester":"S16",
               "name":"Plant Sciences"
            },
            {
               "department":"PORT",
               "semester":"S16",
               "name":"Portuguese"
            },
            {
               "department":"PSYC",
               "semester":"S16",
               "name":"Psychology"
            },
            {
               "department":"PUAF",
               "semester":"S16",
               "name":"Public Policy"
            },
            {
               "department":"RDEV",
               "semester":"S16",
               "name":"Real Estate Development"
            },
            {
               "department":"RELS",
               "semester":"S16",
               "name":"Religious Studies"
            },
            {
               "department":"RUSS",
               "semester":"S16",
               "name":"Russian"
            },
            {
               "department":"SLAA",
               "semester":"S16",
               "name":"Second Language Acquisition and Application"
            },
            {
               "department":"SLLC",
               "semester":"S16",
               "name":"School of Languages, Literatures and Cultures"
            },
            {
               "department":"SOCY",
               "semester":"S16",
               "name":"Sociology"
            },
            {
               "department":"SPAN",
               "semester":"S16",
               "name":"Spanish"
            },
            {
               "department":"SPHL",
               "semester":"S16",
               "name":"Public Health"
            },
            {
               "department":"STAT",
               "semester":"S16",
               "name":"Statistics and Probability"
            },
            {
               "department":"SURV",
               "semester":"S16",
               "name":"Survey Methodology"
            },
            {
               "department":"TDPS",
               "semester":"S16",
               "name":"Theatre, Dance and Performance Studies"
            },
            {
               "department":"THET",
               "semester":"S16",
               "name":"Theatre"
            },
            {
               "department":"TLPL",
               "semester":"S16",
               "name":"Teaching and Learning, Policy and Leadership"
            },
            {
               "department":"TOXI",
               "semester":"S16",
               "name":"Toxicology"
            },
            {
               "department":"UMEI",
               "semester":"S16",
               "name":"Maryland English Institute"
            },
            {
               "department":"UNIV",
               "semester":"S16",
               "name":"University Courses"
            },
            {
               "department":"URSP",
               "semester":"S16",
               "name":"Urban Studies and Planning"
            },
            {
               "department":"USLT",
               "semester":"S16",
               "name":"Latina/o Studies"
            },
            {
               "department":"VMSC",
               "semester":"S16",
               "name":"Veterinary Medical Sciences"
            },
            {
               "department":"WMST",
               "semester":"S16",
               "name":"Women's Studies"
            }
         ]


