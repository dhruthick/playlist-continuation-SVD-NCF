# Matrix Factorization for Project Automatic Playlist Continuation
In this project as part of the course, DSC 210 - Numerical Linear Algebra, we compare different approaches for matrix factorization in recommender systems. In particular we consider regular Singular Value Decomposition (SVD), SVD with bias terms, and Neural Collaborative Filtering to learn the latent factors of user/items. Our experiments are done on the Spotify Million Playlists Dataset, where we try to tackle the problem of Automatic Playlist Continuation using matrix factorization.

There are two main notebooks in this repository.
<ul>
<li> datapreprocessing.ipynb - This notebook preprocesses the interactions data to build train, valid, and test sets that are used to train and evaluate our apporaches. It takes about 90 minutes to build all the sets. The necessary data files for this notebook (interactions.csv and tracks.csv) can be found <a href='https://drive.google.com/drive/folders/1nhifU2sFqZy4bKhwj1XOV0tqbRBMLJ7O?usp=sharing'>here</a> (can be accessed with a UC San Diego account). The resultant train, test, and validation sets can also be found in the same link.
<li> svdvsncf.ipynb - This notebook trains and evaluates the models mentioned above. The results are also plotted. To run this notebook you will need the files - train_with_negative.csv, valid_wnegatives.csv, test_wnegatives.csv, and tracks.csv. All of these files can be found <a href='https://drive.google.com/drive/folders/1nhifU2sFqZy4bKhwj1XOV0tqbRBMLJ7O?usp=sharing'>here</a> (can be accessed with a UC San Diego account).
</ul>

We have also included a report explaining our work in detail in this repository.
