# codeless-ai-ml-2022
## Social Network Ads
### Introduction
* Social network advertising, also social media targeting, is a group of terms that are used to describe forms of online advertising that focus on social networking services. One of the major benefits of this type of advertising is that advertisers can take advantage of the users’ demographic information and target their ads appropriately.Advantages are advertisers can reach users who are interested in their products, allows for detailed analysis and reporting, information gathered is real, not from statistical projections, does not access IP-addresses of the users.
### Overview of the Study
* Our field study concerns the dependence of purchase of product on Gender , age , estimated salary of a person with given userID.

The specific objective of this Study was to investigate the advertising strategy employed by company to which group of people they must advertise more. Our goal was to compare purchasing of the product by person based on sex , age and estimated salary.
### Data
*Data contains 5 columns.
1.	UserID.
2.	Gender 
3.	Age 
4.	EstimatedSalary 
5.	Purchased 
### Model
#### <img width="437" alt="image" src="https://user-images.githubusercontent.com/109578693/222183286-4c65211b-e577-4739-bd6c-d608f7986a19.png">
#### <img width="463" alt="image" src="https://user-images.githubusercontent.com/109578693/222183404-2e66358e-fe3d-4e6f-8b58-a1c520830123.png">

#### Data access
<img width="618" alt="image" src="https://user-images.githubusercontent.com/109578693/223731115-11e56812-e406-4142-88f7-ae188dbf2832.png">

#### Data transform
<img width="477" alt="image" src="https://user-images.githubusercontent.com/109578693/222185869-b5b35125-ce6a-4f17-bc16-564afa041893.png">
##Before going to rule engine
##### Histrogram of Estimate salary 
<img width="758" alt="image" src="https://user-images.githubusercontent.com/109578693/223732343-b49f109a-cf8d-461e-b871-ea5e06454561.png">
##### Box plot of Age
<img width="758" alt="image" src="https://user-images.githubusercontent.com/109578693/223732521-ddef8381-a8fc-4835-b44c-9d928dae89d2.png">
##### Pie chart of purchase and not purchase



##### Data understanding
<img width="386" alt="image" src="https://user-images.githubusercontent.com/109578693/222186087-6ab212e6-6df2-4ded-988d-1dd9c323c519.png">

#### Barchart to see whice Gender buy more
<img width="758" alt="image" src="https://user-images.githubusercontent.com/109578693/223733397-21cb03b8-0dae-4de9-9d98-3c50f4d40053.png">
#### piechart of Age 
<img width="758" alt="image" src="https://user-images.githubusercontent.com/109578693/223733691-c1de9b81-1bda-490a-93e5-3091e38c9404.png">
#### piechart of salary
<img width="758" alt="image" src="https://user-images.githubusercontent.com/109578693/223733913-c45dd1e1-157b-40a8-b2b0-7bc34622118a.png">

##Data prepare : Splitting data as 80% traning and 20% for testing data
<img width="396" alt="image" src="https://user-images.githubusercontent.com/109578693/223734455-58b70a92-6925-4be0-9e5b-39b44a99beb2.png">


## Modelling of statistic leanner :Setting the target node and building the model
<img width="579" alt="image" src="https://user-images.githubusercontent.com/109578693/223734823-9c85ae59-0a59-43ad-ac32-43c0fac801f4.png">
## Modelling of logistic predictor : to predic the target column
<img width="950" alt="image" src="https://user-images.githubusercontent.com/109578693/223735387-9fcbca2b-eea5-4fb6-b451-a536c87acbdc.png">

## Modelling of decision tree leanner
<img width="711" alt="image" src="https://user-images.githubusercontent.com/109578693/223736002-5b944a12-ab36-40cc-badd-ea310efa3bb5.png">
## Modelling of decision tree predictor
<img width="950" alt="image" src="https://user-images.githubusercontent.com/109578693/223736303-5445c86e-8146-4bf1-aee4-4bd248e63f2d.png">

## Modelling of random forest leanner
<img width="960" alt="image" src="https://user-images.githubusercontent.com/109578693/223736699-aa688a97-bcb7-42fc-926c-d9f942ae107f.png">
## Modelling of Random forest predictor
<img width="950" alt="image" src="https://user-images.githubusercontent.com/109578693/223736972-0368ffb3-608a-4ab9-9584-a9a7af66d7d3.png">


#### Score of statistic
<img width="341" alt="image" src="https://user-images.githubusercontent.com/109578693/222183618-ad99d74e-9688-455e-b483-85d382ae6806.png">

#### Score of decition tree learner
<img width="341" alt="image" src="https://user-images.githubusercontent.com/109578693/222183798-bbc40d3a-a0da-4ebe-9c15-18fb13bdac42.png">

#### Score of random forest lerner
<img width="341" alt="image" src="https://user-images.githubusercontent.com/109578693/222183913-79ab6acf-90eb-419e-81f7-92fbff7ffe18.png">







### Results
*We found empirical support for Hypothesis. The number of females who purchased the product are more than number of  males who purchased the product.
### Conclusion
*This paper was motivated by the need for research that could improve our understanding of how social advertising can affect the purchase of product based on age, gender and estimated salary of a person. The unique contribution of this paper is that we investigated the number of males and females who purchased the product through social network advertisements. We observed the number of females are larger than males who purchased the product.


##### Name Sayutee waesohoh 621431001
##### Name Anas waesaha 621431021
