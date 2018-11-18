# My solution to CFT Contest 2018

I with team ranked 3rd place in the [CFT Contest](https://datasouls.com/c/cft-contest/leaderboard). The task was to identify and correct typos in a person's name. We tried several approaches in this competition, but our two best scores we achieved with a voting of several seq2seq models and lightgbm on linear models predictions. It was an interesting experience primarily because of multitask learning.

## In this repository you can find:
* prepare data.ipynb - notebook with my data processing code (various counters, TF-IDF and binary features)
* models.ipynb - notebook with code of learning different models, the quality of which was checked on  classification into 2 and 3 classes
* final solution.ipynb - notebook in which I used my best Logistic Regresssion model to solve first task (Full names classification), which was used in the final ensemble, and symspellpy library to solve second task (typos correction)

## My teammates:
- [Denis Vorotyntsev](https://github.com/DenisVorotyntsev)
- [Miras Amir](https://github.com/amirassov)
