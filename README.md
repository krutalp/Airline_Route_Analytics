# Evaluating and Optimizing Passenger Airline Routes using Graph Anomaly Detection

## 553.602 Research and Design in Applied Mathematics: Data Mining

### Team Members: Krutal Patel, Mansi Goel, Chenyu Xie, Nihaar Thakkar   

### Subject Area: Transportation Optimization, Transportation Science 

### Proposed Research: 

Air transportation plays an essential role in modern society by connecting people and business. The success and efficiency of transportation is significantly impacted by the airline route design. Two major route models in air transportation are the point-to-point model and the hub-spoke model. In the hub-spoke model, there’s a central hub where all flights come together from origins and passengers can change flights to reach their destinations. On the contrary, the point-to-point model operates with direct flights between origins and destinations. Without a central hub, the point-to-point model is vulnerable to delays since a delay at an airport could result in a chain reaction of delays and cancellations by impacting the flights through the network and scheduling challenges of coordinating flights. Southwest Airlines, one of the largest airline companies in the United States, operates under a point-to-point model. Recent delays in their flights lead to an investigation of potential causes of the disruptions and raise questions about the model they implement. The goal of this project is to optimize Southwest Airline routes by examining the route patterns for airlines that utilize hub-spoke models such as United and Americans and perform Graph Anomaly Detection to determine potential hubs and essential routes for Southwest Airline, aiming to achieve high profits and lower delays. 

### Technical Plan: 

The main goal of this project is to analyze route patterns for airlines which deploy the hub-spoke model and apply Graph Anomaly detection algorithms to extract possible hubs and significant routes for Southwest Airlines, which uses point-to-point models.  

1. Collect datasets on Aircraft Type, Route Demand, Airline Routes, associated costs for airports and routes, associated profits for airports and routes, delay and cancellations data for each airport 
2. Clean the datasets and reorganize data into appropriate tables with associated attributes. For example, node and edge attribute tables 
3. Conduct exploratory Data Analysis on current route models and airline patterns by querying datasets from current Airlines such as American, Delta, United  
4. Develop attribute-enriched graph objects to model airline routes from datasets.  
5. Create scalable methods to extract node and edge attributes 
6. Conduct Data Analysis to determine route patterns, properties of hubs, demand of certain routes 
7. Optimize routes for Southwest in two ways, one using a simulation technique with Graph Anomaly Detection, and the other using nonlinear programming.  
8. Deploy embedding methods to analyze network properties and apply techniques such as Graph Neural Networks, Node2vec  
9. Develop an LP or NLP: create objective function with constraints to minimize costs and maximize profits
10. Compare Hub-and-spoke model with point-to-point model using the two techniques. 
11. Develop specific hub airports Southwest should denote in their model and locate specific routes that could be removed.  
12. Simulate projected profits of the proposed route plan. 

Potential Impact: 

We hope to suggest a well-formulated plan that can help Southwest Airlines improve their current route model. In the future, this might lead to reduced delays and discrepancies, especially during busier times like the holidays. Suggesting a Hub-and-spoke model for Southwest may lead to increased efficiency by reducing costs and centralizing operations at a hub.  The hub-and-spoke model will provide more connecting options to passengers, enabling them to reach more destinations indirectly. The conversion to a hub-and-spoke model may have a positive or negative impact on economic competitiveness between various airline companies, depending on the location of the hub airport and its accessibility to surrounding areas.  
