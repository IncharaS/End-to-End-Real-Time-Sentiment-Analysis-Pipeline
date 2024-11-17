#  End-to-End Real-Time Sentiment Analysis Pipeline  

This project demonstrates how to build an end-to-end real-time data engineering pipeline that streams, processes, and analyzes customer reviews using **TCP/IP Sockets, Apache Spark, OpenAI LLM (ChatGPT), Kafka, and Elasticsearch**.  

The system continuously ingests customer reviews from **Yelp**, processes them with **Apache Spark**, performs sentiment analysis using **OpenAI ChatGPT**, publishes the results to **Kafka**, and finally indexes the data in **Elasticsearch** for fast querying and visualization. This solution is designed to handle real-time data streams efficiently, making it an ideal reference for those looking to build scalable and production-ready **data pipelines**.  

### Key Components  
- **Data Source:** Uses the **Yelp dataset** as a source of customer reviews.  
- **TCP/IP Socket:** Streams data over the network in real-time.  
- **Apache Spark:** Processes the data efficiently using its distributed computing framework.  
- **Confluent Kafka:** Handles real-time streaming and message brokering on the cloud.  
- **Control Center & Schema Registry:** Monitors Kafka streams and manages schemas.  
- **Kafka Connect:** Bridges Kafka topics to Elasticsearch for seamless integration.  
- **OpenAI ChatGPT:** Performs **real-time sentiment analysis** on customer reviews.  
- **Elasticsearch:** Indexes and stores processed sentiment data for efficient querying and visualization.  

##  Technologies Used  
- **Python** - Core language for data processing and integration  
- **TCP/IP Sockets** - Streaming raw data over the network  
- **Apache Spark** - Distributed computing for efficient data processing  
- **Confluent Kafka** - Real-time message streaming  
- **Docker** - Containerized deployment for easy scalability  
- **Elasticsearch** - High-performance indexing and querying  
