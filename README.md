# [Partido Libertario Mx Social Networks Analysis](#Table-Of-Contents)
Analyzing the results from their social networks, insights and proposing posible actions to improve.

![7ZgECHff_400x400](https://user-images.githubusercontent.com/58957744/122456991-c815e980-cf73-11eb-934f-adee99c33b28.jpg)


You can start by reading the results or go directly to the [table of contents](#Table-Of-Contents).

# [Results](#Table-Of-Contents)
All the results are written below but if you want to see the **report in PowerBI** [click](https://app.powerbi.com/view?r=eyJrIjoiNzMxNmQ2OWEtNzkxZS00Y2E2LTg1MDktMTdhNzZkMTAyYzc3IiwidCI6IjJlZGE0M2M5LTUxYzktNDAwMi1iZjJmLTlmY2QwMzZmNjdkNyJ9)

*    Twitter
      * We must take advantage of the trendings related to libertarianism, failures in the federal government and anti-communism to grow our reach on social networks, we must tweet quickly and get on the trend. 
      * Our results this month are not significantly lower than the past month (U-MannWhitney test).
      * Even though this month is not significantly lower, we couldn't get on the trends since they were about elections.
*    Facebook
      * We must have content related to ephemeris ready, especially if it is related to capitalism and libertarianism, it will make us grow as we see it in the first peak of this month and as we saw it in 8M.
      * Our results this month are significantly lower than the past month (U-MannWhitney test).
      * Our best months with the greatest scope were those in which great exponents of libertarianism accompanied us in our events, we must begin to create personalities from our people.
      * Create our own memes for this platform.
*    TikTok
      * Taking the trends from twitter, our personal brands from facebook, we must take our people to create content, specifically video content with maximum 60 seconds length, to have an impact on tiktok. Our best videos on titok take a trend from twitter and expose their position with data and emotions in not more than 60 seconds.
      * We achive at least 1 video that grows more than the others each month, that video achieves around 11k and 15k views.
      * Our results this month are not significantly lower than the past month (U-MannWhitney test).

* Actions:
    1. Quickly get on the trends on twitter.
    2. Take those trend themes into a position of one of our members.
    3. Resume that position in 1 minute and create and upload the content to our social networks.
    4. Create specific content for facebook, related to memes signed by us.
    5. In future we must be able to hold our live conferences on at least twitter and facebook.
    6. Replicate events with big personalities of libertarianism.
    7. Use our best publications and tweets to map what our audience wants us to explain in the next event.

**Some of the visualizations**

**Overall comparison**

![overall](https://user-images.githubusercontent.com/58957744/122456421-2a221f00-cf73-11eb-877a-a6bb32e125b3.png)

**Facebook**

![fb](https://user-images.githubusercontent.com/58957744/122456441-30180000-cf73-11eb-807e-834e8e47090b.png)

**Twitter**

![twitter](https://user-images.githubusercontent.com/58957744/122456464-373f0e00-cf73-11eb-8e2c-b0f4b9dc5b02.png)




# [Online Visualization](https://app.powerbi.com/view?r=eyJrIjoiNzMxNmQ2OWEtNzkxZS00Y2E2LTg1MDktMTdhNzZkMTAyYzc3IiwidCI6IjJlZGE0M2M5LTUxYzktNDAwMi1iZjJmLTlmY2QwMzZmNjdkNyJ9)
**click the title above**

# Table Of Contents

* [Abstract](#Partido-Libertario-Mx-Social-Networks-Analysis)
* [Online Visualization](#Online-Visualization)
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
