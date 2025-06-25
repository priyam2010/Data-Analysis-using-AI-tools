# Data-Analysis-using-AI-tools
## Introduction
In today’s fast-paced business environment, data often arrives through various channels, including email. Automating the process of identifying, extracting, storing, and analyzing such data can significantly reduce manual effort and improve decision-making. This project leverages n8n, PostgreSQL, and Quadratic (AI Spreadsheet) to build an end-to-end data automation and analysis pipeline.

##  Problem Statement
Many organizations receive critical data in the form of email attachments—such as reports, logs, or CSV files—which need to be processed regularly. Manually monitoring emails, extracting data, and preparing it for analysis is time-consuming, error-prone, and inefficient. There is a need for an automated system that can:

Detect and trigger actions based on specific email subjects.

Extract relevant data from attached files.

Store the data in a structured database.

Enable seamless and intelligent analysis with minimal manual intervention.

## Conclusion 
The implemented solution successfully automated the data pipeline from email ingestion to analysis. Using n8n, the system efficiently monitors and processes incoming emails based on custom triggers. Extracted data is loaded into PostgreSQL, ensuring structured and queryable storage. Quadratic then enables fast, AI-assisted exploration and insight generation. This solution not only reduced manual effort but also improved the speed and accuracy of data-driven decision-making.
