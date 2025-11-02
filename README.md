# Data-Warehouse-END-to-END
Will Be updated periodically
ETL - From Source i have incorporated 3 layers bronze, silver, gold layer as my data architecture 
There are multiple standard in data warehouse we can sit with stakeholder to bulidit and then decide what needs to be done.
Task - Design data architecture like building house - blueprint - flow integrate and be accessed. scalable and easyto maintain - brainstorm and design.
data architecture has -1 Data warehouse this is most organised - 2 Data lake good for big data not structured - 3 Data lakehouse is mix of both - 4 data mesh its decentralised .
How to build data warehouse - 4 approaches - 
Inmon Approach --- stage Entreprose data warehouse 3NF - Data Marts (foucus on one like customers and sales and connect to BI.
Kimbaall - stage - Data mart - BI
Data Vault - Stage - Raw Vault - Business Vault (business rules and tranformation  - Data Marts - BI
Medallion Architecture - Bronze(is similar to stage its original as it is and help tracebility and find issues) - Silver ( where we do tranformations and cleansing but dont apply any riules) - Gold (its ike data marts, different objects not only for report but for ML,AI)
We need to decide and confirm one of the above and use it as first step on building architecture.

Secret priciple - SOC - Seperation of Concerns - this is what is bronze, silver and gold layer does.
Naming convention - should have standardised - camel case - kebab case - snake case - we are going with snake case.

Besigning BRONZE - setup meeting with stakeholder - Understand Who own the Data ?, What Business Process it supports ? and System and Data Documentation ?, dara Model and Catalog ? - How is data stored? (SQL,Oracel, AWS)- what are the integration capabilities like API, File extract direct DB, - Incremental VS Full Load, Data scope and Historical Needs - 
