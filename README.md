# Facebook_friend_recommendation
This repository contains the case study of facebook friend recommendation where missing links are predicted using directed social graph

### Problem statement:
Given a directed social graph, have to predict missing links to recommend users (Link Prediction in graph)

Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.

### Important Features 
![feature imp](https://user-images.githubusercontent.com/25454660/61453732-960d3e80-a97c-11e9-9f5d-4928ff75388d.png)

### Performance of the Model
<table>
<th><td>model</td><td>	f1 score(train)	</td><td>f1 score(test)</td></th>
<tr><td>1	</td><td>XGBoost with hyperparameter tuning	</td><td>0.999800	</td><td>0.925871</td>
</table>
