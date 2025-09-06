# Spotify Audio Analysis: Genre Classification and Popularity Prediction

Music is more than sound — it is patterns, emotions, and data waiting to be understood.  
This project explores Spotify’s audio features to classify tracks by genre, predict their popularity, and uncover the hidden patterns that make songs stand out.

---

## Project Overview
- **Genre Classification**: Predict the genre of a track based on its audio features.  
- **Popularity Prediction**: Identify the factors that make a track popular and predict its popularity score.  
- **Clustering and Trends**: Explore whether tracks with similar features form natural clusters.  
- **Interpretability**: Understand which features influence the predictions the most.  

---

## Business Use Cases
- **Streaming Platforms**: Smarter playlist recommendations and content organization.  
- **Artists and Record Labels**: Insights into what makes songs successful for strategic decision-making.  
- **End Users**: Better personalized music discovery and listening experiences.  

---

## Key Insights
- Features such as danceability, energy, and valence strongly influence genre classification.  
- Popular tracks often score high on energy and loudness, suggesting intensity plays a bigger role than tempo.  
- Clustering shows two natural families of tracks: high-energy rhythm-driven genres and acoustic or low-energy genres.  
- SHAP analysis highlights danceability and valence as significant contributors to classification performance.  

---

## Tech Stack
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)  
- LightGBM, XGBoost, Random Forest  
- SHAP (for feature interpretability)  
- Streamlit (for interactive app)  
- Spotify Web API (dataset source)  

---

## Results Summary
- **Genre Classification**: XGBoost achieved around 92% accuracy with strong precision and recall across multiple genres.  
- **Popularity Prediction**: Random Forest Regressor performed best with R² ≈ 0.78 and MAE ≈ 5.  
- **Clustering**: PCA visualizations revealed clear separation between acoustic and high-energy tracks.  
- **Recommendation Potential**: Combining genre classification and popularity prediction models can power recommendation engines.  

---

## Streamlit App
To run the application locally:  
```bash
streamlit run streamlit_app.py

---

##Repository Structure
├── Classification.ipynb   # Genre classification models
├── Regression.ipynb       # Popularity prediction models
├── Clustering.ipynb       # Clustering and visualization
├── streamlit_app.py       # Interactive web application
├── requirements.txt
└── README.md


---
Author

Name: Prithviraj Dwivedy 
Email: prithvirajdwivedy@gmail.com

LinkedIn: https://www.linkedin.com/in/prithvirajdwivedy19/
