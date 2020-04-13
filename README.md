# Recommender-system-by-NMF

Developing a recommender system by Non-negetive matrix factorization method along with data analysis
 
 <br /> Dataset : 100k movielens
 <br /> The dataset that has been used for this project is collected from MovieLens web site byGroupLens research group in the Department of Computer Science and Engineering at theUniversity of Minnesota. This data set has a small volume and is recommended for educationand development purposes.It contains 100836 ratings and 3683 tag applications applied to9742 movies. It was collected from 610 users which each rated at least 20 videos, and they wereidentified by ID only. The dataset was generated on September 26, 2018.Provided data set contains four main files links.csv, movies.csv, ratings.csv and tags.csv,and among them movies.csv, ratings.csv are the files which used in this project for movierecommendation.  rating.csv file contains all ratings info.  In each row, there exists userId,movieId, rating and timestamp which represents the rating of a movie given by a user. Ratingshave a 5-star scale, with half-star increments.  On the other hand, movies info are given inmovie.csv file with each row of movieId, title and genres. List of genres are as follows: Action,Adventure, Animation, Children’s, Comedy, Crime, Documentary, Drama, Fantasy, Film-Noir,Horror, Musical, Mystery, Romance, Sci-Fi, Thriller, War, Western and (no genres listed)
 
 <br /> NMF method:
 <br /> NMF can be used for recommender systems and is based on decomposing user-item interaction matrix to two low dimensional matrices. It is interesting to note that this method considers hidden features or latent factors for decomposition and at the end approximating missing entries in user-item matrix. More xplanations about NMF method can be foung in this link:https://medium.com/@farnazgh73/non-negative-matrix-factorization-nmf-4798d29e8c62

