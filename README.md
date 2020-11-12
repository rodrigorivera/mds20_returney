# RETURNEY: Semi-supervised Prediction of the Return Time of a User
Project of "Models of Sequence Data" course, Skoltech, 2020

## Problem statement
The problem is to develop a model that learns to predict users' return times from browsing histories of many other users. Some users do not come back, hence, our model needs to be able to both learn from such users' data and predict that some users will not come back during some specified prediction window.


## Structure
- `RMTPP` - folder with our implementation of vanilla Du et al. paper
- `RNNSM` - folder with our implementation of vanilla Grob et al. paper
- `semi-supervised` - folder with our experiments on semi-supervised approaches to the problem
- `data` - folder with relevant datasets
- `references` - folder with relevant existing implementations and their descriptions


## References
The project is based on the following papers:

- [A Recurrent Neural Network Survival Model: Predicting Web User Return Time](https://arxiv.org/abs/1807.04098)<br>
Georg L. Grob, Ângelo Cardoso, C. H. Bryan Liu, Duncan A. Little, Benjamin Paul Chamberlain, 2018

- [Recurrent Marked Temporal Point Processes:Embedding Event History to Vector](https://www.kdd.org/kdd2016/papers/files/rpp1081-duA.pdf)<br>
Nan Du, Hanjun Dai, R. Trivedi, U. Upadhyay, M. Gomez-Rodriguez, Le Song, 2016
