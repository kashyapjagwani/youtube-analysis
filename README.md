# Youtube Analysis using Python, Postgres, and Tableau
Developed a data pipeline in Python to consume YouTube Data API to fetch data about Pewdiepie’s channel and stored it on AWS RDS - Postgresql and visualized data using Tableau to create a dashboard

1. I started off with fetching Pewdiepie's uploaded videos and transfored data into a Pandas dataframe with 6 columns - video_id, video_title, upload_date, view_count, like_count, comment_count.
2. Next, I uploaded the dataframe onto an AWS RDS - PostgreSQL.
3. Finally used Tableau to visualize the data and create an analysis of Pewdiepie's channel like in which month is the channel getting most views, etc.
