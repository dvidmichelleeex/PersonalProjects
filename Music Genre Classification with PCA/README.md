# Music Genre Classification with PCA

## Problem Statement
How can we effectively classify and predict the genre of music tracks based on their unique characteristics, such as tempo, rhythm, and more?

## Objectives
1. Classify music tracks by their genre using a machine learning model (Logistic Regression).
2. Predict genres for tracks with missing genre labels.
3. Evaluate the effectiveness of Principal Component Analysis (PCA) as a dimensionality reduction technique to improve model performance.

## Tools Used
Jupyter Notebook, Python

## Project Files
- **Music Data Legend.xlsx**: Contains descriptions and data types of each characteristic used in the dataset.
- **music_dataset_mod.csv**: The dataset with 1,000 music tracks, each with distinct characteristics and genres (some genres are missing).
- **Music Genre Classification with PCA - Project.ipynb**: Jupyter notebook containing all code and steps of the project.

## Dataset Overview
The dataset includes the following characteristics:
- **Tempo**: Beats per minute of a track.
- **Dynamic Range**: Difference between the quietest and loudest parts.
- **Vocal Presence**: Prominence of vocals.
- **Percussion Strength**: Intensity of percussion instruments like drums.
- **String Instrument Detection**: Prominence of string instruments like guitars.
- **Electronic Element**: Use of electronic sounds or synthesizers.
- **Rhythm Complexity**: Variation in rhythm patterns.
- **Drums Influence**: Contribution of drums to the overall sound.
- **Distorted Guitar**: Use of distorted guitar sounds, common in rock and metal.
- **Metal Frequencies**: Presence of metal-like sounds.
- **Ambient Sound Influence**: Use of ambient sounds for atmosphere.
- **Instrumental Overlaps**: Interplay of multiple instruments.
- **Genre**: Categorical label of the music genre.

## Summary of Work
1. **Data Preprocessing**:
   - Cleaned the dataset by handling missing values.
   - Encoded categorical genre labels into numerical values using `LabelEncoder`.

2. **Correlation Analysis**:
   - Identified strong correlations between features such as "Distorted Guitar" and "Metal Frequencies" (approx. 0.9).
   - Addressed multicollinearity issues by applying PCA.

3. **Dimensionality Reduction with PCA**:
   - Reduced the dataset's dimensionality while retaining 80% of its variance.
   - Selected 8 principal components to effectively represent the dataset.

4. **Model Training and Evaluation**:
   - Trained two logistic regression models:
     - **PCA-Transformed Data**: Achieved **53.6% accuracy**.
     - **Original Data**: Achieved **52.4% accuracy**.
   - The PCA-transformed model performed slightly better in terms of accuracy and precision.

5. **Genre Prediction**:
   - Predicted genres for tracks with missing labels using the trained PCA model.
   - Updated the dataset with the predicted genres.

## Results
- PCA was effective in reducing noise and redundancy while improving model performance.
- The PCA-transformed model showed better accuracy and precision compared to the original data model.
- Successfully predicted missing genres, completing the dataset.

## Recommendations
- Future improvements can include balancing the dataset by increasing the representation of less frequent genres.
- Test the models with advanced classification techniques like Random Forest or Support Vector Machines (SVM).
- Use cross-validation to further validate the model's performance.

---
