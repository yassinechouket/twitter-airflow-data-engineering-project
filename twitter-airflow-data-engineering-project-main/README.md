# twitter-airflow-data-engineering-project


This project involves creating an ETL (Extract, Transform, Load) pipeline to retrieve tweets from a specific user on Twitter (e.g., Elon Musk), transform the data, and store it in a PostgreSQL database. The project is orchestrated using Airflow and deployed on AWS EC2 to run continuously. The pipeline includes:

Extraction: Fetching tweets via the Twitter API.

Transformation: Processing and cleaning the retrieved data (extracting key information like tweet text, number of likes, and retweets).

Loading: Storing the transformed data into a PostgreSQL database hosted on an EC2 instance.

The pipeline is automated to run at regular intervals, enabling the continuous collection and analysis of Twitter data, such as trends, user engagement, and interactions.
