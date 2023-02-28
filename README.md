# Recommendation System Course Fall 2022-23; Reichman University

Deep Neural Network for YouTube video recommendations/ P.Covington, J.Adams, E.Sargin.  
Final project by Assaf Caftory and Guy Zepko

![](https://github.com/assafcaf/YouTubeFinal/blob/main/costume_model.png?raw=true)

This repository includes our report of the paper: Deep Neural Network for YouTube video recommendations/ P.Covington, J.Adams, E.Sargin  (Anchor Paper).
https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf
1.  The report document with our analysis and innovations (pdf)
2.  Jupiter notebooks with code for experiment on MovieLens-1M (Hyperparameter tuning and display of the results)

## Results
We combined the hyperparameter tuning and results discussed in the same section under the "results" chapter in the report


## Running the notebooks
* GPU is mendatory for realistic runtime
* The data is downloaded from dropbox in the first run of the notebook and store it under "data" folder
* Dataset objects are created for each "window_size" parameter (can take several minutes per  dataset) and stored as "data/data_<window_size>.csv" for shortened future runtime
