This code is submitted to Waystar as part of the interview requirements for Cloud Engineer position


This code is submitted by Sope Ogundipe. Base code was forked from 

This is a URL Shortener API witten in Python and SQLite 

Flask is used as the framework for creating the environment and running the code. 

The python library - Hashids is used to generate unique IDs from integers

The following steps were followed:
STEP1. I set up the required dependencies for my environment (Python, Hashids and Flask)

STEP2. I created the database schema. The schema creates a table that stores records for the original (long) URL and the shortened URL generated from a hash string. 
For monitoring, the code also sores values for the number of times the shorted URL value has been cliked. 

STEP 3. I initialised the database 

STEP 4. User Interface. The styling is done using Bootstrap and the index.html file is used to define the user interface.

STEP 5. The app is run and the url http://127.0.0.1:5000 is generated if the build is sucessful. 

STEP 6. Test
To test, I entered the a URL and clicked the submmit button. It succesfully returned a shortened URL with the hash
I also tested the short URL in a browser and it redirects to the long URL

Statistics:
When URL is clicked , a count of the number of times increases. This is vieable from the URL http://127.0.0.1:5000/stats
