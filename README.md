## Customer Engagement Insights Dashboard

This dashboard provides a high-level overview of customer engagement patterns
and the performance of a logistic regression model, designed to communicate
key insights clearly and concisely.



### Engagement Distribution by Transaction Count & Model Predictions vs Actual Engagement

| Engaged Customers | Predictions vs Actual |
|-------------------|----------------------|
| ![](https://github.com/user-attachments/assets/ff0fa34b-e72c-46a3-896f-dd23ce1a92bd)<br><br>**Insight:** Customers with lower transaction counts are more likely to be classified as not engaged, indicating a strong relationship between transaction activity and engagement levels. | Predicted(red) Actual(green). ![](https://github.com/user-attachments/assets/21911858-5b7a-4be7-b0cf-abb19ea0a2b4) <br><br>**Insight:** While the model performs well overall, some misclassifications are represent, highlighting the limitations of predicting engagement using a single feature.|

---

### Model Performance Summary
The classification report below shows that the model achieves over **90% accuracy**
across the dataset.

![Model Performance](https://github.com/user-attachments/assets/78fea6f7-4eb3-4f88-a20b-6fdd57c9cbf3)

**Insight:** High overall accuracy demonstrates strong predictive capability,
while precision and recall values highlight areas for further improvement using
additional features.


