# Weather Data Processing using Hadoop MapReduce

## Description

This Hadoop MapReduce program processes weather sensor data logs and extracts the **maximum temperature for each year**.

## Prerequisites

Ensure you have the following installed:

- Java (JDK 8 or later)
- Apache Hadoop (v3.x recommended)
- HDFS set up and running

## Dataset Format

The dataset should have fixed-width fields:

- **Year**: Positions 15-19
- **Temperature**: Positions 87-92

### Example Record:
