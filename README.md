# [Partido Libertario Mx Social Networks Analysis](#Table-Of-Contents)
Analyzing the results from their social networks, insights and proposing posible actions to improve.

You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
All the results are written below but if you want to see the report in tableau [click](https://app.powerbi.com/view?r=eyJrIjoiNzMxNmQ2OWEtNzkxZS00Y2E2LTg1MDktMTdhNzZkMTAyYzc3IiwidCI6IjJlZGE0M2M5LTUxYzktNDAwMi1iZjJmLTlmY2QwMzZmNjdkNyJ9)




# Table Of Contents

* [Abstract](#Partido-Libertario-Mx-Social-Networks-Analysis)
* [Results](#Results)
* [Tools And Libraries](#Tools-And-Libraries)
* [Data Wrangling](#Data-Wrangling)


# [Tools And Libraries](#Table-Of-Contents)
  * Python 3.7
  * Pandas 1.1.5
  * Numpy 1.19.5
  * Datetime
  * Excel
  * Power BI
  * re
  * os

# [Data Wrangling](#Table-Of-Contents)
The wrangling was done altogether (twitter and facebook) in a jupyter notebook via google colab, to see the entire document and more in detail comments I added [click](https://github.com/JorgePablol/Data-Analysis-Libertarian-with-Tableau/blob/main/Libertarian_cleaning_github_version.ipynb) if the document don't open reload or download and open it with Google Colab. 


## The wrangling can be divided in 3 simple steps:

### 1. Importing Libraries and declaring the function I will use to create some features on the next functions.


![librerias creacion de features](https://user-images.githubusercontent.com/58957744/122442315-0f947980-cf64-11eb-8b45-c0f389e22dc2.png)


### 2. Dropping useless features

![limpiando](https://user-images.githubusercontent.com/58957744/122441935-a9a7f200-cf63-11eb-8b51-3b3eadddc90f.png)


### 3. Executing the function scripts.

![fb actualizando dataset historico](https://user-images.githubusercontent.com/58957744/122442060-cb08de00-cf63-11eb-9456-adcd90f2c7fe.png)

### Extra. Making of historic dataset.

![contatenando el primer dataset historico](https://user-images.githubusercontent.com/58957744/122442160-e247cb80-cf63-11eb-880f-7993891becad.png)
