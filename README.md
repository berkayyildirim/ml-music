# **Music Dataset Analysis Using Machine Learning**

## **Overview**

This project analyzes a music dataset to explore trends and patterns, predict outcomes, and derive actionable insights using machine learning techniques. The study involves data preprocessing, exploratory data analysis (EDA), and building predictive models to uncover relationships within the dataset.

The models and analysis help demonstrate how machine learning can enhance decision-making in music-related domains such as recommendations, genre classification, and trend predictions.

---

## **Key Features**

- **Data Preprocessing**:

  - Cleaned and normalized raw data.
  - Encoded categoritarget label.

- **Exploratory Data Analysis (EDA)**:

  - Visualized patterns in features like tempo, energy, and danceability.
  - Analyzed correlations between song attributes and their popularity.

- **Machine Learning Models**:

  - Developed classification models for tasks such as:
    - Classifying genres based on song attributes.
  - Experimented with ensemble methods (e.g., Random Forest, Gradient Boosting) and optimized hyperparameters for performance.

- **AWS Integration**: (todo)
  - Utilized AWS SageMaker for scalable model training and evaluation.
  - Leveraged AWS S3 for storing large datasets and AWS Lambda for on-demand model execution.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib, seaborn
- **Machine Learning**: Classification algorithms, ensemble methods
- **Cloud Services**: AWS S3, SageMaker, Lambda (todo)
- **Visualization**: matplotlib, seaborn

---

## **Results**

- **Key Insights**:

  - High tempo and energy are positively correlated with song popularity.
  - Danceability and loudness are critical features for genre classification.
  - Popular songs often exhibit a balance between acousticness and instrumentalness.

- **Model Performance**:
  - **Genre Classification**: Achieved an accuracy of **62.66%** using a Tuned Gradient Boosting.

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
