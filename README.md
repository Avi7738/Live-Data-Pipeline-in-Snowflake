# Live-Data-Pipeline-in-Snowflake
This project demonstrates the implementation of a live data pipeline using Snowflake, a cloud-based data platform. The pipeline processes data from ingestion to consumption, leveraging Snowflake’s powerful features for real-time data updates and transformation.

## Features

**1. Data Ingestion**

- Extracted order, item, and customer data from an S3 bucket.

- Ensured smooth and efficient data flow into Snowflake.

**2. Snowflake Setup**

- Set up External Stages to access data stored in S3.

- Implemented Snowpipe for automated data loading, enabling real-time processing.

- Established a Landing Zone to store raw data before any transformation.

**3. Stream & Task Mechanism**

- Created Streams to capture and track changes in both the Landing Zone and Curated Zone, ensuring real-time data updates.

- Built Tasks to automate data transformation and maintain a seamless workflow.

**4. Curated Zone**

- Transformed and enriched the data in the Curated Zone, preparing it for business consumption.

**5. Consumption Zone**

- Organized the refined data in the Consumption Zone for analysis, reporting, and decision-making.

**6. ELT Process**

- Followed the ELT process (Extract, Load, Transform) to optimize data handling and ensure real-time availability of up-to-date information.

## Tools & Technologies

- **Snowflake:** Cloud-based data platform

- **AWS S3**: Data storage and ingestion

- **Snowpipe:** Automated data ingestion

- **Streams:** Real-time change tracking

- **Tasks:** Automated workflows for data transformation

## Benefits of the Pipeline

- **Real-Time Processing:** Automated data ingestion and real-time updates using Snowpipe and Streams.

- **Seamless Data Workflow:** Tasks and automated workflows ensure smooth data transformation and enrichment.

- **Scalable Architecture:** Built on Snowflake’s cloud-native features, allowing easy scaling as data volume increases.

- **Enhanced Data Accessibility:** Refined data is readily available for analysis and reporting.

## Key Learnings

This project provided hands-on experience with:

- Setting up and managing External Stages and Snowpipe for data ingestion.

- Building Streams and Tasks to automate workflows.

- Designing and optimizing modern ELT pipelines.

 - Leveraging Snowflake’s robust features for real-time data architecture.

## Contact

For any questions or feedback, please reach out to:

- **Name:** AvinashKumar Rajbhar

- **Email:** avi241882@gmail.com

- **LinkedIn:** https://www.linkedin.com/in/avinashkumar-rajbhar-858133284/

Enjoy exploring and building with Snowflake! 
