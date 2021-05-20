# Melbourne real estate history in 2017
## Contents
1. [**Installation**](#Installation)
2. [**Motivation**](#Motivation)
3. [**Notebooks**](#Notebooks)
4. [**Results**](#Results)
5. [**Licensing**](#Licensing)
-----------------------------------------------------------------------------------------------------------------------------------------
### Installation:
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

### Motivation:
According to **Snapshot of Tony Pino's Melbourne Housing Dataset in 2017** to have a look at Melbourne real estate history records. For anyone like me who want to stay and live long term in Melbourne, owning a property could be a essential move to consider. Researching and studying real estate history could help to understand the trend of market, also it could provide me insights from data which might be valueable.

### Notebooks:
There is **3 main questions** for my notebooks: each main questions have several sub questions for my findings.
1. [**Understand the area distribution and pattern**](https://nbviewer.jupyter.org/github/yayuchen/melbourne_housing/blob/main/Area_distribution.ipynb#2) - checking which area has more traded records.
2. [**According to question 1 to analysis property types distribution**](https://nbviewer.jupyter.org/github/yayuchen/melbourne_housing/blob/main/Property_TYPE.ipynb#1) - which type of property has more records.
3. [**Based on my own requirement to find out and recommend myself which area I should consider**](https://nbviewer.jupyter.org/github/yayuchen/melbourne_housing/blob/main/Recommend.ipynb).

### Results: 
**Question 1** - For those area which had traded more frequently, the average property price is lower. On the other hand, less frequency area has higher average price.

**Higher frequency Council areas and average Price** ![**Higher frequency Council**](https://github.com/yayuchen/melbourne_housing/blob/main/images/region%20and%20price.png?raw=True)

**Lower frequency Council areas and average Price** ![**Lower frequency Council**](https://github.com/yayuchen/melbourne_housing/blob/main/images/less%20region%20and%20price.png?raw=True)

**Question 2** - In entire dataset, **H** type of property has the highest percentage. In **higher frequency Councils**, the percentage of **H** is slightly less than the other subset, but the other types are slightly higher. Between 2 subsets there are different features: Higher frequency Council area has more rooms, bathrooms and car spots, the property built year is older, but this subset is **closer** to CBD.

**Entire Type data distribution** 
![type distribution](https://github.com/yayuchen/melbourne_housing/blob/main/images/type%20distribution.png?raw=True)

**Difference of Type percentage** 
![difference type](https://github.com/yayuchen/melbourne_housing/blob/main/images/subset%20type%20distribution.png?raw=True)

**Numerical data analysis** 
![numerical data](https://github.com/yayuchen/melbourne_housing/blob/main/images/numerical%20data.png?raw=True)

**Question 3** - In less 1 million subset, **MORELAND, MARIBYRNONG, BOROONDARA and GLEN EIRA** has the lowest Price property. **WYNDHAN, STONNINGTON, PORT PHILLIP and HUME** has the median Price which is less than $600000. The lowest price Type is **U**, **SOUTHERN, WESTERN and NORTHERN** has lower median value than other Council area. For Distance less than 10 subset, there is more **U** types, only **MELBOURNE and YARRA** are no further than 5.

**Price distribution by Council area and median Price** ![group plot](https://github.com/yayuchen/melbourne_housing/blob/main/images/group%20data.png?raw=True)

**Distance distribution and subset difference** ![distance](https://github.com/yayuchen/melbourne_housing/blob/main/images/distance.png?raw=True)

**Distance distribution of Council area** ![council distance](https://github.com/yayuchen/melbourne_housing/blob/main/images/closer%20council.png?raw=True)

**All findings can be found in this post.**

### Licensing:
You can find the Licensing for the data and other descriptive information at this [**Kaggle link**](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot). Otherwise, feel free to use the code here as you would like!
