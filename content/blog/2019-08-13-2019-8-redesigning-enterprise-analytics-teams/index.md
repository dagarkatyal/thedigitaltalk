---
title: "Redesigning Enterprise Analytics Teams"
date: "2019-08-13"
categories: 
  - "analytics"
  - "tips"
tags: 
  - "ai"
  - "analytics"
  - "bi"
  - "business-intelligence"
  - "data"
  - "data-engineering"
  - "maturity"
  - "modern-data-platform"
  - "organization"
  - "strategy"
  - "tips"
  - "zero-based"
cover:
    image: "images/img-1.jpg"
---


Cloud technologies are changing the way we operate and do business. They enable us to focus the time and energy of the resources in developing applications rather than spending time on the maintaining the infrastructure. While cloud technologies enable business to take the leap it is vital to understand how these technology impact the organizations and change the organization models.

This article talks about the changing structure of analytics organizations in the enterprise which traditionally had fully scaled analytics teams. The analytics teams in large organizations have many aliases such as “Data team”, “BI team”, “Central data organization”, “BI CoE” etc. These large teams consisted of multiple roles and clear defined responsibility. In a typical organization it would not be very difficult to see roles such as ETL Developer, BI developer, BI Server Admin, QA, Data Modeler, DBA, Data Analyst, and Data Scientist. All these roles had a clear line of responsibilities but caused overheads because of increased hand-offs and too many points of failure because of shared responsibility.

Along with the technology shift, it has become almost vital to look forward newer organization models that keeps the focus at the business outcomes and reduces the overheads. This goes with the concepts of “Zero Based Thinking”.

 Zero Based Thinking or Zero Based Principal is a decision-making process based on imagining yourself back at the point before particular decisions were made, and free to make those decisions with the knowledge that you have now about their outcome. This is essentially putting your decision to trial. 

> Zero-basing organizations, which use zero-based principles as a lens to reshape organizational structure and operations, can unleash greater productivity. The resulting purpose-built enterprise ensures that staff and resources are allocated to the highest-value areas of the business. 
> 
> \-McKinsey 

Organizations need leaner and agile structure to focus on the business outcome. Following are the key roles that should be part of the analytics organization which is focused solely on delivering business value

### Data Engineer

This role has been talked about almost everywhere, and is the anchor of the complete team. This is not just an ETL Developer, a DBA, a report writer, Bi administrator. But is a mix of all these roles. These are the group of people responsible for setting up the relevant infra, provisioning resources, setting up access, sourcing data, manipulating data, wrangling data, making the data available to end users and helping the organizations consume data. In short, whenever, data is accessed, manipulated or written, it is handled by data engineers

### Data Scientist

This is a specialized skill which every data driven organization need. Data scientist consume the data wrangled by data engineers and use complex equations and statistics to write a models. These models understands the patterns in the data and can tell the next expected outcome with certain confidence. This the role that take analytics to higher maturity levels.

### AI Engineer

Not many people have been talk about this role. I feel this is going to be the next important role in the organization. There is huge advancement in field of the commercial AI or COTS AI services such as Speech recognition, Image recognition API, text analytics, search, and bots. These commercial AI products enable rapid application creation and use of pre-built pre-trained ML models for prediction. Since these models are pre-build, there is not much for the data scientists, but a special category of resources who use these AI products and create applications in very short time 

With the advent of self-service BI tools such as Power BI and Tableau the report writing has moved to business users. The maintenance roles have slowly started disappearing because of cloud. QA skills will be part of development teams because of move towards dev-ops. So I feel the three roles mentioned above will provide all key skills in order of an analytics team to succeed.
