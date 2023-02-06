# Data Analytics Academy - Project Work 1

The project was carried out entirely in Italian, while it is published in English in order to extend the reach to a greater number of people.

## Overview

Project Work 1 is an integrative work proposed by the Academy offered by Adecco - Avanade. 

The objective is to verify the capacity for synthesis, modeling, organization, analysis and communication in a Project articulated in several phases.

## Data Source

The data source is that from the public Facebook profiles of the 12 course participants. For privacy reasons, they cannot be published to replicate the results. In any case, if there is any doubt, do not hesitate to ask.

The formatting of the collected data was carried out in Google Sheets, and later it was downloaded in Microsoft Excel format to work on-premise.

Data collection, data type classification and the modeling were carried out in group through a brainstorming process on the Miro.com platform.

## Data Model

abstraction and construction of the conceptual/logical model with draw.io

<img width="620" alt="DataModel" src="https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/01_Model-CL.png">

## Database

This and the next steps, until the conclusion of the project, were carried out individually.

Construction of the database with DBMS SQL Server localhost.

https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/02_SQL_CreateTables.pdf

https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/02b_SQL_Diagram.pdf

## ETL process

Data extraction and loading is done with a Microsoft SQL Server Integration Services (SSIS) Project in Visual Studio 2019. The author has decided to do it in this way, in order to implement this renowned ETL tool.

<img width="620" alt="ETL" src="https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/03_EL.png">

## Queries preparation for data extraction

There were defined five objectives of Data Mining. Subsequently, SQL Queries were prepared to answer these analytic goals.

https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/04_SQL-Queries.pdf

## Report and presentation

Finally, the visualization process begins: The connection to the DB is made using the SQL gateway. data extraction and loading is carried out, as well as the creation of graphs. The construction of the report is carried out based on the five analytical objectives proposed above.

Additionaly, the task of this project is to create a hypothetical scenario for the analysis of the available data. For this, it is proposed a fictitious company "NetFliz" interested in evaluating new and diverse investment possibilities, according to the tastes and preferences of existing clients.

Microsoft Power BI has been used to create report, inside it contains an interactive dashboard.

https://github.com/victoria-mascaro/DAAcademy_ProjectWork1/blob/main/05_ProjectWork_MASCARO.pdf

## Built With

•[Power BI](https://powerbi.microsoft.com/en-us/)
•[SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
•Google Sheets
•Microsoft Excel
•[miro Brainstorming](https://miro.com/)
•[draw.io](https://app.diagrams.net/)
