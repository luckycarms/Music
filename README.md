# Music and Stress Reduction


Music has an affect on everyone. It has the ability to enhance the mood that you are experiencing. I believe that music has healing properties, according to the National Institute of Health " Adult patients with moderate-to-severe symptoms receiving music therapy in community hospitals reported clinically significant mean reductions in pain (2.04), anxiety (2.80), and stress (3.48)" 

> Rodgers-Melnick, S. N., Rivard, R. L., Block, S., & Dusek, J. A. (2023, April 13). ***Effectiveness of music therapy within Community Hospitals: An Emmpire retrospective study.*** Pain reports. [NIH](https://pmc.ncbi.nlm.nih.gov/articles/PMC10508459/#:~:text=Adult%20patients%20with%20moderate%2Dto,%2C%20and%20stress%20(3.48).)

## Overview
The purpose is to determine if there is a specific genre that has the best effect on improving mental health/mood. Three datasets were utilized to explore the relationship between music, mental health, and the popularity of Spotify songs.

## Data
The first dataset used in this project contains survey information related to mental health and whether or not there is improvement in mental health with music. 

The next datasets used in this project contains popular spotify songs.

- [Music & Mental Health Survey Results](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)

- [Spotfiy Music Datasets](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset)


## Description

Reviewed survey data where individuals answered questions about type of mental health issues they experience and where they denoted their favorite genre of music and whether or not that music improves there mental health.

Reviewed dataset that detailed popularity of Spotify songs based on a script that fetched songs based on popularity using score of 0 to 100 where the higher the number the more popular the song. 

Since I used the popularity dataset from Spotify, I used only the survey responses that had primary streamining service of spotify as listed. From there I looked at the genres listed and using statistical model of confidence intervals to see if one genre was significantly significant and from there reviewed popular songs by genre.

## Project Structure
1. Data exploration: Jupyter Notebook
2. Analysis: Using Python with the Pandas package to clean the data as well as using DBBRowser for SQLite to organize the data
3. Visualizations: Used Matplotlib, Seaborn and Wave to visualize data


## Features Utilized for the project

| Feature          | Description                          |
|------------------|--------------------------------------|
| Read one dataset in with an API and one data set from csv | Read in dataset from kaggle first one using Kagglehub the second one from downloading the files|
| Cleaned survey dataset | In jupyter notebook cleaned the survey dataset and then later merged it with the spotify dataset. |
| Cleaned the spotify dataset | In DBBrowser for SQlite cleaned and filtered dataset then performed a union for the high and low popularity data. |
| Visualization | Made a bar graph, A waveform and a heatmap using Matplotlib, Seaborn, and Wave. |
| Utilize a virtual environment      | Made a venv for this project. |
| Notate code with markdown cells in Jupyter Notebook | Included notes in my code describing the code blocks. |


## Getting Started
1. Clone the repository: `git clone https://github.com/luckycarms/Music.git'
2. Install the necessary dependenciesL `pip install -r requirements.txt'
3. Explore the Jupyter notebook

## Dependencies
* Used Python, and DBBrowser for SQLite
* Review requirements text.
* used a Mac OS Sequoia 15.3.1 

### Virtual Environment
#### Instructions
- After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal.
- Create a virtual environment in the project folder. 
- Activate the virtual environment.
- Install the required packages. 
- When you are done working on your repo, deactivate the virtual environment.

#### Commands
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create  | python3 -m venv venv | python -m venv venv |
| Activate | source venv/bin/activate | source venv/Scripts/activate |
| Install | pip install -r requirements.txt or pip install packages | pip install -r requirements.txt or pip install packages|
| Deactivate | deactivate | deactivate |





