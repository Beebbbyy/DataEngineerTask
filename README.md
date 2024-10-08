# DataEngineerTask

## Overview

This project processes XML files and converts them into relational tables using PySpark. The goal is to extract specific data from an XML structure, convert it into PySpark DataFrames, and save the results as Snappy-compressed Parquet files.

## Project Structure

- **transformation.ipynb**: This notebook contains the core logic for reading XML files, transforming them into DataFrames, and saving them as parquet files.
- **test_xml_processing.ipynb**: This notebook contains unit tests to validate the XML processing logic.
- **sample_data.xml**: A sample XML file that is used as input for the transformation logic.
- **output**: This directory will contain the generated parquet files after running the transformation logic.

## Prerequisites

Ensure the following are installed:

- Python 3.x
- PySpark
- unittest or pytest for testing

You can install the required Python libraries with:

```bash
pip install pyspark lxml pytest
