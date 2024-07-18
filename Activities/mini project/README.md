# use Data bricks to pull raw S3 data, transform it, and push it back to S3 to upload it to snowflake
## data ingestion
### ingested raw song and user log data and saved it as dataframes in spark.
## data transformation
### transformed date to timestamp. extracted data from the raw sources and saved it in seperate dataframes to be cleaned. did a join between the song and log data and extracted columns into a song facts table
## data load
### pushed the transfomred dataframes of song, artist, user, time, and songfacts to S3 to load into snowflake through external stages
## data analysis
### ran basic queries and analysis to verify the data populated into snowflake 

![mini project diagram](https://github.com/user-attachments/assets/da8fbc7b-e1e9-47ed-a0c6-dcb63495bacb)
mini project diagram.jpg)
