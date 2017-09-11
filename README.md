# Using Posters to Recommend Anime and Mangas  

[![](banner.png)](http://research.mangaki.fr/2017/07/18/mangaki-data-challenge-en/)

Featuring Blended Alternate Least Squares with Explanation (**BALSE**).

- [PDF](https://arxiv.org/abs/1709.01584) on arXiv
- Comments on [Hacker News](https://news.ycombinator.com/item?id=15203024) (We made it to the front page!)
- [Data Challenge](http://research.mangaki.fr/2017/07/18/mangaki-data-challenge-en/) running until **October 1**

## Abstract

> The classic recommendation problem is the following: given a user and the items (mangas) that they like, how can we recommend new items (mangas) that they are also likely to enjoy? Typically this is done via collaborative filtering, i.e. people with similar taste also enjoy other mangas, so we recommend these to the original user.
A very common problem occurs when you have a new or obscure manga, aka the cold-start problem. There are no reviews to use for this manga, so a cooler option is to build a system that actually understands the content it recommends. We propose extracting visual information from the posters of these little-known mangas, using a deep neural net called Illustration2Vec. The theory is that users that like mangas with "girl with sword" will also like other mangas that have "girl with sword" or perhaps "girl with bow" but probably not "multiple boys in a swimming pool".

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

[![](mangaki.png)](http://research.mangaki.fr/2017/07/18/mangaki-data-challenge-en/)

We organize a data challenge about recommender systems with Kyoto University. Until **October 1**.

Predict taste! Win prizes! [Compete Now!](http://research.mangaki.fr/2017/07/18/mangaki-data-challenge-en/)

## Dataset

Dataset will be released once the competition is finished.

In the meantime, you can check:

- Our [implementation of BALSE](https://github.com/mangaki/mangaki/blob/master/mangaki/mangaki/algo/balse.py) using Tensorflow, scikit-learn
- Our [Jupyter notebook](https://github.com/mangaki/notebooks/blob/master/Balse%202.ipynb) for the benchmarks
