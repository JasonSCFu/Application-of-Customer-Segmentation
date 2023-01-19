
# <h1 align="center" id="heading">Customer Segmentation using K-Means and Affinity Propagation</h1>


## What is customer segmentation? ##
Customer segmentation is one of the simplest and most powerful technique in marketing to group customers into different buckets so that campaigns could be tailored for specific group of customers based on their behavior rather than one blank campaign for entire customer database.

Let’s start with simple definition of Segmentation or Clustering. In simple terms, Clustering is a mathematical way to segment customers into different groups. It is an Unsupervised machine learning technique where each instance, in our case, each customer is assigned to a group based on their behavior and all the datasets are unlabeled unlike in Supervised machine learning where all the instances are labelled. Once customers are clustered in their respective segment, this gives us an opportunity to understand more about that segment and we can be more targeted and the campaigns we run for those segments becomes more personalized which is what each and every customers want in this digital age.




## Issue of applying segmentation in real business ##

I use a public dataset from [Kaggle](https://www.kaggle.com/code/paulinan/bank-customer-segmentation/data) to walk through the application of segmentation methods to banking customer base. Using segmentation to group similar customers into groups are not new. But in real business application, I often came across the following questions when I try to interpret the result to business.

* 1: Why are these customers grouped together? What are the common traits?
* 2: Why do some customers transit from one group to another over times? What are the drivers behind it?

Of course, there are others questions to address when we use clustering techniques. For example, how many clusters should we use? How to measure the stability of clusters?

In fact, segmentation in real business application is more of an art than science. But the way to communicate to non-technical stakeholders are important. In this repo, I will show how to use K-Means and Affinity Propagation to segment credit card customers, and more importantly, how to visualize and explain the segments. 



## Dataset ##

In this dataset, each entry represents a person who takes a credit by a bank. Each person has the following attributes.

* Age (numeric)
* Sex (text: male, female)
* Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
* Housing (text: own, rent, or free)
* Saving accounts (text - little, moderate, quite rich, rich)
* Checking account (numeric, in DM - Deutsch Mark)
* Credit amount (numeric, in DM)
* Duration (numeric, in month)
* Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)









<br/>
<br/>
<br/>
Hope you will find it insightful. Any feedback or comments are welcome. 
