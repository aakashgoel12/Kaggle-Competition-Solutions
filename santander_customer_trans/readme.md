KAGGLE COMPETITION - Santander Customer Transaction Prediction

1) PROBLEM - Can you identify who will make a transaction?

2) EVALUATION - Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

3) ABOUT - Repository contains different approaches I tried and finally after completion of competition, I am standing @ position 1229 out of 9038 Teams with AUC value 0.89987 (Private Leaderboard) and 1224 position with AUC value 0.90095 (Public Leaderboard). Check it EshuGoel on leaderboard (https://www.kaggle.com/c/santander-customer-transaction-prediction/leaderboard)


4) LINKS - 
	a) https://www.kaggle.com/c/santander-customer-transaction-prediction
	b) https://www.kaggle.com/c/santander-customer-transaction-prediction/data
	c) https://www.kaggle.com/c/santander-customer-transaction-prediction/leaderboard

5) MY LEARNINGS
	a) Cross fold matters alot, improved my score from AUC 0.89 to 0.90.
	b) Data shuffling also helps alot.
	c) Always start with Base Model like in this problem of Binary classifier (MuliNomial Naive Bayes).
	d) Should read maximum no of kernels during competition - Quite Informative.
	e) When Classification problem comes @ hand - Must give try to LightGBM, CatBoost (part of many winnning solutions).
	f) Denoising data - Is training data contains lot of noise?

6) Github Link: https://github.com/aakashgoel12/KaggleCompetitionSolutions

7) 