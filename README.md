# Citi Bike Analysis with Tableau
![image](https://github.com/AnaTipps/citybike_challenge/assets/131827518/c2b68d65-9fc7-456c-a8f5-13e78749ac3b)


## Background 

Congratulations on your new role as the Lead Analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Bike program! You now oversee the largest bike-sharing initiative in the United States. Your primary responsibilities include generating routine reports for city officials to enhance and promote the program.

Since 2013, the Citi Bike program has established a robust data collection system, updating bike data monthly and sharing it on the [Citi Bike Data](https://citibikenyc.com/system-data) webpage. However, there's currently no dashboard or advanced reporting in place. To address city officials' inquiries, your initial task is to create a set of data reports to provide the necessary insights.


## Deployment
Below is the link to the Tableau dashboard displaying the analysis results: 
https://public.tableau.com/app/profile/ana.luisa.tipple/viz/citibike_challenge_16958390807360/citibike 
![image](https://github.com/AnaTipps/citybike_challenge/assets/131827518/3b4e53ea-e445-4ae5-b97b-fd70b4dc3472)


## Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

    - The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

        * How many trips have been recorded in total during the chosen period?

        * By what percentage has total ridership grown?

        * How have the proportions of short-term customers and annual subscribers changed?

        * What are the peak hours when bikes are used during the summer months?

        * What are the peak hours when bikes are used during the winter months?

        * Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?

        * Today, what are the top 10 stations in the city for ending a journey? Based on data, why?

        * Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?

        * Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?

        * How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).

        * What is the average distance in miles for a bike trip?

        * Which bikes (by ID) are most likely due for repair or inspection in the timespan?

        * How variable is the utilization by bike ID?

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

3. Create one of the following visualizations for city officials:

    - **Basic**: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

    - **Advanced**: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

    - The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

4. Create your final presentation:

    - Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

    - Ensure your presentation is professional, logical, and visually appealing.
    
## Data Source

The first stage of the project required gathering monthly CSV files spanning from January 2018 to December 2020, sourced from the [Citi Bike Data](https://citibikenyc.com/system-data) webpage. These files were then organized within a dedicated folder named "data." It's important to note that the data utilized in this analysis exclusively pertains to the Jersey City region.

Following this, I created a Jupyter Notebook file named [citibike.ipynb]([https://github.com/AnaTipps/citybike_challenge/citibike.ipynb](https://github.com/AnaTipps/citybike_challenge/blob/main/citibike.ipynb)). In this file, I systematically cleaned and merged all the monthly CSV files into a single CSV file, preparing the data for subsequent importation into Tableau.

   
   ** Please be aware that due to the substantial size of the CSV files, they cannot be stored within this repository or in GitHub's Large File Storage. To generate your own master CSV file for Tableau utilization, kindly refer to the instructions outlined in [citibike.ipynb]([https://github.com/AnaTipps/citybike_challenge/citibike.ipynb](https://github.com/AnaTipps/citybike_challenge/blob/main/citibike.ipynb)).**
