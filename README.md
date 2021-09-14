# Summary-of-Academic-Project
Hi, welcome to my Git!  
Here is a list of selected projects completed during my study in business analytics at University of California, Irvine. 

## [Free-to-Fee-Strategy Analysis](https://github.com/joychentw/Free-to-Fee-Strategy-Analysis)
<img src="https://github.com/joychentw/Summary-of-Academic-Project/blob/main/images/free-to-fee.png?raw=true" width="350">   

- **Tools**: Tableau for data visualization and R for the rest of the analysis (techniques: Propensity score matching, logistic regression)
- **Objective**: Understanding what factors cause people to go from freemium to premium on an anonymized real music streaming company nicknamed High Note
- Finding? Peer influence  plays a significant role. PSM is used to match people with similar conditions to exclude compudning factors. There is a positive correlation between subscribing and having friends who are adopters. This might be due to homophily, people who have similar behavior will befriends each other, or it could also be seeing a friend subscribe pushes their friends to subscribe too. High Note could consider engaging in more referral marketing. 

  
   
## [Co-purchasing Analysis via Network Analysis](https://github.com/joychentw/Copurchasing-Analysis-via-Network-Analysis)
<img src="https://github.com/joychentw/Summary-of-Academic-Project/blob/main/images/copurchasing.png?raw=true" width="350">   

- **Tool**: R (techniques: network analysis)
- **Objective**: This project is about Amazon’s co-purchase network: Which products are purchased together on Amazon. 
- Finding? The social graph shows two main groups, one with Id 33 in the center: Double Jeopardy (T*Witches, 6), another one represented with Id 4429 in the center: Harley-Davidson Panheads, 1948-1965/M418. Between 33 and 4429. 
- There is a local bridge, meaning it ties between two groups in a social graph that are the shortest route by which information might travel from those connected to one to those connected to the other. If the local bridge is removed, the distance between these two groups will increase, which will significantly reduce the probability of co-purchasing behavior between the two groups and the frequency of products being bought. 



## [House Price Prediction](https://github.com/joychentw/House-Price-Prediction)
<img src="https://github.com/joychentw/Summary-of-Academic-Project/blob/main/images/houseprice.png?raw=true" width="450">   

- **Tools**: Tableau for data visualization and R for the rest of the analysis
             techniques: linear regression, backward stepwise regression, regression tree, random forest, XGBoost, time series models
- **Objective**: Understanding factors that affects house price in Iowa and to predict house price for both sellers and buyers
- Finding? For sellers: Location matters, Stonebrook has 20% higher price than the rest of the area. We think it is beacuse there are good ranking schools nearyby. Polish the basement if there is one as it increases the house price significantly. Install heating system will enable sellers to ask higher price. As for buyers: From late May to mid July, there is a greater demand for houses with sales peaking. Also, to avoid competition, buyers should look for houses after summer months so they have greater bargain power.
