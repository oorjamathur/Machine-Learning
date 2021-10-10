## Online Shoppers Intention

![Online Shopping](https://www.weirdworm.com/wp-content/uploads/2020/01/Online-Shopping.jpg)

- Overview
- Tech Stack
- Enhancements
- Technologies Used

### Overview
1. __GOAL__: The goal is to predict shopper's intention of buying products given various features.
2. The dataset has features like 
- 'Administrative' = no. of administrative pages visited
- 'Administrative_Duration' = time spent on administrative pages
- 'Informational' = no. of informational pages visited
- 'Informational_Duration' = time spent on informative pages
- 'ProductRelated' = no. of product pages visited
- 'ProductRelated_Duration' = time spent on product pages
- 'BounceRates' = no. of people who enter the site and leave without requesting anything(they view only one page)
- 'ExitRates' = total amt of exits/ total amt of visits in a definitive time duration
- 'PageValues' = avg value of a web page a user visited before completing an e-commerce transaction
- 'SpecialDay' = proximity to some special day
- 'Month' = month of the year
- 'OperatingSystems' = label encoded OS
- 'Browser' = label encoded browser
- 'Region' = label encoded region
- 'TrafficType' = label encoded traffic type
- 'VisitorType' = returning/new/other
- 'Weekend' = whether date of visiting the site is weekend (boolean)
- 'Revenue' = target (boolean)

3. This is a classification problem.
4. The notebook contains extensive visualizations along with inference derived from each visualization.
5. Both bagging(Random Forest Classifier) and boosting(XGBoost Classifier) has been used. the best of both is selected.
6. Class weights parameter has been used in Random Forest Classifier to check imbalanced data.

### Tech Stack
1. Visualizations using Seaborn
2. Sklearn
3. Bagging - Random Foresr
4. Boosting - XgBoost
5. Dealing with imbalanced data.

### Technology Used
1. Machine Learning
2. Bagging
3. Boosting
4. Seaborn


### Enhancements

1. Overfitting was noticed so we can try reducing dimensions using PCA or feature selection.
2. We can do hyperparameter tuning to further improve model metrics.
