# Real-Time Stock Market Data Pipeline

## Project Overview

This project demonstrates an end-to-end real-time streaming data pipeline using Apache Kafka and AWS cloud services.  
The pipeline streams stock market data in real time from a producer application to a consumer application and stores the streamed data into Amazon S3. AWS Glue and Athena are then used for data cataloging and querying.

---

## Architecture Diagram

![Architecture](real-time-data-pipeline-architecture.png)

---

## Technologies Used

- Python
- Apache Kafka
- AWS EC2
- Amazon S3
- AWS Glue Crawler
- AWS Athena
- Jupyter Notebook

---

## Dataset

Stock market dataset used in this project:

- `indexProcessed.csv`

---

## Producer Code

Producer application continuously sends stock market records into Kafka topics in real time.

### Producer Screenshot

Add your producer code screenshot here.

---

## Consumer Code

Consumer application receives Kafka messages and stores the streamed data into Amazon S3.

### Consumer Screenshot

Add your consumer code screenshot here.

---

# Demo Videos

## 1. EC2 & Kafka Setup

This recording demonstrates:
- Connecting EC2 instance
- Starting Zookeeper
- Starting Kafka server

---

## 2. Real-Time Producer → Consumer → S3 Pipeline

This recording demonstrates:
- Producer sending data
- Consumer receiving data
- JSON files storing into Amazon S3

---

## 3. AWS Glue & Athena Query Execution

This recording demonstrates:
- Glue crawler creation
- Athena table creation
- Query execution
- Table preview and downloading queried data

---

## Workflow

```text
Dataset
   ↓
Kafka Producer
   ↓
Apache Kafka (EC2)
   ↓
Kafka Consumer
   ↓
Amazon S3
   ↓
AWS Glue Crawler
   ↓
AWS Athena
```

---

## Conclusion

Successfully built a real-time stock market streaming pipeline using Kafka and AWS cloud services for ingestion, storage, cataloging, and querying of streaming data.
