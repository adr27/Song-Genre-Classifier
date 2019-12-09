# Song-Genre-Classifier


Project_CK_v1.ipynb contains the final code for the project.
songDb.tsv contains the datas set we used for the Project.

The initial code is normalizing all the values in different columns and dropping incomplete cases.
A correlation matrix is then generated to understand different relationships in the data. 
Prinicipal component analysis is then done on the data set. 
Mode, name are then dropped because they are not required and dont affect the prediction of a Genre
K means clustering is then done to look at different groups of song genres.
We then pick 10 Genres to try and predict.
The first model we build is Random forest, then k nearest neighbour and then state vector classification.
