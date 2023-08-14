# Personalized Product Recommendations:
## Use-cases:
Recommendation according to purchase history 
Recommendation according to browsing history analysis
Recommendation according to sentiment analysis
Recommendation based on rating
Recommendation based on user interaction

## Constrains:
Analyze user preference
Analyze past interaction
Analyze product popularity in a specific region
Analyze user similarity

## Solution statement/ Proposed approach

### Popularity Based Recommendation:
	- Recommendation based on demand
	- Suggests the most frequently purchased products to customers

### Collaborative Filtering Recommendation:
	- Recommendation based on purchase history 	
	- Uses algorithms to filter data from user reviews to make personalized recommendations for users with similar preferences.

### Content Based Filtering Recommendation:
	- Recommendation based on rating and feedback
	- Records and uses personalized features in order to recommend products

### Sentiment Based Recommendation:
	- Recommendation based on user sentiment 
	- Uses natural language processing to analyze user sentiment
 
## Required Module:
### sklearn:
![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/9167f279-5893-49fe-88e7-71b7657e579c)

### surpise:
![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/72b11289-52c3-48e7-9a5e-856a5db87aa6)

### scipy:
![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/992d9420-c3b0-444f-a1d3-5bca1e7491a8)

### others:
![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/0f0c385b-cdde-47f3-bd0d-985f0503f115)

## Data Analysis:
![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/34760e99-2f41-4355-bd9a-2021a455fb28)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/457d698e-6b1e-4f90-ae1f-a52587e50c67)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/75ff8023-645b-46a9-a035-8d11150a7c66)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/a3d8d9ad-f3e9-4f7c-bf74-2a6233ec72ed)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/448e8585-d7dd-4751-b4de-05e3a71e2334)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/d93171c3-a9de-48dd-9a87-a3b6e6441622)

![image](https://github.com/sujanrupu/Personalized_Product_Recommendations/assets/103595490/32b433a9-203a-469e-80fa-2fc37d3ba3bf)

## Limitations
- Cold Start Problem
- Limited Serendipity and Exploration
- Filter Bubble Effect
- Limited Understanding of Context and Intent
- Lack of Transparency and Explainability
- Stereotyping and Bias
- Dynamic Preferences and Drifting

## Observation
- The Popularity-based recommender system depends on some parameter, such as frequency counts, which may be not suitable to the user.
- Model-based Collaborative Filtering is a personalized recommender system, the recommendations are based on the past behavior of the user and it is not dependent on any additional information.
- Item Similarity Based model performed worse than even simple popularity based models. Best performing models is SVDpp (RMSE : 1.04%)
- Hyper parameter tuning with GridSearch didn't improve model performance

## Future Scope
- Hybrid Recommendation Systems
- Context-Aware Recommendations
- Explainable AI and Transparency
- Federated Learning for Privacy
- Multi-Modal Recommendations
- Dynamic Ensemble Models
- Personalized Group Recommendations







