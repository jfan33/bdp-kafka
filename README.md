# bdp-kafka

## Quick resources:
 * [Github desktop](https://desktop.github.com/) -- easy source control via a GUI
 * [Docker for Windows Pro](https://store.docker.com/editions/community/docker-ce-desktop-windows)
 * [Docker for Windows Home](https://www.docker.com/products/docker-toolbox)
 * [Docker for Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac)
 * [Kafka Docker](https://hub.docker.com/r/wurstmeister/kafka/) Docker images with instructions on how to install
 * [Kafka Docker Repository](https://github.com/wurstmeister/kafka-docker) -- Repository for up to date kafka docker images
 * [Kafka project page](https://kafka.apache.org/)

## Dataset
 * [Credit card fraud](https://www.kaggle.com/dalpozz/creditcardfraud) 
 * Add three fake columns to the original dataset: unique user ID, user type (international or domestic), unique account number
 * Columns appended will be used in aggregation in application.
 
## Kafka Introduction and Stories
Apache Kafka is a distributed open-source streaming platform developed by the Apache Software Foundation written in Scala and Java. 

Apache Kafka was originally developed by LinkedIn, and was subsequently open sourced in early 2011. In November 2014, several engineers who worked on Kafka at LinkedIn created a new company named Confluent with a focus on Kafka. According to a Quora post from 2014, Jay Kreps seems to have named it after the author Franz Kafka. Kreps chose to name the system after an author because it is "a system optimized for writing", and he liked Kafka's work. 

Kafka aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds. Kafka could also connect to external systems for data import or export via Kafka Connect and provides Kafka Streams.

![](bdp-kafka/images/kafka%20structure.png)

## Kafka's Advantages in Messaging
In comparison to most messaging systems Kafka has better throughput, built-in partitioning, replication, and fault-tolerance which makes it a good solution for large scale message processing applications.

## Metric - Application
Kafka is often used for operational monitoring data. This involves aggregating statistics from distributed applications to produce centralized feeds of operational data. 

## Sream Processing
 * Concept: Many users of Kafka process data in processing pipelines consisting of multiple stages, where raw input data is consumed from Kafka topics and then aggregated, enriched, or otherwise transformed into new topics for further consumption or follow-up processing.
 * Library: stream processing library called Kafka Streams is available in Apache Kafka
## Project Overview
TBD

## Docker Intallation
 * Fraud detection model
