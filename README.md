# surfs_up
Code: [Surfs_UP_Challenge](https://github.com/smpimentel/surfs_up/blob/main/SurfsUp_Challenge.ipynb)

## Overview of the Challenge
The purpose of this challenge was to create a statistical summary of the temperatures on Oahu during the months of June and December. This was to help determine how successful a surf and ice cream shop would be all year round in the climate spacific to that region. To achieve this we created a for loop  that ran a session.query to filter out the temperatures specifically for the months of June and Decemeber. From this we were able to create a summary that provided the max, min, average, and more.

## Results

### Month of June
Between 2010 and 2017 with over 1700 unique recorded temperatures we were able to see that the weather in Oahu in the month of June is relativily mild and stable for the most part. As seen in the summary shown below. The average temperature for the month of June was about 75 degrees with a low standard deviation at 3.25. It seems that its max and min were within 10 degrees of the  average making it an ideal place it would seem for surfing.

![June_Summary](https://github.com/smpimentel/surfs_up/blob/main/Resources/June%20Temps.png)

### Month of December
From the same database of temperature readings we had a pool of 1500 unique recodings for us to analyise. And although the standard deviation was still fairly low at 3.75 (slightly higher than the month of june) it seemed that its peak temp was almost the same. Its average temperature did drop to 71 degrees. Still in the 70s, but it did reach a low of 56 (still not that volitile). 

![December Summary](https://github.com/smpimentel/surfs_up/blob/main/Resources/December%20Temps.png)

### Summary 
Based on these two months of data it would seem that the weather in Oahu is steady enough to be perfect for this business modal. My only concern would be the percipitation. I would think that if there is a high amount of rain during a certian time of the year, that would potentailly hinder business.


### API App
If you want to be able to call upon specific datas in the data there is an app.py that you can run using flask to better view the data.
Make sure to have these packeges installed:
* python
* numpy
* pandas
* sqlalchemy
* flask
