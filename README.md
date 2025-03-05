# Music and Stress Reduction


Music has an affect on everyone. It has the ability to enhance the mood that you are experiencing. I believe that music has healing properties, according to the National Institute of Health " Adult patients with moderate-to-severe symptoms receiving music therapy in community hospitals reported clinically significant mean reductions in pain (2.04), anxiety (2.80), and stress (3.48)" 

> Rodgers-Melnick, S. N., Rivard, R. L., Block, S., & Dusek, J. A. (2023, April 13). ***Effectiveness of music therapy within Community Hospitals: An Emmpire retrospective study.*** Pain reports. [NIH](https://pmc.ncbi.nlm.nih.gov/articles/PMC10508459/#:~:text=Adult%20patients%20with%20moderate%2Dto,%2C%20and%20stress%20(3.48).)


The purpose is to determine if there is a specific genre that has the best effect on improving mental health/mood. 

## Description

Reviewed survey data where individuals answered questions about type of mental health issues they experience and where they denoted their favorite genre of music and whether or not that music improves there mental health.

Reviewed dataset that detailed popularity of Spotify songs based on a script that fetched songs based on popularity using score of 0 to 100 where the higher the number the more popular the song. 

Since I used the popularity dataset from Spotify, I used only the survey responses that had primary streamining service of spotify as listed. From there I looked at the genres listed and using statistical model of confidence intervals to see if one genre was significantly significant and from there reviewed popular songs by genre.

## Getting Started

### Dependencies

* Used Python, and DBBrowser for SQLite
* used a Mac OS Sequoia 15.3.1

### Virtual Environment
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create  | python3 -m venv venv | python -m venv venv |
| Activate | source venv/bin/activate | source venv/Scripts/activate |
| Install | pip install -r requirements.txt or pip install packages | pip install -r requirements.txt or pip install packages|
| Deactivate | deactivate | deactivate |



## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

