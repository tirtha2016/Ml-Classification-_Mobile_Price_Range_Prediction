# Ml-Classification-_Mobile_Price_Range_Prediction

![smartphones](https://github.com/tirtha2016/Ml-Classification-_Mobile_Price_Range_Prediction/assets/130783172/a818abc7-0332-4d27-944b-17b5cdb909db)



# Project Summary

 The mobile phone industry is fiercely competitive, and the price of a mobile phone is determined by multiple factors such as battery power, Bluetooth, camera quality, and screen size. To investigate the factors that influence the price range of mobile phones, a study was conducted. The study utilized a dataset containing approximately 21 variables to forecast the price range of mobile phones, which are categorized as low, medium, high, and very high.

 Initially, the analysis process focused on data wrangling, which involved managing missing values and verifying unique values. During this stage, it was discovered that 180 mobile phones had a pixel resolution height of 0, and two phones had a screen width of 0 cm. It is not logical for a phone screen width or pixel height to be 0, so I decided to replace these 0 values with the mean values. This ensured that the dataset had no missing values.

 After that  I finished data wrangling, I performed exploratory data analysis (EDA). From this analysis, I discovered that all categories of mobile phones had an equal price range distribution. Furthermore, I found that there was a positive correlation between the battery capacity of a phone and its price range. The distribution of battery capacity also gradually increased as the price range increased, implying that consumers may be willing to pay more for a mobile phone with a higher battery capacity. In terms of Bluetooth usage, I found that almost half of the devices had it, while the other half did not.

 From the scatter plot, it was evident that there was a positive correlation between RAM and price range. The majority of the data points were clustered towards the upper right corner, indicating that as the price range increased, so did the amount of RAM in the device. The study also discovered that the count of devices with dual sim was increasing for the highest price range. Furthermore, the distribution of primary camera megapixels across various target categories remained consistent, suggesting that this feature may not have a significant impact on the price range of mobile phones.

 Based on the analysis of screen size distribution among different target categories, it was observed that there was not a significant difference in the distribution. This suggests that screen size alone may not be the primary factor in determining target categories. However, this consistency in distribution can be beneficial for predictive modeling, as it indicates that screen size may not play a significant role in distinguishing between different target categories, enabling other features to have a more significant impact in determining the target categories. Additionally, the study revealed that mobile phones with higher price ranges were generally lighter in weight than those with lower price ranges.

 Following the exploratory data analysis (EDA), the study conducted hypothesis testing on three statements while handling outliers. During this process, the study identified that RAM, battery power, and pixel quality were the most significant factors influencing the price range of mobile phones. Afterwards, the study engaged in feature engineering and utilized various machine learning models, such as logistic regression, random forest, and XGBoost. After conducting experiments, the study found that logistic regression and XGBoost algorithms with hyperparameter tuning delivered the most accurate results in predicting the price range of mobile phones.

 In summary, the study discovered that the mobile phones in the dataset were separated into four distinct price ranges, each containing an equivalent number of elements. Roughly half of the devices in the dataset had Bluetooth, while the other half did not. Additionally, the study observed that as the price range increased, there was a gradual rise in battery power, and the amount of RAM in the device exhibited continuous growth from low-cost to very high-cost phones. Moreover, the study identified that expensive phones generally tended to be lighter than their lower-priced counterparts.

# Problem Statement

In the competitive mobile phone market, companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

# Main Libraries Used

1. Pandas for data manipulation and agrregation.
2. Matplotlib and Seaborn for visualization and behavior with respect to the target variable.
3. Numpy for computationally efficient operations.
4.  Scikit Learn for model training, model optimization and metrics calculation.

![ml project](https://github.com/tirtha2016/Ml-Classification-_Mobile_Price_Range_Prediction/assets/130783172/7b9c183b-6105-43a1-af48-1993ef53aaa3)

