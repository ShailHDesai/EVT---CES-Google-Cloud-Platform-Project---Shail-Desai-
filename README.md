# EVT-CES Google Cloud Platform Project

This repository contains all the source code and documentation for the EVT-CES project, developed using Google Cloud Platform (GCP) and integrated with Firebase, MongoDB, and BigQuery. The project focuses on creating a scalable cloud-based solution to collect, store, and analyze Electric Vehicle Telematics (EVT) data, providing real-time insights for vehicle performance and fleet management.

## Project Overview

The EVT-CES project leverages GCP and related services to create a connected data ecosystem for electric vehicles. By integrating Firebase for real-time updates, JSON for data formatting, and APIs for secure data transmission, the project ensures efficient collection and processing of vehicle telematics data. MongoDB is used for flexible data storage, and BigQuery powers advanced analytics and reporting capabilities.

### Key Components:
- **Data Ingestion via APIs**: EVT telemetry data is collected through secure APIs, formatted using JSON, and transmitted to cloud services.
- **Firebase Integration**: Real-time updates on vehicle data and notifications are managed using Firebase.
- **Data Storage**: MongoDB is employed to store unstructured vehicle data, while BigQuery handles large-scale data analysis.
- **Data Analytics**: Using BigQuery, the project performs comprehensive analysis on vehicle telemetry to generate actionable insights.
- **Dashboard and Reporting**: A dashboard interface visualizes data trends and allows for the generation of custom reports, which help predict maintenance needs and monitor vehicle performance.

## Repository Structure
- `CIT-41200-Final-Project-master`: Contains final project files.
- `Project Submission - TEAM ORANGE`: Files related to the EVT-CES project submission.
- `Electric Vehicle PDFs`: Reference materials and documentation for the project.
- `Project Architecture Poster.pptx`: Visual representation of the project architecture.
- `README.md`: This file, providing an overview and details about the project.

## Technologies Used
- **Google Cloud Platform (GCP)**: Main platform for hosting and managing the project.
- **Firebase**: For real-time database and notifications.
- **RESTful APIs**: To securely transfer telemetry data.
- **MongoDB**: NoSQL database for storing EVT data.
- **BigQuery**: For performing large-scale data analytics.
- **JSON**: Data format for API communication and telemetry data processing.

## Getting Started

To get started with the project:
1. Clone the repository.
2. Review the project files and documentation.
3. Follow the setup instructions to deploy the project on GCP and configure Firebase, MongoDB, and BigQuery integrations.

## License
This project is licensed under the MIT License – see the LICENSE file for more details.
