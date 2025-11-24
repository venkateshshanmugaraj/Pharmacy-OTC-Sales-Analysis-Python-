# Pharmacy-OTC-Sales-Analysis-Python-
This project analyzes shipment data using Python. I cleaned and processed a CSV file, grouped data by country and product, and calculated total boxes shipped. The goal was to identify shipping trends and support better logistics decisions through clear, data-driven insights.

# 1. Data Handling & Processing

## The project imports and uses CSV data with Python libraries:

  + **pandas**
  
  + **numpy**
  
  + **csv**


## The dataset includes fields like:


  + Country
  
  + Product
  
  + Boxes Shipped


## Data is grouped using:

  **df.groupby(["Country", "Product"])["Boxes Shipped"].sum()**

meaning the project calculates total boxes shipped per country and product.


# 2. Data Analysis

## Performs summation, grouping, and aggregation.

  ### Likely used for:

    + Logistics / shipping analysis
    
    + Country-wise product shipment totals
    
    + Identifying patterns or performance metrics


# 3. Visualization (Detected from code imports)

  ## The project imports seaborn (in your file), indicating:
  
    Preparation for charts such as bar charts, line charts, or heatmaps.


# 4. Possible Goals of the Project

Based on the code patterns, the project is mainly about:

✔️ Analyzing shipment data

✔️ Summarizing shipments by product and country

✔️ Visualizing shipping performance trends
