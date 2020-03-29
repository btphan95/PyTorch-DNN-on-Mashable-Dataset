# Testing a PyTorch DNN Model on the Mashable Online News Popularity Dataset
This notebook is a quick and gentle introduction to training a Deep Neural Network on the Mashable Online News Popularity Dataset in PyTorch. The DNN architecture used is as follows:
```
#                           linear1,nn.BatchNorm1d(hiddenLayer1Size),relu,
#                           linear2,dropout,relu,
#                           linear3,dropout,relu,
#                           linear4,dropout,relu,
#                           linear5,dropout,relu,
#                           linear6,dropout,relu,
#                           sigmoid
```
