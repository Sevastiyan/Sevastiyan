# Wethm Sleep Intelligence Hub

[< Back to Portfolio](https://github.com/Sevastiyan/Sevastiyan)

A fault-tolerant backend capable of processing millions of bio-signal data points per hour to power real-time sleep detection and personalized insights.

---

### The Challenge: Building a Scalable Sleep Analytics Platform

Wethm's vision was to provide users with real-time, actionable insights into their sleep patterns. This required a backend system that could ingest and process a massive volume of bio-signal data from thousands of mattress sensors concurrently, with near-instantaneous results. The core challenges were ensuring extreme reliability, low-latency processing for a seamless user experience, and designing a data architecture optimized for heavy, time-series-based write loads.

---

### The Solution: An Event-Driven, Serverless Architecture

I engineered a high-throughput, fault-tolerant data pipeline on AWS. The system was designed to be event-driven and serverless, leveraging AWS Lambda for processing and DynamoDB for storage. This approach ensured that the platform could scale automatically to handle fluctuating loads while maintaining consistent performance and cost-efficiency.

**Key Architectural Features:**

*   **High-Throughput Data Ingestion:** A robust pipeline capable of handling millions of data points per hour without degradation.
*   **AI-Powered Analytics:** Integrated custom AI models for real-time bio-signal analysis, significantly improving the accuracy of sleep pattern and vital sign detection.
*   **Optimized Time-Series Database:** A custom-designed DynamoDB schema built to handle heavy write operations and complex time-series queries efficiently.

#### Core Technologies Used:

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=AWS%20Lambda&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

---

### Key Achievements & Impact

This project successfully transformed raw sensor data into a premium, subscription-worthy user experience. The platform not only met but exceeded performance targets, establishing a new standard for non-invasive sleep monitoring.

*   🚀 **Massive Scalability:** Connected thousands of devices into a unified analytics ecosystem.
*   💡 **Actionable Insights:** Delivered personalized sleep reports and recommendations to premium users, leading to user-reported improvements in sleep quality.
*   📈 **Clinical-Grade Accuracy:** Achieved stable and clinically relevant vital sign measurements (heart rate, breathing rate) from contactless sensors.
*   🔒 **Rock-Solid Reliability:** Ensured 99.99% uptime through a resilient and fault-tolerant infrastructure design.
*   Embedded AI: Optimized and deployed AI models on resource-constrained embedded devices for on-device processing.
