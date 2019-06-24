# recommendation_systems

##Overview
part-01:
This is the code for the Recommender System. The code uses the lightfm recommender system library to train a
hybrid content-based + collaborative algorithm that uses the WARP ,WARP-KOS,BPR loss function on the movielens dataset.it gives the results on three different loss functions. The movielens dataset contains movies and ratings from over 1700 users. Once trained, our script prints out recommended movies for whatever users from the dataset that we choose.
part-02:
This is advancement of previous recommender system where done it using three different methods like content based,collaborativeand hybrid filtering for this instead of inbuilt dataset library used different datasets like link_small,movies_metadata,ratings_small,tmdb_5000_credits,tmdb_5000_movies csv files whih are freely available at kaggle datasets repository.

## Install the following Dependencies

numpy (http://www.numpy.org/)
scipy (https://www.scipy.org/)
lightfm (https://github.com/lyst/lightfm)
Install missing dependencies using pip
for part2 no additional dependencies are needed assuming all basic dependencies are already installed.
##Usage

Once you have your dependencies installed via pip, run the script in terminal.
