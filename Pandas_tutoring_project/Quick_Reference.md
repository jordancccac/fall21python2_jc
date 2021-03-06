
# Pandas Tutoring Documentation 

## Data Structures 

    1.	Series: 1-demensional array of tabular data
    
            •   Example code:
![Series Image.io](/Pandas_tutoring_project/images/Picture1.jpg "Series image")

 
    2.	Data Frames: 2-demensional array; can be considered a collection of Series 
    
                a.Can be created in the dataframe statement or an object can be passed as an argument
                
                b.It can take many forms, including a dictionary, list of dictionaries, and a Numpy ndarray 
 
        •   Example code:
 ![Data Frame Image.io](/Pandas_tutoring_project/images/Picture2.jpg "Data Frame Image")
 
 See further introduction at: (https://pandas.pydata.org/docs/user_guide/dsintro.html)
## Indexing
    •   Indices can be 0-based integers, or customized strings, integers, and floats using the keyword argument "index"
    
    •   If no index is assigned, 0-based integers are default
    
    •   Example code:
![Customizing Indicies Image.io](/Pandas_tutoring_project/images/Picture3.jpg "Custom Indexing")

### Indexing rows and columns, using iloc and loc 
    •	Index rows with default 0-based integer labels using iloc 
    
    •       Example code:
    
![Index with iloc.io](/Pandas_tutoring_project/images/Picture4.jpg "iloc indexing")


    •	Index rows with custom integer labels that exceed the length of the axis using loc
    
    •       Example code:
    
![Index with loc.io](/Pandas_tutoring_project/images/Picture5.jpg "loc indexing")


    •	Index rows with string labels using loc
    
    •	Index integer or string column labels using the structure: dataframe[int or ‘string’]
    
 See more on indexing: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.iloc.html

## Manipulation 
    •	Add a column to a data frame in a specific location using the structure: dataframe.insert(position, column name, [value 1, value 2, etc.])
    
    •       Example code:
![Add Column.io](/Pandas_tutoring_project/images/Picture6.jpg "Adding a column")


    •	Change the value of a single cell using the structure: dataframe.at[row, column]=value 
    
    •       Example code:
![Value Changing.io](/Pandas_tutoring_project/images/Picture7.jpg "Value Changing")


## I/O Processing 
    •	Read a json file into a dataframe using: object=pd.read_json(file_name.json)
    
See more on I/O processing in Pandas: https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#excel-files
