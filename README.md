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
visualization aids in pinpoinƟng the responsible truck driver for each route on distinct occasions. This 
insight provides clarity into truck driver assignments and route allocation, contributing to a 
comprehensive understanding of the geospatial-temporal patterns associated with truck drivers.

### General Employee Movement Tab: 
![geeneral tab](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/16dd1ec6-52b7-470e-b7bb-8e37a93f3f16)

The second tab introduced an intuitive dropdown menu enabling the selection of distinct 
employee categories. An additional time dropdown facilitated the isolation of movements during specific 
periods of the day. The chosen parameters dynamically updated the graph, allowing users to visualize 
employee movement patterns based on their category and chosen time. Complementing the graph, a 
table provided details, enhancing the understanding of employee trajectories. A weekend radio button
was added, to switch between weekday and weekend views. This option aimed to unveil disparities in 
general employee movement behaviors between these timeframes.


### Individual Employee Movement Tab: 
![individual](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/1ec21ee7-fafc-42f5-bcc7-d8f9b40b3abd)

In the "Individual Employee Movement" tab, users can select an employee's name, along with a 
date and time range. The resulting graph provides a detailed trajectory of the selected employee's 
movement during the specified period. A supplementary table showing card transaction data is 
positioned under the graph. This integration facilitates a comprehensive analysis, enabling users to 
discern potential anomalies or irregularities in an individual employee's movement patterns and 
associated financial activities. By comparing movement data with card transactions, this tab supports the 
identification of suspicious behaviors and aids in confirming the legitimacy of transactions

## Anomalies

Who : Loreto Bodrogi , Isia Vann, Minke Mies, Hennie Osvaldo    
When : Midnight – Early Morning | 7,9,11 and 14 January     
Where : Executive Houses (Ada Campo Corrente, Orhan Strum, Willem Vasco Pais, and Ingrid Barranco)     

![shift table](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/b9064698-eb8b-4990-8a88-846cd526b591)

Anomalies from the graphed general movement of the employee have shown a group of 
individuals who needs further investigation: Loreto Bodrogi, Isia Vann, Minke Mies, and Hennie 
Osvaldo – all of whom hold positions within GAStech's security division. Intriguingly, their 
activities have been notably conspicuous during the midnight to early morning hours on specific 
dates: January 7th, 9th, 11th, and 14th. What sets these instances apart is the fact that their GPS 
locaƟons seem to converge at the residences of prominent executives, namely Ada Campo 
Corrente, Orhan Strum, Willem Vasco Pais, and Ingrid Barranco. Such patterns raise suspicions, 
suggesting potential ulterior motives. Given the context of a kidnapping investigation in this 
project, it is possible that these security personnel could be linked to the abduction. Their 
seemingly suspicious actions and location near executive houses could indicate a deeper 
involvement, possibly implicaƟng them as suspects or, at the very least, individuals of interest in 
a kidnapping scenario.

Who : Loreto Bodrogi, Minke Mies, Inga Ferro, and Hennie Osvaldo  
When : Generally Afternoon on Weekday  
Where : Several Mysterious Places  

![sus place](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/41d64117-1402-4da2-a06e-56eba7be3278)

![mysterious place](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/587951d9-8744-4415-9a9e-a29ca64af4e1)

The name mentioned above often visits these 5 mysterious places where there is no detail of 
what location it is. They generally visit these places during the lunch break and there are no 
transactions on their card being charged during their visit to these places. Again the names are 
similar to the security member that spies on the executive houses but Isia Vann is not included 
here, instead, there’s Inga Ferro who is also a member of the security team. The table below 
describes their visiting dates and area

Who : Lucas Alcazar & Minke Mies  
When : Night, 13 Jan  
Where : Frydos Autosupply n’ More   

![loreto xx lucas](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/db631d81-cf02-4e28-8529-e90f08bf5979)

On January 13th night Lucas’s credit card was charged $1000 at 19:20, although his GPS 
location showed that he was not present at the auto supply establishment during that time; his 
whereabouts were instead traced to Ouzeri Elian. Several potential explanations surface, each 
with its own complexities. Furthermore, after the suspicious activities done at night by the 
security team, further investigation focused on those security members. One theory points to 
potential credit card theft by Loreto Bodrogi, given his proximity to Ouzeri Elian that night and 
move to near his home which is coincidentally near from Frydos Autosupply n' More. 
![lucas vs loreto](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/af32a8e5-bfc0-4bca-ac94-166919fd3df2)

An alternative hypothesis implicates Minke Mines, whose GPS location more accurately 
aligns with Frydos Autosupply n' More. Yet, no corresponding transaction from Minke Mies 
corroborates this theory. This hypothesis also creates suspicion towards Henk Mies the truck 
driver, as they shared family name and with a big purchase of $1000, it might be items that 
need to be transported by truck. However further invesƟgaƟon showed that Henk never drives 
past/near the shops, thus he is out of suspicion.
![minke mines no transaction](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/735b573e-b031-459b-98a9-8cc421cfdfe3)

Possible credit card theŌ happened supported with the fact that Lucas's credit card sees 
no further usage following this event, limited only to his loyalty point utilization up to the 16th
Jan. 

![lucas 1000 13 night](https://github.com/wtwilley17/Kronos-Incident/assets/93458004/b20a96f5-253e-458a-a94a-a1e7ec512a1f)








