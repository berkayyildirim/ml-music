# **Music Dataset Analysis Using Machine Learning**

## **Overview**

This project analyzes a music dataset to explore trends and patterns, predict outcomes, and derive actionable insights using machine learning techniques. The study involves data preprocessing, exploratory data analysis (EDA), and building predictive models to uncover relationships within the dataset.

The models and analysis help demonstrate how machine learning can enhance decision-making in music-related domains such as recommendations, genre classification, and trend predictions.

---

## **Key Features**

- **Data Preprocessing**:

  - Cleaned and normalized raw data to handle missing values and outliers.
  - Encoded categorical features such as genre, artist names, and track popularity.

- **Exploratory Data Analysis (EDA)**:

  - Visualized patterns in features like tempo, energy, and danceability.
  - Analyzed correlations between song attributes and their popularity.

- **Machine Learning Models**:

  - Developed classification and regression models for tasks such as:
    - Predicting song popularity.
    - Classifying genres based on song attributes.
  - Experimented with ensemble methods (e.g., Random Forest, Gradient Boosting) and optimized hyperparameters for performance.

- **AWS Integration**: (todo)
  - Utilized AWS SageMaker for scalable model training and evaluation.
  - Leveraged AWS S3 for storing large datasets and AWS Lambda for on-demand model execution.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib, seaborn
- **Machine Learning**: Regression models, classification algorithms, ensemble methods
- **Cloud Services**: AWS S3, SageMaker, Lambda (todo)
- **Visualization**: matplotlib, seaborn

---

## **Results**

- **Key Insights**:

  - High tempo and energy are positively correlated with song popularity.
  - Danceability and loudness are critical features for genre classification.
  - Popular songs often exhibit a balance between acousticness and instrumentalness.

- **Model Performance**:
  - **Genre Classification**: Achieved an accuracy of **85%** using a Random Forest Classifier.
  - **Popularity Prediction**: Achieved an R² score of **0.78** using Gradient Boosting Regressor.

---

## **Future Improvements**

- Experiment with deep learning models like Convolutional Neural Networks (CNNs) for audio feature extraction.
- Include text-based data such as song lyrics to enrich predictions and classifications.
- Develop a REST API to integrate the model into music recommendation systems.
- Scale up the analysis using larger datasets from streaming platforms.

---

## **Author**

**Berkay Yildirim**

- MSc Artificial Intelligence, UWE Bristol
- [LinkedIn](https://linkedin.com/in/huseyin-berkay-yildirim)
