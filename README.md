<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __IPM Diamonds__ #
Irene Rengifo - Project Module 2 - Data Analytics Part-Time Bootcamp - Nov 2021 - Ironhack Madrid
## **Goal** ##
To create a dashboard that is user friendly, that the customer understands as much as possible about diamonds. 

## **Overview** ##
### **Data Exploration and Preparation.** ### 

The goal of this challenge is to perform an exploratory analysis in order to gain initial insight on our diamonds database and prepare the data model that better fits your visualizations. 

#### **Data Collection** ####
I used Jupyter Notebook and SQLite to connect and extract the information from diamonds.db database.  Using pandas and numpy libraries, I then exported the diamonds.csv to start working with:

#### **Exploratory Analysis** ####
Descriptive statistics with Tableau
First insights of the data based on descriptive statistics
Graphical representation of descriptive statistics and relations


![Image](https://ae01.alicdn.com/kf/H19dd6da48ab04e43ba543e893827f6b4I.jpg)

### **Dashboard** ### 

Identification of needs to develop the dashboard and development of the dashboard

Aim: To create a dashboard that is user friendly, that the customer understands as much as possible about diamonds. My dashboard is made so that you can see everything, however, within the options you have in terms of price, you can see the diamond options that exist; and compare between the diamonds (within the parameters) having the highest visibility to differentiate the options (cut, color, clarity).

The parameters I worked with were price and caratage group.

In order to achieve this, I needed to create a dynamic dashboard. Used parameters and calculated fields to get the dashboard to present as much information as possible in a summarized way.


## **Data** ##
1. diamonds.db 

## **Project Main Stack**

- [SLQlite](https://www.sqlite.org/index.html) - used during the starting process of working on the project. 
- [Tableau Public](https://public.tableau.com/en-us/s/) 
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)




## **How to access IPM Diamonds Visualizations**  

[Dashboard](https://public.tableau.com/app/profile/irene1690/viz/DiamondDashboard-IPMDiamonds/Dashboard1?publish=yes)

[Tableau Public - Visualization Story](https://public.tableau.com/app/profile/irene1690/viz/DiamondStatistics-IPMDiamonds/Story1?publish=yes)



## **Conclusions* #

There are some outlier values in the dataset that affects the **mean price** of the diamonds, regardless of the group **category**. 

While I did the analysis with the main dataset by category, I found some odd results that would suggest that diamonds with lower level color or with lower quality of **cuts** had a **higher average price** than others with higher quality. I concluded that this was due to comparing diamonds from different carats between each other.  
For this reason, I decided that to obtain the most objective result, I should compare all characteristics within diamonds of the same **group of carats**, by doing this I found that my new results had more logic, and that indeed while comparing between diamonds of the same range of carats, higher level **color**, **clarity** and **cuts** did have a **higher average price** as compared to lower quality within the same carat group. 

Insights: 
1.	Most diamonds in this dataset have **“Ideal”** cut and **“G”** color.
2.	The cities with the highest amount of diamonds and **total sales** are Surat, Kimberly and Antwerp. 
3.	In conclusion, I found that diamonds with higher quality in all the parameters have higher average prices when compared to others within the same carat group. 

For me, the main conclusion that I've obtained by working with this diamonds database is that the quality of a diamond is explained by different features that are objectively measured by professionals. Some of them are more important than others. This is the thing with carats: the bigger, the more expensive. But this only represents the size of the diamond, not the quality in terms of the other features.


## **and remember: if you don't have a diamond, YOU CAN'T SIT WITH US!!!.** ##
![Image](https://media.giphy.com/media/xT9KVuimKtly3zoJ0Y/giphy.gif)










