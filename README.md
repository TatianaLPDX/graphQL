# Wikipedia Voting Patterns with Graph Databases

## Project Objective:
Wikipedia is a free encyclopedia written collaboratively by volunteers around the world. 
A small part of Wikipedia contributors are administrators (users with access to additional technical features that aid in maintenance).
In order for a user to become an administrator, a Request for adminship (RfA) is issued and the Wikipedia community via a public discussion or a vote decides who to promote to adminship. 

The main objective of the project is to examine and analyze voting data via graph databases (such as GraphQL and Neo4j), perform data analysis, and graph presentation of the findings.

## Project Approach:
The project will be implemented on 2 separate graph database systems: GraphQL and Neo4j. The systems are very different in the way they create graph databases (GraphQL performs transformation to graph data after API ingestion, while Neo4j initially requires user to create graph models). It would be interesting to see both approaches and examine their advantages and disadvantages.

## Team Structure:
The project will be implemented by 1 person, Tatiana Luchian. So I will be completing all of the  functions on the project (project management, data cleaning, data transformation, implementation, analysis, and reporting)

## Project Milestones:

| Task       | Description        |Due Date  |Status  |
| ------------- |:-------------:| -----:|-----:|
| Data Cleaning     | Pre-process and clean data for API ingestion and data model | 07/10 |COMPLETED |
| Data Model Creation      | Design data model and relationships in the model for Neo4j. Via python script transforms the data.      |   07/15 | COMPLETED |
| DB creation in Neo4j  | Create a script to populate transformed data into Neo4j, create a graphical presentation of the data.      |    07/25 |In progress |
|Graph creation in GraphQL | Upload data to BigQuery, create API call for GraphQL.      |   07/30 |In progress |
|Data analysis & reporting | Perform data visualization and analysis of findings, document, and present the findings via the final presentation.      |    08/10 |Not started |
