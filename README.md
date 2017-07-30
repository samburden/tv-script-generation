# Deep Learning - TV Script Generation project

This is a recurrent neural network (RNN) that generates a TV script for a scene on the Simpsons TV show. Specifically, it will generate a script for a scene at Moe's Tavern using a subset of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) which contains the scripts for all episodes. The subset of data used can be found in the [data/simpsons](data/simpsons) folder.

This project is using Python 3 and needs the following libraries:

* numpy
* tensorflow
* matplotlib
* jupyter notebook

These can be installed using pip or conda if using [Anaconda](https://www.continuum.io/downloads).

The project is implemented in a Jupyter notebook and can be run using the following from a terminal:

```jupyter notebook dlnd_tv_script_generation.ipynb```

If interested in training your model on a GPU for better performance, checkout [FloydHub](http://www.floydhub.com).
