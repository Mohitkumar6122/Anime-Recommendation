# Anime-Recommendation

Building anime recommendation system based only on user viewing history, Genre and other features.

![table](https://wallpapercave.com/wp/wp5257135.jpg)

## DATASET
This dataset is taken from : https://www.kaggle.com/CooperUnion/anime-recommendations-database?select=anime.csv <br/>
**myanimelist.net API for providing anime data and user ratings.**

This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings.

## Content

### Anime.csv

1. anime_id - myanimelist.net's unique id identifying an anime.
2. name - full name of anime.
3. genre - comma separated list of genres for this anime.
4. type - movie, TV, OVA, etc.
5. episodes - how many episodes in this show. (1 if movie).
6. rating - average rating out of 10 for this anime.
7. members - number of community members that are in this anime's "group".

### Rating.csv

1. user_id - non identifiable randomly generated user id.
2. anime_id - the anime that this user has rated.
3. rating - rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).
