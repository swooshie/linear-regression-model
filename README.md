For my Linear Regression model project, I used the Housing dataset to predict property prices based on various features like square footage, number of rooms, and location. To optimize the performance of the model, I explored multiple loss functions:

Squared Loss Function (L2 loss): I implemented this to minimize the sum of squared differences between predicted and actual values. This loss function is sensitive to outliers, as it penalizes larger errors more heavily, making it ideal when large deviations are particularly costly.

Absolute Loss Function (L1 loss): This approach minimizes the sum of absolute differences, offering a more robust alternative to squared loss. L1 is less sensitive to outliers, as it treats all deviations equally, which made it useful when there were significant but sparse outliers in the dataset.

Infinite Loss Function (L∞ loss): I also experimented with the infinite loss function, which focuses on minimizing the largest deviation in the dataset. This loss function ensures that the worst-case error is minimized, making it appropriate for scenarios where minimizing the largest error is critical.

By comparing the performance of the model under each of these loss functions, I was able to better understand the trade-offs between sensitivity to outliers and robustness, and select the most suitable one for this regression task.
