# Energy Consumption Dashboard

### Dashboard Link : [https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection](https://app.powerbi.com/reportEmbed?reportId=b44f4ad2-27c6-4c57-9dee-8071d1650402&autoAuth=true&ctid=08de8628-593e-43f5-9ceb-f3e5dd7ae2cb)

[MC-ETH-EE Sparkmeter dashboard] <img width="1551" height="863" alt="image" src="https://github.com/user-attachments/assets/4a767923-c46d-4f91-9e1f-ba429b9687b3" />



## Problem Statement<img width="860" alt="sparkmeer" src="https://github.com/user-attachments/assets/1f8109b2-6454-4d83-83fc-49e3a2a1e1b5" />


This dashboard helps the business stakeholder understand their customers better. It helps the solar electricity provider know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. 

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file, api souces, azure
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
-
