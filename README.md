# Movies-ETL
## Overview
In this project is basicly to start and hone my skills in the ETL process. Using datasets from different sources. The data must be cleaned and merged in order to later write it inside a database using SQLAlchemy.

## Results 
The results were the good cleaning of all the data of the different datasets using regex expresions to find out different types of formats that were in the datasets and parse them in order to have a more consistent dataset. Most of the de cleaning had to be made to the wikipedia json file due to the large amount and variety of values. A same approach was made onto the kaggle dataset and afterwards using scatter plots it was determined which columns should be kept. The join was made using the imdb ids and finally the ratings were added to have another table inside of our database.

The code was then refactored into a function in order to be able to use it in future datasets.

## Conclusion
The ETL process is one that requires patience and does not have to be so complicated it is better to start with small modifications and as you do them then more irregularities will be poping up. This irregularities then can be addressed and rinse and repeat. 
