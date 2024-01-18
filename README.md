# Housing-Dataset-ML-Models
*Dataset:* House Sales in King County, USA: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

*Tools:* Python, Jupyter Notebook, Visual Studios, Kaggle
# Problem Explanation
Housing price prediction is a powerful tool to help homeowners, investors, and businesses with impactful financial decisions. The goal of this project is to accurately curate machine learning models to predict the housing sales prices of homes in the dataset and to understand the results of the experiment and the reasoning for their performance. The dataset that was selected contains the selling price of houses in King County, Washington along with 20 other features of the home. These features include a unique id for the home, sale date, number of bedrooms, number of bathrooms, square footage of the home, square footage of the land, number of floors, waterfront boolean, view score, condition score, grade score, square footage of above ground floors, square footage of the basement, year built, year renovated, zip code, latitude, longitude, square footage of the living space of the 15 closest neighbors, and the square footage of the land of the 15 closest neighbors. This dataset will be modeled with many different machine learning algorithms to analyze their performance at predicting the homes sales price. These models include linear regression, k-nearest neighbors regression, neural network regression, single decision tree, bagged trees, and boosted trees.
# Evaluation Criteria
To evaluate the regression models’ success against each other, the error of the predictions will be used, specifically the Root Mean Squared Error (RMSE) and the R2 values. The error evaluation will be performed on both the training and testing predictions for overall model accuracy, as well as to determine if any over or underfitting is occurring. From these results, the best performing models can be found and further analysis for each model can be explained.
# General Results
The experiment had five main classes of models: linear regression, k-nearest neighbors, neural networks, and decision trees. Overall, the performance of the decision trees far exceeded the performance of the other model types. Decision trees, specifically the boosted decision tree regression, output the best results at predicting the housing sales price. This is due to the boosted tree’s ability to sequentially build trees that reduce error with each iteration to produce the final strong learner. Boosted trees also excel at reducing bias and variance in ‘noisy’ data as well as data that contains outliers. For this reason, the boosted decision tree outperformed the other tested machine learning models.
# Conclusion
Predicting housing sales prices is significant. It is crucial in investment decisions to identify overpriced or underpriced homes to determine the best time to buy or sell a property to maximize earnings. It can also be used by homeowners to know the price of their home for future financial planning. Banks and mortgage lending businesses can use a home’s predicted price to assess the risks of providing a mortgage to a home and to determine the amount of the loan and interest rates. Overall, the price of a home is rather specific to its many features. With the use of machine learning models, relatively accurate price predictions can be made to help make informed financial decisions.
