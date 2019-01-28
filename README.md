# Recommendation Systems Using Factorization Machine and Wide and Deep Learning

Authors: Deepak Ravishankar(dr2998),Yu Han Huang(yh3093),

Final project for the Personalization: Theory and Applications class (Columbia University, Fall 2018)

## Business Problem:
In both Factorization Machines and Wide and Deep Learning, we want to learn how the algorithms can effectively recommend our users to the movies that they might like. We try to optimize our recommendation system to minimize the difference in our prediction of users’ rating and their real preference. Since the dataset we use is relatively large, we are also interested in knowing how well these algorithms scale with the data size. More detailed objective and evaluation of individual system are explained in the report.


## Data:
We used the MovieLens 1M Dataset due to the following considerations: 
  1) It provides demographic information of the users and movie information which enables us to construct a factorization machine   incorporated with additional information that can assist in prediction and can be compared with our original factorization machine. 
  2) The data size is sufficiently large with 1,000,209 anonymous ratings of 3,706 movies made by 6,040 MovieLens users who joined MovieLens in 2000.
  3) The data can be downloaded from: https://grouplens.org/datasets/movielens/

## Contents:
- Factorization Machine - No Side Information.ipynb : Factorization Machine with no side information but user and movie data
- Factorization Machine - With Side Information.ipynb : Factorization Machine with side information including user demographic and movie genres
- Factorization Machine Model Extension - Hybrid Model.ipynb : Efforts to improve the factorization machine model
- Deep and Wide Model.ipynb : The deep and wide model implemented from the following paper: https://arxiv.org/pdf/1606.07792.pdf
- Report.pdf : Report explaining the experiments done
