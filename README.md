# Analyzing-Cinematic-Ratings-with-Hadoop-Ecosystem
Project Description

Analyzing Cinematic Ratings with Hadoop Ecosystem  is a Big Data analytics initiative designed to process and analyze movie feedback utilizing a distributed computing architecture. The project demonstrates a complete, conventional Big Data workflow from raw data ingestion to structured querying, leveraging the Hadoop ecosystem to calculate average movie ratings and identify top-performing cinematic titles.


Core Workflow
The project follows a structured pipeline to seamlessly handle and transform the dataset:


Data Ingestion & Storage: A movie-centric CSV file containing audience feedback and metadata—including unique user identifiers, movie titles, and numerical ratings on a 1–5 scale—is uploaded and held securely within the Hadoop Distributed File System (HDFS).



Distributed Processing: A custom Python-based MapReduce framework operates via Hadoop Streaming. The Mapper script extracts movie titles and pairs them with their respective ratings, while the Reducer script aggregates this data to compute the precise mean rating for every unique film.



Data Warehousing: The processed output is saved back into HDFS and subsequently loaded into Apache Hive. A dedicated table schema (movie_avg) is formulated to structure the aggregated results.



Analytics & Discovery: Using structured HiveQL queries, the processed results are analyzed to order the data and filter out the top five highest-rated movies based on their calculated average scores.


Technology Stack

Storage Environment: Hadoop Distributed File System (HDFS) 


Processing Engine: Hadoop Streaming utilizing Python for MapReduce logic 


Data Warehousing & Querying: Apache Hive 


Development Environment: Linux Command Line Interface 


AI Integration: Generative AI was employed as a high-level assistant for drafting Python scripts, resolving logical bottlenecks, optimizing SQL queries, and deepening technical comprehension of the Hadoop framework.

