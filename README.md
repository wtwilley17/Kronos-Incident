# Kronos-Incident
### The Kronos Incident: Geospatial-Temporal Patterns of Life Analysis

This project revolves around tackling the complex mystery presented by the VAST Challenge in January 2014. The enigmatic disappearance of GAStech employees during their company's IPO celebration, with suspicions pointing towards the Protectors of Kronos (POK), creates a compelling backdrop. GAStech's secretive geospatial tracking software, concealed within company vehicles, serves as a crucial data source, despite missing data for the critical day of the disappearance. Law enforcement has also provided access to two weeks of credit and debit card transactions and loyalty card data for local GAStech employees.

As a data science expert aiding the investigation, our mission is to harness the power of data visualization and analytics to decipher this information. We must unravel the complexities arising from incomplete and inconsistent data to identify suspicious behavioral patterns and prioritize leads related to the missing personnel. This project embarks on a journey through data exploration and visualization to shed light on the enigma of the missing GAStech employees and assist law enforcement in their quest for answers.

## Data Visualization 
The visualization phase of the project used Plotly Dash to provide an interactive and comprehensive representation of the cleaned and merged data. The integration of Plotly Dash component tabs facilitated a structured and user-friendly interface for exploring the diverse facets of employee movement and behavior. 

### Truck Driver Movement Tab: 
![truck page](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/df480ca8-aafd-4d15-b7de-540edd320f70)

The first tab, dedicated to "Truck Driver Movement," addresses the unique challenge of 
identifying truck drivers for various routes and dates. The dynamic graph displayed on this tab enables 
users to select specific routes and dates. By correlating the GPS data with the truck routes, this 
visualizaƟon aids in pinpoinƟng the responsible truck driver for each route on disƟnct occasions. This 
insight provides clarity into truck driver assignments and route allocation, contributing to a 
comprehensive understanding of the geospatial-temporal patterns associated with truck drivers.

### General Employee Movement Tab: 
![geeneral tab](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/16dd1ec6-52b7-470e-b7bb-8e37a93f3f16)

The second tab introduced an intuitive dropdown menu enabling the selection of distinct 
employee categories. An addiƟonal Ɵme dropdown facilitated the isolation of movements during specific 
periods of the day. The chosen parameters dynamically updated the graph, allowing users to visualize 
employee movement patterns based on their category and chosen time. Complementing the graph, a 
table provided details, enhancing the understanding of employee trajectories. A weekend radio buƩon
was added, to switch between weekday and weekend views. This option aimed to unveil disparities in 
general employee movement behaviors between these timeframes.


### Individual Employee Movement Tab: 
![individual](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/1ec21ee7-fafc-42f5-bcc7-d8f9b40b3abd)

In the "Individual Employee Movement" tab, users can select an employee's name, along with a 
date and Ɵme range. The resulting graph provides a detailed trajectory of the selected employee's 
movement during the specified period. A supplementary table showing card transaction data is 
posiƟoned under the graph. This integration facilitates a comprehensive analysis, enabling users to 
discern potential anomalies or irregulariƟes in an individual employee's movement patterns and 
associated financial activities. By comparing movement data with card transactions, this tab supports the 
identification of suspicious behaviors and aids in confirming the legitimacy of transacƟons






