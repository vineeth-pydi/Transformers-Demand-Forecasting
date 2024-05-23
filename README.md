# Transformers-Demand-Forecasting
# Application of Transformer Models for Demand Forecasting in the FMCG Industry

## Project Overview

Welcome to our repository dedicated to the research project aimed at enhancing demand forecasting in the Fast-Moving Consumer Goods (FMCG) industry using advanced transformer models. Our objective is to improve forecasting accuracy by integrating external data sources and leveraging the capabilities of transformer models.

## Disclaimer

Due to a Non-Disclosure Agreement (NDA) with our industry partner, we cannot share specific data sets or disclose the name of the company involved in this project. All proprietary information has been omitted to comply with the terms of the NDA.

## Key Components

### Methodology

- **Data Integration**: We combine internal shipment and consumption data with external data sources such as Google Trends and Amazon reviews.
- **Modeling**: We implement transformer models like iTransformer and TimesNet for time-series forecasting and demand sensing.
- **Evaluation**: We compare the performance of the models using metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).

### Tools and Libraries

- **Programming Language**: Python
- **Libraries**: PyTorch, Scikit-Learn, Pandas, NumPy, Matplotlib
- **External Data Sources**: Google Trends, Amazon Reviews

### Model Training

We provide scripts and notebooks for training the transformer models, including steps for data preprocessing, feature engineering, and model evaluation.

## Results

- **Model Performance**: Detailed comparison of model performance on various data sets.
- **Insights**: Key insights gained from integrating external factors into the forecasting models.

## Detailed Description

### Abstract

Advanced demand forecasting techniques that adapt to changing market conditions are essential in the FMCG industry. This project presents a novel method combining demand-sensing approaches with iTransformer models, which excel at processing multivariate time series data. By integrating sentiment analysis from Google Trends, Amazon reviews, and competitors’ analysis, the model provides a comprehensive understanding of market behaviors and trends. The incorporation of DistilBERT for sentiment analysis enriches customer sentiment insights, resulting in significantly better reliability and precision than traditional forecasting techniques.

### Introduction

Accurately predicting demand in the FMCG sector is crucial due to the broad range of products, rapid turnover rates, and shifting consumer preferences. Traditional forecasting methods like linear regression struggle with the dynamic nature of the industry. This study aims to address these challenges by leveraging improved transformer models for time series data analysis and incorporating external influences such as social media trends, promotional events, and competitor activities.

### Literature Review

Transformers, initially designed for natural language processing, have shown promise in capturing temporal dependencies in time series data. Studies by Kambale et al. (2023) and Rao et al. (2023) highlight transformers' ability to manage multivariate scenarios. The iTransformer model, described in "Transformer: Inverted Transformers are Effective for Time Series Forecasting," enhances multivariate data handling by prioritizing variate tokens over temporal tokens. Despite its promise, the iTransformer’s simplicity offers quicker adaptability for FMCG workflows compared to models like Temporal Fusion Transformers (TFT) and Adversarial Sparse Transformers.

### Methodology

#### Data Integration

We integrated internal shipment and consumption data with Google Trends and Amazon reviews data, ensuring alignment by week, year, product name, and country. Sentiment scores from social media and customer reviews were incorporated to understand product sentiment.

#### Model Training

The iTransformer model was trained and tuned for our dataset, and its performance was compared against the TimesNet model using metrics like MSE and MAE. The dataset was augmented to improve training efficiency, highlighting the substantial volume of data required for transformer models.

#### Demand-Sensing

Five models (Gradient Boosting, XGBoosting, Light GBM, Random Forest, and an ensemble stacking method) were implemented to measure the sentiment surrounding the brand and competitors using a pretrained DistilBERT model.

## Results

### iTransformer Results

The iTransformer consistently outperformed the TimesNet model in MSE and MAE across prediction horizons of 48, 96, and 192 intervals, demonstrating its robustness and precision in modeling time series data.

### Demand-Sensing Results

Utilizing Google Trends and Amazon data, the ensemble model yielded the most precise predictions for both shipments and consumption. Gradient Boosting and XGBoost followed, with XGBoost showing the highest error rates.

## Conclusion

This study successfully demonstrated the effectiveness of transformer models and demand-sensing techniques for demand forecasting in the FMCG industry. By leveraging the innovative iTransformer model and integrating external factors like social media sentiment and competitive analysis, we significantly improved forecasting accuracy compared to traditional methods. The results underscore the potential of advanced analytics in enhancing demand forecasting precision, offering actionable insights for FMCG companies to navigate market volatility confidently.

## Acknowledgements

We extend our gratitude to Professor Yang Wang and Professor Matthew Lanham from Purdue University for their guidance and support throughout this research project.

## Contact

For any questions or further information, please contact:

- Vineeth Pydi: [vpydi@purdue.edu](mailto:vpydi@purdue.edu)
- Pratiksha Gupta: [gupt1018@purdue.edu](mailto:gupt1018@purdue.edu)
- Nikolai Saporoschetz: [nsaporos@purdue.edu](mailto:nsaporos@purdue.edu)
- Liana Simopoulos: [lsimopou@purdue.edu](mailto:lsimopou@purdue.edu)
- Nicholas Zimmerman: [zimmern@purdue.edu](mailto:zimmern@purdue.edu)

Feel free to explore the repository and reach out if you have any questions or need further information!

