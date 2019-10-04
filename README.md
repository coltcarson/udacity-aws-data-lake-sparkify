# Music Streaming Data Lake (AWS)

For this project, we created a music streaming data lake ETL pipeline using S3 and Python. We began by using Python to extract user listening and song metadata JSON files from S3 buckets so that they could be staged and transformed within an AWS Data Lake.

--------------------------------------------

# Schema
![Data Lake Schema](https://github.com/coltcarson/udacity-aws-data-lake-sparkify/blob/master/Udacity%20DE%20Project%20%233.png)

--------------------------------------------

# Files
1) etl.py - Script copies data to enviroment for transformation then inserts data into dimension tables on S3
3) dl.cfg - Stores AWS Login Credentials.

--------------------------------------------

# Instructions
1) Create or navigate to an AWS S3 bucket and add the required aws login credentials to the dl.cfg file.

2) Type run etl.py in your terminal to start the ETL process.
