## Crime Analytics API Project

### Part A: Background
    This project utilizes crime and police data available on a public API, published by
    the "Single Online Home National Digital Team." Data is provided by various police forces
    and the Ministry of Justice. Comprehensive data is available from street crimes and outocmes, 
    to police team members and police priorites and action plans. 

### Part B: Reserach Questions

    This program aims to answer the following reserach questions:
      1. Were crime rates higher in the 6-month period before COVID than during the 6-month 
      period after COVID cases appeared and the UK lockdown began? 
      2. If crime rates did drop, did the Police achieve/see more favorable outcomes for the crimes that did occur? 
      3. What (if any) change occured in the types of crimes that were being committed?  

### Part C: Program Design and Functionality
    
    There are 2 versions of this analytics program. 1 requires data/user choices to be hard-coded in,
    and the other provides a user-interface,allowing the user to enter dates/data choices straight-forwardly, being designed for non-technical users.
    
    Both programs adhere to the same overarching structure: 
      1. The API is called using a particular police force, one of their neighborhoods, and particular dates. 
      2. A crime report for that location and date is returned. 
      3. The data is analyzed to measure the crime rate and other metrics including outcomes and types of crimes.
      4. The results are visualized in graphs. 
      

![Crime Analytics Diagram.io](/Crime_Analytics_API_Project/Crime_API_Diagram.jpg "Program Diagram")
### Part D: API/Data Link

API Documentation and sample data can be found here: https://data.police.uk/docs/

### Part E: Results 

