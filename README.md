# car_price_prediction using linear regression-

Built a Machine Learning regression model to predict Ford car prices using a real-world automotive dataset. The project covers complete EDA, feature relationship analysis, 
data preprocessing using both One-Hot Encoding and Label Encoding, feature scaling, and training a Linear Regression model evaluated using standard regression metrics.

Applied One-Hot Encoding using pd.get_dummies() on model, transmission, and fuelType columns
Additionally applied Label Encoding as an alternative encoding approach for comparison
Standardized numerical columns — year, mileage, tax, mpg, engineSize — using StandardScaler
Split dataset into training and testing sets with 67/33 ratio using train_test_split

Model Used
Linear Regression — Trained on One-Hot Encoded and scaled features to predict continuous car price values. 
Evaluated using R² Score to measure the proportion of variance explained by the model.
