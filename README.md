# **Broome County Transit Study**
  
## **Description (Motivation? The why? Solved Problems?)**

This project aimed to uncover meaningful insights into rider behavior and transit system performance. Using visual dashboards and spatial analysis tools, we explored several key questions:

- Which routes are the most heavily used?
- What are the busiest stops in the system?
- When during the day and week does ridership peak?
- How do transaction types vary across the network?


      
## **Table of Contents** 
  - [Software](#software)
  - [Cleaning](#cleaning)
  - [Visuals](#visuals)
  - [Contributions](#contributions)
  - [Questions](#questions)
  -[Links](#links)

## **Software <a id="software"></a>**
  - R for Algorithmic Data Cleaning
  - ArcGIS for mapping visualizations and website story map presentation
  - Tableau for interactive dashboard visualizations and analysis
    
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

<img width="1699" alt="TransitCleaningAlgo" src="https://github.com/user-attachments/assets/2090a949-7a9b-47cc-be2c-a077eef935fe" />

      
## **Visuals <a id="visuals"></a>** 
  <img width="897" alt="map" src="https://github.com/user-attachments/assets/852ea677-b77d-4eb5-be9c-d8a493c1b8c8" />
  <img width="1360" alt="RidershipDashboard" src="https://github.com/user-attachments/assets/4ce66632-73aa-41b4-ae8f-1b0b20120f35" />



    
## **Questions <a id="questions"></a>**
      
  Please feel free to reach me at gwentzel@binghamton.edu or on linkedIn
  my profile is https://www.linkedin.com/in/gavinwentzel/

## **Links <a id="links"></a>**
Best Website Experience is on a computer
<img width="1426" alt="Broome County Transit Study" src="https://github.com/user-attachments/assets/9546d201-df9b-42fd-8db4-da533e3a2984" />

https://storymaps.arcgis.com/stories/c7c294705bee42c186271ae2da46b8c1
