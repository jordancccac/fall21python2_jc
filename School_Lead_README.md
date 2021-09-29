# Project: Blood Lead Levels in Pittsburgh-area School Districts 

## Description 
 
### Part A: Background

    This project focuses on a data set that measured lead levels
    in school districts by testing blood in children under 6 years of age.
    
    The data was collected over 6 years: 2015-2020. 
    The annual percentages represent the percent of children (* out of the total number tested*) who had 
    blood lead levels equal to or greater than 5 micrograms of lead per decileter of blood.

### Part B: Functionality and Purpose

    The project utilizes JSON encoded search criteria, partially defined by the user, allowing
    him/her to search for specific data points, namely, school districts. 
    The output, which includes JSON-encoded results, displays the students' lead levels over the 6 year period. 
    
    The ultimate goal is to analyze the change in lead levels to identify high-risk areas, as well as safe areas,
    and help make more informed public health decisions and share best practices.  

## Part C: Data Link

   The original data set can be found at: (https://data.wprdc.org/dataset/allegheny-county-elevated-blood-lead-level-rates/resource/e99fa58e-f09a-4aa0-90a9-7996a0bca147?inner_span=True)
    
## Part D: Creating a JSON file to Encode Search Criteria 

   1. A file with the .json extension can be created in a Python environment (like Jupyter notebooks or the Python shell). 
   It can also be created in the Git Bash command line text editor: vim
   
   2. To properly structure the JSON content, enter the search criteria as key-value pairs in curly braces.
   The key is "SchoolDistrict" and the corresponding value is your school district of choice. 
   For example: { "SchoolDistrict" : "Avonworth" }
