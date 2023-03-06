# AKPIK Datathon

Welcome to our Datathon! We provide you with a [Jupyter](https://jupyter.org/) notebook  [`participants-notebook.ipynb`](https://github.com/mirkobunse/akpik-datathon23/blob/main/participants-notebook.ipynb), which contains everything you need to get started. You can use this notebook in two ways:

1. via [Google Colab](https://colab.research.google.com/drive/1cBCzYzAWFCFO9HsuvZMRkzjuBZutsysy?usp=sharing). In this free, hosted service, you do not need any local software - any standard web browser suffices. However, you need a Google account to use this service.
2. locally, via [Docker](https://docs.docker.com/). In this setup, you do not need a Google account, but you have to have a running Docker installation on your Laptop. To start a Docker container with a Jupyter server, run

```
docker run -it -p 8888:8888 --volume=$PWD:/tf tensorflow/tensorflow:2.9.3-jupyter
```

in your terminal and open the displayed link in your local browser.
