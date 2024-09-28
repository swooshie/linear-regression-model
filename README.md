### Linear Regression Model

The Linear Regression model project used the Housing dataset to predict property prices based on features such as square footage, number of rooms, and location. In optimizing the model's performance, several loss functions were explored:

Squared Loss Function (L2 loss): This function minimizes the sum of squared differences between predicted and actual values. The squared loss function is sensitive to outliers, as it penalizes larger errors more heavily, making it suitable when large deviations are particularly costly.

Absolute Loss Function (L1 loss): This function minimizes the sum of absolute differences, providing a more robust alternative to squared loss. L1 is less sensitive to outliers, treating all deviations equally, which is useful when there are significant but sparse outliers in the dataset.

Infinite Loss Function (L∞ loss): This function minimizes the largest deviation in the dataset, ensuring that the worst-case error is reduced. It is appropriate for scenarios where minimizing the largest error is critical.

By comparing the model's performance under each loss function, the trade-offs between sensitivity to outliers and robustness were evaluated to select the most suitable one for this regression task.

Conclusion

R2 score for Linear Regression Problem in Python displayed results closer to 0.98, 0.91, and 0.85 for Squared, Absolute, and Infinite loss functions respectively, and observed how the line fits and reacts to outliers to each loss function![image](https://github.com/user-attachments/assets/bc5c5fb5-73cd-4590-93ec-4b5defb7a83d)
