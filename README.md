# 🎧 Exploratory Data Analysis (EDA) on Spotify Dataset

In this project, I’ve compiled and analyzed a dataset with over 500,000 songs from Spotify, one of the world’s most popular music streaming platforms.

The aim of this analysis is to explore how music varies across genres, moods, and years — and ultimately answer key questions about what makes a song feel good, energetic, or relaxing. The analysis focuses on mood-related metrics like valence, energy, and danceability, as well as temporal and genre-based patterns.

## 📁 Project Structure

eda-spotify/
├── data/
│   ├── spotify_dataset.csv                                 # Dataset that I worked on
│   └── 900k Definitive Spotify Dataset.json                
│   └── final_milliondataset_BERT_500K_revised.json         
├── notebooks/
│   └── eda_spotify.ipynb                                   # Jupyter Notebook with the analysis
├── archive/
│   └── 900k-spotify.zip                                    # Original compressed file (optional)

### 📚 Notebooks Available

- [🇬🇧 English Version](notebooks/spotify_eda_ENG.ipynb)
- [🇪🇸 Versión en Español](notebooks/spotify_eda_ESP.ipynb) ( NOT AVAILABLE )

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 🧹 Data Cleaning Process

- Removed null values and duplicates
- Converted text columns to appropriate formats
- Created a cleaned version of the dataset for analysis

### 📊 Key Analysis Topics

This EDA addresses the following questions:

1. **What are the top 10 songs with the highest “feel-good” vibes?**
2. **Which artist transmits the most overall flow based on average mood-related metrics?**
3. **What are the TOP 3 songs in different contexts?**
    - 🎉 **Party**
    - 💻 **Work**
    - 🏋️‍♂️ **Exercise**
    - 🧘 **Relaxation**
    - 🚗 **Driving**
4. **How has the positivity index (valence) evolved year by year?**
5. **What does the distribution of song quantity look like per year and genre?**
6. **Includes a final personal analysis, exploring subjective observations and musical curiosities.**

### 🔍 Key Insights

- 🎶 The **top 10 "feel-good" songs** are determined by the highest valence scores, showcasing uplifting and positive tracks.
- 🌍 The **artist with the most overall flow** based on average mood-related metrics is identified, offering insights into artists who maintain high energy and positive vibes in their music.
- 🎧 **Top 3 songs** for different contexts, such as partying, working, exercising, relaxing, and driving, are explored, helping to categorize music based on common activities and moods.
- 📅 **Positivity index evolution** shows how the average valence score has changed over the years, revealing trends in the music industry.
- 📊 **Distribution of songs per year and genre** helps to understand how different genres have evolved over time in terms of popularity and production volume.
- 🧐 The **personal analysis** on trends in musical keys

## 📌 Notes

- All data used is public and comes from a third-party dataset compiled from Spotify, covering a wide range of years and artists.
- This is a solo project developed for learning and portfolio purposes.

## 👤 Author

**Ferran Piqueras Pons**  
[LinkedIn](https://www.linkedin.com/in/fpiqueraspons/) · [GitHub](https://github.com/Tzantza)