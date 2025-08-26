
# Skin Type Detection

## **Problem Background**

I am a data scientist currently working at a renowned beauty clinic in Jakarta. With the increasing demand for personalized skincare solutions, we plan to develop a technology that can detect an individual's skin type: oily, dry, or normal. This technology will implement a machine learning model utilizing the **Oily, Dry, and Normal Skin Types Dataset** to automatically detect skin types, aiming to improve diagnostic accuracy and personalize product recommendations for users.

## **Project Output**

- **Automated Skin Type Detection System**: High-accuracy skin type detection from facial images.
- **Enhanced User Experience**: Personalized skincare product recommendations.
- **Machine Learning Model**: CNN model trained for skin type classification.
- **Model Evaluation**: Accuracy report and test results analysis.
- **System Integration**: Integration with the clinic’s application for faster diagnostics.

## **Dataset Overview**

This dataset consists of 3,152 facial images used for skin type detection (Oily, Dry, Normal), divided into Training, Validation, and Testing datasets.

### **Data Distribution Before Cleaning:**

- **Training (2,756 images)**:
  - Dry: 23.7%
  - Normal: 40.0%
  - Oily: 36.3%
- **Validation (262 images)**:
  - Dry: 27.1%
  - Normal: 42.4%
  - Oily: 30.5%
- **Testing (134 images)**:
  - Dry: 26.1%
  - Normal: 44.0%
  - Oily: 29.9%

### **Data Distribution After Cleaning:**

- **Training (677 images)**:
  - Normal: 34.5%
  - Oily: 34.2%
  - Dry: 31.3%
- **Validation (94 images)**:
  - Normal: 35.1%
  - Oily: 34.0%
  - Dry: 30.9%
- **Testing (195 images)**:
  - Normal: 34.4%
  - Oily: 34.4%
  - Dry: 31.3%

### **Total Data After Cleaning: 966 images**

The dataset is now more balanced, ready for analysis and modeling, reducing the risk of overfitting.

## Method

The methods used in the analysis include central tendency calculations, descriptive statistics using confidence intervals to understand the potential profits, and inferential statistics using Pearson correlation to examine the relationships between variables.

## Conclusion & Recommendation

* **Diesel Cars** offer better price benefits, but they fall short in terms of mileage and fuel efficiency. Overall, **petrol cars** provide better value for money in the **NON-EV** category.
* Based on the **confidence interval** results, the top 5 car models for each fuel type are as follows:

  * **Petrol cars** : The best return for diesel vehicles is seen with the **M5 Petrol 2019** and **8 Series 2019 Petrol** models.
  * **Diesel cars** : The **X6 Diesel 2020** model offers the best return for diesel cars.
  * **Hybrid cars** : The best hybrid models are the **i8 2017** and  **i8 2019** .
  * **Electric cars (EV)** : The **i3 2016** is the top-performing EV.
* The selection of these car units is based on an observation of the correlation between price and mileage for each fuel type, combined with insights from car prices, mileage, and engine sizes across different price categories (from cheap to expensive). The findings will be shared with the company to assist in further decision-making.

## Stacks

The analysis is performed using Python to manage the data and conduct statistical calculations. Tableau is used for data visualization. In Python, I utilized the **pandas** library for data management, **scipy** for statistical analysis, and **seaborn** and **matplotlib** for data visualization.

To install the necessary dependencies, run the following command:

```bash
pip install -r requirements.txt
```

## References

- [BMW Used Car Dataset from Kaggle](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes/data?select=bmw.csv)
- [Tableau Visualization](https://public.tableau.com/app/profile/rafi.siregar/viz/milestone_17478445912520/Dashboard2?publish=yes)
