# -Data-flow-from-Kafka-to-Hadoop
This project aimed to build a data pipeline from Apache Kafka to Hadoop, enabling efficient collection, storage, and processing of large datasets. Data from various sources is collected through Kafka and then pushed to Hadoop for real-time storage and analysis.

Methods: Two approaches were proposed to implement the data pipeline:
- MongoDB -> Kafka -> Hadoop
![image](https://github.com/user-attachments/assets/f60129ea-55f7-4865-9e2b-8a86c8e627cf)

- API -> Kafka -> Hadoop
![image](https://github.com/user-attachments/assets/0ef879ca-7fd9-47d7-b95f-defedb1daa26)


Data Used: The data was sourced from the Aviationstack website, which provides real-time and historical flight information. The raw data was then processed and filtered to retain essential details such as flight codes, flight dates, departure and arrival airports, time zones, takeoff times, and airline names.

Results: The data pipeline was successfully built, and the data processing steps were carried out. The outcomes include data transmission flows from MongoDB and the API to Kafka, followed by data transfer to Hadoop. Reports and presentation slides outlining the project execution and results were also completed.
