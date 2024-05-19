<details open>
<summary> Day 1 </summary>

## 08.30 am: Introduction
[Here's](https://docs.google.com/presentation/d/e/2PACX-1vRbfvQpTP4ARbARRWhOL6WZ6koCKSHvf5OxFyHcJjn8GHXG3OpuneEH6uMYlpxKX0H_sEfHB6KAKrkq/pub?start=true&loop=false&slide=id.g29007063b8d_0_118) what I achieved so far.

## 08.35 am: Unsupervised machine learning
  1. 

## 09.15 am: Code using Google Colab
   1. Using either your new Google account or your personal account, open [Google Colab](https://colab.research.google.com/) in another tab
   2. Google Colab's interface and functions:
     - Tools >> Settings >> 
         - Editor >> Show line numbers (check if you prefer)
         - Miscellaneous >> Corgi mode, Kitty mode (turn on if you like)
      - Test with some basic code:
         - Click Connect at top right
         - Write simple definition	
         - Test simple math problem
      - Runtime settings
         - Run cells
         - Reset
      - Code and text cells
      - Save
   3. More about Colab’s Markdown here
   4. Open a new notebook on [Google Colab](https://colab.research.google.com/)
   5. Try out a few plots on Seaborn:
      - [histplot](https://seaborn.pydata.org/generated/seaborn.histplot.html#seaborn.histplot)
      - [displot](https://seaborn.pydata.org/generated/seaborn.displot.html#seaborn.displot)
      - [boxplot](https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot)
      - [lmplot](https://seaborn.pydata.org/generated/seaborn.lmplot.html#seaborn.lmplot)
   6. Practice:
      - Load the [CSV](https://docs.google.com/spreadsheets/d/1IaonaJj-c5Ud76Uc9WeRiMSlKLTNnbg-BCUxOoZrXn0/edit?usp=sharing) into Colab
      - Create a [displot](https://seaborn.pydata.org/generated/seaborn.displot.html#seaborn.displot), where x-axis represents `Region`
      - Create a [catplot](https://seaborn.pydata.org/generated/seaborn.catplot.html#seaborn.catplot), where x-axis is `Profit` and y-axis is `Sub-Category`
      - Adjust the size of charts by `sns.set(rc={'figure.figsize':(25.7,8.27)})`
      - Create a [boxplot](https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot) where x-axis is `Sales`, and y-axis is `Region`

___

## 10.15 am: Break
___

## 10.20 am: Data structures and the pandas library
  1. Most common data structures:
     - Lists like `my_list = [1, 2, 3, 'hello', True]`
       - Lists are ordered collections of items, and can contain elements of different types
       - Elements can be changed after the list is created
       - Denoted using square brackets `[]`
     - Tuples like `my_tuple = (1, 2, 'world', False)`
       - Similar to lists
       - Immutable: once the elements are created, they cannot be changed
       - Denoted using parentheses `()`
     - Dictionaries like `my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}`
       - Collections of key-value pairs
       - Unordered
       - Keys must be unique within a dictionary
       - Used to map relationships beween items
       - Denoted using `{}`
     - Sets like `my_set = {1, 2, 3, 4, 5}`
       - Unordered collections of unique elements
       - Useful to remove duplicates from a sequence or testing membership
       - Denoted using curly braces `{}` or `set()` 
     - Strings like `my_string = "Hello, World!"`
       - Sequences of characters, used to represent text data
       - Enclosed in single or double quotes
     - Arrays like `my_array = array.array('i', [1, 2, 3, 4, 5])`
       - Collections of items of the same type (integers or floats etc.)
       - More memory efficient than lists for certain operations
       - Created using `array()` from the `array` module
  2. Lists
     - Using `my_list = [1, 2, 3, 4, 5]`:
       - Access element by index
       - Extract a subset of elements
       - Adding elements to the list
       - Inserting and deleting elements
       - Length of list
       - Membership testing
  3. Dictionaries
     - Using `my_dict = {'name': 'John', 'age': 30}`
       - Access element by key
       - Adding and updating key-value pairs
       - Length of dictionary
       - Membership testing
  4. Sets
     - Using `my_set = {1, 2, 3, 4, 5}`
       - Adding and removing elements from set
       - Union, intersection, and difference
       - Length of set
       - Membership testing in set
  5. Strings
     - Using `my_string = "Hello, World!"`
       - Accessing characters by index
       - Extract substrings
       - Concatenation
       - Length
       - Membership testing
  7. Open [pandas](https://pandas.pydata.org/) documentation
  8. Download as [Excel](https://docs.google.com/spreadsheets/d/1IaonaJj-c5Ud76Uc9WeRiMSlKLTNnbg-BCUxOoZrXn0/edit?usp=sharing)
  9. Try a few pandas tasks:
     - Load Excel file (above) using one of the functions provided in the [pandas](https://pandas.pydata.org/docs/reference/io.html#excel) library
     - Load a csv file from [KKM](https://raw.githubusercontent.com/MoH-Malaysia/covid19-public/main/static/population.csv) using one of the functions provided in the [pandas](https://pandas.pydata.org/docs/reference/io.html#flat-file) library
     - Convert the csv file (or the Excel file) into a parquet file using one of the functions provided in the [pandas](https://pandas.pydata.org/docs/reference/io.html#parquet) library
     - Load the parquet file into Google Colab, verify if the conversion is done correctly
     - Try loading a sample parquet file from [kkmnow-data](https://github.com/MoH-Malaysia/kkmnow-data)

## 11.00 am: scikit-learn
  1. Open [scikit-learn](https://scikit-learn.org/stable/) documentation
  2. 

## 12.00 pm: Parse and analyze data from Microsoft Excel
  1. 
___

## 1.00 pm: Lunch
___

## 2.00 pm: Unsupervised machine learning using medhX data
  1. Wyhow to provide data source on [Drive](https://drive.google.com/drive/folders/1-7WkExnqc7FJp4clivrxfp6lxDebDpGj?usp=sharing)

</details>

<details open>
<summary> Day 2 </summary>

## 08.30 am: Text mining

## 09.30 am: Revise data structures and list methods

## 10.00 am: JSON parsing and list comprehensions

___

## 10.40 am: Break
___

## 10.50 am: XML parsing

## 11.30 am: REST APIs (using [data.gov.my](https://data.gov.my/dashboard))
   1. Using either your new Google account or your personal account, sign up for [Postman](https://www.postman.com/), then log in
       - Look for Workspaces (top left of the page) >> My Workspace (Click)
       - ![image](https://github.com/atlas-github/2023fstep25/assets/50855923/4144bc9c-1375-404e-9a39-747cd179724c)
         
       - Look for the + sign beside Overview
       - ![image](https://github.com/atlas-github/2023fstep25/assets/50855923/3582e9e2-61d3-4925-811d-959303ffca23)
         
   2. Open [data.gov.my](https://data.gov.my/dashboard) using another tab on your browser >> API Docs
   3. Scroll to Realtime APIs >> Weather API
   4. Try the Forecast API Endpoint `GET https://api.data.gov.my/weather/forecast` on Postman
        - Look for the icon circled in the snapshot below
        - ![image](https://github.com/atlas-github/2023fstep25/assets/50855923/f68b0004-a86f-467a-8c0c-d0a5c47c09a5)
     
        - Switch from cURL to Python - Requests
        - ![image](https://github.com/atlas-github/2023fstep25/assets/50855923/225b80ec-0323-42ad-8eb0-67c9d5ae0d85)
     
        - Copy the Python code from Postman and paste into a new [Colab notebook](https://colab.research.google.com/)

   5. Change `print(response.text)` to `response.json()` to see the data returned by the API endpoint
   6. Tasks:
      - Convert json output into a dataframe using `pd.json_normalize()`
      - Store dataframe into a variable `df`
      - Filter to include only `df[df['location.location_name'] == 'Langkawi']`
      - Output into a CSV file, then download and open in Excel
      - Now try the Transport API (GTFS-R) and output the locations of Prasarana buses on Google My Maps

## 12.00 pm: Text mining using [PubMed](https://pubmed.ncbi.nlm.nih.gov/) and [LILACS](https://lilacs.bvsalud.org/en/)
  1. Build RSS feed parser using PubMed, with a sample search term
     - Save search results as a dataframe
     - Upload results to a Google Sheet
     - Email notification to receive new results
  2. Task
     - Build RSS feed parser using LILACS, with a sample search term
     - Save search results as a dataframe
     - Upload results to a Google Sheet
     - Email notification to receive new results

___

## 12.50 pm: Lunch
___

## 2.00 pm: Web scraping

## 2.30 pm: Text mining KMBase
  1. Open [Google Colab](https://colab.research.google.com/) in another tab
  2. Follow in class instructions:)

## 4.00 pm: Recap and end

</details>
