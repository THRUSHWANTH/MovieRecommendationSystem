# MovieRecommendationSystem
This Project is about  building simple and content based movie recommendation engine.

SIMPLE RECOMMENDATION SYSTEM 
  In this recommendation system , top ten movies will be predicted based on votes and ratings given to that movie.Here popularity score is calculated for every movie based on 
  following formula. 
  
  weighted score/popularity score= ((v/(v+m)*R))+((m/(v+m))*C)
  v = votecount
  m= minimum votes required to get in list
  R=Average Rating of the movie
  C=Mean vote of whole movies 
  
  
CONTENT BASED RECOMMENDATION SYSTEM
 Here we find top ten movies similar to given paticular movie.Here we used TF-IDF(Trem frequency  - inverse document frequency) to get weighted matrix and used Cosine similarity
 to find similar movies.We also used Director,cast,genre to find similarity score.Here I given more weightage to director in soup sentence to get most similar movie .
 
