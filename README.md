# Using Posters to Recommend Anime and Mangas in a Cold-Start Scenario

Featuring Blended Alternate Least Squares with Explanation (**BALSE**).

- [PDF](https://arxiv.org/abs/1709.01584) on arXiv
- Comments on [Hacker News](https://news.ycombinator.com/item?id=15203024)

To quote the paper, please use:

    @article{Vie2017,
       author = {{Vie}, Jill-J{\^e}nn and {Yger}, Florian and {Lahfa}, Ryan and {Clement}, Basile and 
        {Cocchi}, K{\'e}vin and {Chalumeau}, Thomas and {Kashima}, Hisashi},
        title = "{Using Posters to Recommend Anime and Mangas in a Cold-Start Scenario}",
      journal = {ArXiv e-prints},
    archivePrefix = "arXiv",
       eprint = {1709.01584},
     primaryClass = "cs.IR",
     keywords = {Computer Science - Information Retrieval, Computer Science - Learning,
        Statistics - Machine Learning, recommender system, cold-start, collaborative filtering, LASSO, tag prediction},
         year = 2017,
        month = sep,
       adsurl = {http://adsabs.harvard.edu/abs/2017arXiv170901584V},
      url = {https://arxiv.org/abs/1709.01584},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }

## Mangaki Data Challenge

We organize a data challenge about recommender systems with Kyoto University. Until **October 1**.

Predict taste! Win prizes! [Compete Now!](http://research.mangaki.fr/2017/07/18/mangaki-data-challenge-en/)

## Dataset

Dataset will be released once the competition is finished.

In the meantime, you can check:

- Our [implementation of BALSE](https://github.com/mangaki/mangaki/blob/master/mangaki/mangaki/algo/balse.py) using Tensorflow, scikit-learn
- Our [Jupyter notebook](https://github.com/mangaki/notebooks/blob/master/Balse%202.ipynb) for the benchmarks
