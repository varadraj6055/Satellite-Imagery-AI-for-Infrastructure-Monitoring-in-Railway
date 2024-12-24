Satellite Imagery for Railway Infrastructure Monitoring

Project Overview

This project leverages high-resolution satellite imagery (1-3 meters) and AI-based object detection models to monitor and assess railway infrastructure. The goal is to detect anomalies, such as cracks or vegetation encroachment, and monitor the condition of tracks and bridges using state-of-the-art technologies.



Features

High-Resolution Imagery: Captures detailed features of railway infrastructure for accurate monitoring.

AI-Powered Object Detection:

Models used: YOLO, Faster R-CNN, and SSD.

Applications: Identifying rail tracks, bridges, vegetation, and detecting anomalies.

Big Data Integration:

Process and analyze large-scale imagery using Apache Spark.

Cloud-based storage for scalability and real-time data access.

Visual Insights: GIS integration and dashboards for anomaly visualization and reporting.

Workflow

Data Collection:

Acquire satellite imagery from sources like Sentinel-2 or Maxar.

Annotate images with domain-specific features.

Preprocessing:

Georeference and align imagery.

Enhance resolution and remove noise.

Model Training:

Train object detection models (YOLO, Faster R-CNN, SSD) using annotated datasets.

Fine-tune models for railway-specific anomalies.

Big Data Processing:

Use distributed frameworks like Apache Spark for imagery analysis.

Store results in NoSQL databases for efficient retrieval.

Visualization:

Display detected anomalies and conditions on GIS platforms.

Provide real-time monitoring through interactive dashboards.

Installation and Setup

Clone the repository:

git clone <repository-url>
cd railway-infra-monitoring

Install dependencies:

pip install -r requirements.txt

Download and preprocess satellite imagery.

Train models using the provided training scripts.

Deploy the pipeline for real-time monitoring.

Technologies Used

AI Models: YOLO, Faster R-CNN, SSD

Programming: Python, TensorFlow, PyTorch

Big Data Tools: Apache Spark, Hadoop

GIS Tools: QGIS, ArcGIS

Visualization: Tableau, Power BI

Contributions
our Whole Team Worked Together 
Members 1: Kharosekar Varadraj Abhay
Member 2 : V Tharun 
Member 3: Ransingh Vedant 
Member 4: Ashraf M
Member 5 : Khan Samim Masud

We welcome contributions to enhance the project. Feel free to fork the repository and create pull requests.
