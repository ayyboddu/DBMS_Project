# DBMS_Project
Database Translation Project

## Project Overview

This project involves restructuring the dataset obtained from the GitHub Events API (https://api.github.com/events) to make it suitable for loading into a SQL or Graph database. We have opted to use a Graph database for this purpose and will be implementing the solution in Python. The primary reason for choosing Python is its availability of various libraries that facilitate working with graph databases, such as Py2neo for Neo4j and Graphene for ArangoDB.

## Project Goals
The main objective of this project is to transform the raw JSON data from the GitHub Events API into a format that can be efficiently stored and queried in a Graph database. The process will involve creating nodes for each data entry and establishing relationships between them, preserving their respective properties.

## Implementation Plan
To achieve our goal, we will follow this step-by-step plan:

**Data Preparation**: We will begin by loading the JSON data into Python objects, such as dictionaries or lists, using the built-in json module. This will enable us to process and manipulate the data effectively.

**Choosing the Graph Database**: Based on our preference for Graph databases, we will select an appropriate library or driver that provides the necessary APIs to interact with the chosen graph database. The choice of the specific graph database will depend on the requirements and capabilities of the project.

**Connecting to the Graph Database**: Once the appropriate library or driver is chosen, we will establish a connection to the selected graph database from our Python environment.

**Creating Nodes**: For each entry in the JSON data, we will create a corresponding node in the graph database using the chosen graph database library or driver. This step will involve mapping the data fields to appropriate node properties.

**Customizing Node Properties**: The node properties will be customized using the data from the JSON entries. This will involve setting the properties to the corresponding values from the dataset.

**Establishing Relationships**: For each relationship in the JSON data, we will create a corresponding relationship in the graph database using the graph database library or driver. Identification of the start and end nodes of the relationship will be based on their unique IDs or specific properties.

**Verification and Testing**: Once the data has been successfully imported into the graph database, we will perform thorough verification and testing to ensure the accuracy and integrity of the transformed dataset.

## Link to final presentation

https://docs.google.com/presentation/d/1ItgLWj-AeQUp7Aw7RLaNI7VWalgrsyWA8p7I7DH9BJg/edit#slide=id.g23784840e88_0_307
