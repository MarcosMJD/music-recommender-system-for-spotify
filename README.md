# spotify-music-recommender-system
Music recommender system from Spotity playlists dataset

Made for the initiative project-of-the-week from DataTalks.club
https://github.com/DataTalksClub/project-of-the-week/blob/main/2022-10-19-recommenders-1.md

## Dataset
Spotify Playlists. 1.2GB of tabular data for music recommendation
https://www.kaggle.com/datasets/andrewmvd/spotify-playlists

## Plan
- [x] Select dataset
- [x] Create repo in git
- [x] Clone repo and setup environment (pipenv, install libraries)
- [x] Download dataset
- [x] EDA in jupyter notebook
- [x] Analyse sparcity
- [ ] Set a baseline
- [ ] Set model evaluation metrics
- [x] Analyse solutions
- [x] Implement matrix factorization model with LightFM
- [ ] 

## Notes
- In collaborative filtering, consider weight samples in order to avoid frequent queries or frequent items dominate the objective function
- Consider cold start problem in collaborative filtering: https://developers.google.com/machine-learning/recommendation/collaborative/summary?hl=en
- 

## Useful commands

Update pip on Windows: `python -m pip install --upgrade pip`
Update pipenv before creating the virtual env: `pip install --upgrade pipenv`
Create basic virtual env: pipenv install pandas numpy --dev ipython

