# 🚀 Project Description: Exploring Kafka and AWS
![image](https://github.com/manuelpt49/KafkaPythonAwsProject/assets/79064546/fb048e56-91aa-4a6c-b7a8-002fc929a173) Taken from (https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/Architecture.jpg)

I embarked on this project to deepen my understanding of Kafka while gaining hands-on experience with AWS resources. The journey began by setting up an EC2 instance where I installed and deployed the Kafka server. Using SSH, I connected from my local machine and executed ![scripts](https://github.com/manuelpt49/KafkaPythonAwsProject/blob/main/%23Downloading%20Kafka.txt) to initialize Zookeeper, deploy Kafka, create a topic, and set up a producer and a consumer.

Simultaneously, I ran a Python script in a notebook on my local machine, leveraging the Kafka library. As part of a test, I used a CSV file with numerous rows, randomly sending data to the consumer. The consumer's logic involved creating an S3 bucket to store received elements, simulating real-time data transmission.

With a substantial amount of data in the bucket, I employed a crawler to extract file schemas, creating a serverless database in Athena for efficient querying.

This project provided an in-depth understanding of Kafka's inner workings and the interaction between its services. Overcoming challenges during the deployment of Kafka services on EC2 was a significant learning curve, but persistence paid off.

Additionally, by implementing logic in Python, I explored available libraries to connect with Kafka, expanding my knowledge in the data engineering world.

**Looking ahead, my next milestone involves delving into Airflow and exploring ways to integrate these two powerful tools.**

## 🛠️ Technologies Used:

- Kafka
- AWS (EC2, S3, Athena, Glue)
- Python

## 🌐 Project Repository: [Link to Repository]

*Special thanks to Darshil Parmar for sharing his knowledge on his YouTube Channel.* https://www.youtube.com/watch?v=KerNf0NANMo
