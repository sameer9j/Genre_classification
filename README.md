# Music Genre Prediction System using Audio and Lyrics Ensemble Models

Purpose: To create a model, which automatically predicts the genre of any new music developed by a user. An ideal use case would be - song streaming websites using the system to easily identify song genres for unlabelled songs.

Tools Used: Jupyter Notebook, Python

Overview of each code:

1. audio_analysis/Audio EDA v0.1ss.ipynb: 
The code contains:

  * Exploratory audio data analysis 

2. audio_analysis/Audio Models+Ensemble v0.1ss.ipynb:
  
  * Audio Modeling - QDA, Logistic, SVM
  
  * Ensemble models

3. Text Modeling (5000 words, 1000 word) - text_analysis/final_text_analysis.ipynb
The code contains:

  * Text Modeling - Random Forest, Gradient Boosting, Multilayer Perceptron
  
  * Ensemble Model

4. Text EDA - data_eda/word_cloud.ipynb
 
5. Ensemble Boosting.ipynb: 
The code contains:

  * Boosting for ensemble 

6. LyricBagofWordsClassifier.ipynb
This code contains:

  * Text modeling (500 word) - Random Forest, SVM, KNN, Logistic Regression
  
## Datasets Used:
1. Genre Annotations:
 http://www.tagtraum.com/msd_genre_datasets.html (File name: msd_tagtraum_cd2c.cls.zip)
 
2. Audio Dataset:
 https://labrosa.ee.columbia.edu/millionsong/tasteprofile

3. Lyrics Dataset:
 https://labrosa.ee.columbia.edu/millionsong/musixmatch
