This project is to predict if a customer is happy or not based on the answers they give to questions asked.

The dataset was trained on 4 models, namely Logistic Regression, Decision Tree, Random Forest and XGBoost. The model outputs indicate XGBoost as the optimal model due to its highest accuracy scores of 70% (train set) and 73% (test set), also two important features that are highly predictive are `courier_satisfaction` and `on-time_delivery`. 

However, the test accuracy of 73% is **not** an ideal number at all, so to achieve a higher score, it is recommended to introduce more highly relevant features, which would require domain expertise and is room for improvement for subsequent surveys. Meanwhile, the feature X6 or `easy_order` may be considered for removal for future surveys since it ranks last on both feature importance and $\chi^2$ (Chi2) value.

---
