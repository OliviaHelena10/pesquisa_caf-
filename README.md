# Coffee Preferences Patterns ☕


![image](https://github.com/OliviaHelena10/pesquisa_caf-/assets/163002226/8c6f4436-cffc-4fb7-b770-1df0cfa90d0a)


## Context
As a coffee lover, I have always been interested i learning new things about coffee, such as use new methods to do my coffe, try different spices, experiment new flavors...

When I was looking for a new dataset to practice my skills I found a data from the "Great American Coffee Taste Test" and I falled in love with it, so I decided to use this to discover 
interesting things about other coffee drinkers. 

Bellow there are some things that I have learned and consider important.


## A bit of history
"As it’s thought that coffee originated in Ethiopia, it’s also believed it made its way north, across the red sea into Yemen in the 15th Century. It then started to be grown here in the 
Yemeni district of Arabia, and by the 16th century it was known in Persia, Egypt, Syria, and Turkey.

It was immensely popular for its qualities to help improve alertness and wakefulness, allowing people to devote more time to spiritual matters and praying.

The world’s first coffee house was opened in Constantinople in 1475, now known as Istanbul. Coffee was drunk at home as part of the daily routine, as well as to show hospitality to guests. 
Outside of the home, people visited coffee houses to not only drink coffee but to engage in conversation, listen to music, watch performers, play chess, gossip and catch up on news. Without 
the modern technologies we have today, coffee houses quickly became the epicentre for exchanging and gaining information. They were often referred to as “Schools of the Wise.”

And with thousands of pilgrims visiting Mecca each year from all over the world, knowledge of this “wine of Araby”, which it quickly became referred to, began to spread."


source: https://www.nescafe.com/in/understanding-coffee/coffee-history#:~:text=As%20it's%20thought%20that%20coffee,Egypt%2C%20Syria%2C%20and%20Turkey.


## Objectives
Investigate and discover common coffee preferences.


## Data Pipeline

![Pipeline de Dados](https://github.com/OliviaHelena10/pesquisa_caf-/assets/163002226/a2cf38aa-9442-4102-a4ca-cb803d30fac0)

The dataset was obtained at Kaggle, after downloading I started to clean and manipulate all the data with python and some librarys like Pandas, Numpy and Matplotlib to ease visualization and get better results.

## ETL 
![image](https://github.com/OliviaHelena10/pesquisa_caf-/assets/163002226/5a6a5be3-ba29-4fd4-97ec-7486458de98b)


###  Extract:

Downloaded a dataset from Kaggle.

Availabel at: https://www.kaggle.com/datasets/joebeachcapital/coffee-taste-test


###  Transform:
   
The data was very dirty so it wouldn't be efficient to use her without a proper change to prepare it for graphics and visualization.

First of all I imported some useful libraries for data manipulation - such as Pandas, Numpy and Matplotlib - and started to explore 
the collected data to have a better comprehension including finding inconsistent data. After some researches I found some unusable columns
that had lots of missing values and others that weren't relevant so I dicarded them. Afterwards, some informations were united as one, to solve 
this issue I separeted them as lists of values - later this will cause me some trouble when i try to use Power Bi.

In order to fill some missing data without drastically changing my future results, I made some visualizations with box plot to have a deph 
understanding of some of my columns, then i discovered the bests values to fill in. Finally I saved my data in a csv to use on Power Bi,
but then I found out that made a really big mistake, I had lists as column values and when I tried to use the visualizations it was pratically
impossible to use Power Bi tools. After a bit of headache trying to solve this problem with the microsoft app, I concluded that it was not possible
for me to do what I needed there. 

Back to VsCode I created some loops to scroll through the list and the occurence of each item, it successfully worked so I saved my outcomes as 
new tables, this way there will be no problems with Power Bi.



###  Load:

After cleaning the data it's important to load the updated version, only then we can start to use visualization tools


## Visualization
