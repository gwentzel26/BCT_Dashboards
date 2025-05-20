# **Broome County Transit Study**
  
## **Description (Motivation? The why? Solved Problems?)**
      This project aimed to uncover meaningful insights into rider behavior and transit system performance. Using visual dashboards and spatial analysis tools, we explored several key questions:

- Which routes are the most heavily used?
- What are the busiest stops in the system?
- When during the day and week does ridership peak?
- How do transaction types vary across the network?


      
## **Table of Contents** 
      
  - [Cleaning](#cleaning)
  - [Visuals](#visuals)
  - [Contributions](#contributions)
  - [Questions](#questions)
  -[Links](#links)
      
## **Cleaning <a id="cleaning"></a>**
  • Started with ~3,000 individual bus GPS files (one per week, per bus across 47 buses).
• Created one data frame per bus using loops in R, adding a Bus ID column to each.
• Merged all bus data frames into a single 9 million row dataset.

Filtered GPS Data:

Retained only records where Movement Status = "Stopped" or "Idle" to reflect moments when boarding could occur.

Joined Transaction and GPS Data

Matched GPS data to transactions based on Bus ID, Date, and Time

Standardized Product Categories

• Cleaned and standardized product names to align with official fare categories.
• Ensured consistency across all fare types (e.g., "Regular Fare," "31-Day E&H Pass," "Transfer").
• Enabled segmentation of rider behavior by payment type for deeper analysis.

Created Nearest Stop Assignment

• Extracted stop coordinates manually from TransitApp.com and organized them into Excel files.
• Used Haversine distance calculations with a 400-meter radius threshold to assign each transaction to its nearest stop.
• Transactions beyond 400 meters of any stop were classified as "Other."

Example of one of the initial R-scripts for cleaning and merging all of the weeks of data into one Bus file

![alt text](TransitCleaningAlgo-1.png)
      
## **Visuals <a id="visuals"></a>** 
  ![alt text](map.png)
  ![alt text](RidershipDashboard-1.png)
  

    
## **Questions <a id="questions"></a>**
      
  Please feel free to reach me at gwentzel@binghamton.edu or on linkedIn
  my profile is https://www.linkedin.com/in/gavinwentzel/

## **Links <a id="links"></a>**
Best Website Experience is on a computer

https://storymaps.arcgis.com/stories/c7c294705bee42c186271ae2da46b8c1