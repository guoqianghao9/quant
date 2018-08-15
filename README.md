# quant
#python version == 3.6
#tensorflow version == 1.9.0
#本项目根据CDNS上LSTM股票预测进行交易思路上的改进
#本文更偏重于交易思路

#导入所需要的包
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import talib as ta
import datetime,pickle
import tensorflow as tf
from sklearn.preprocessing import minmax_scale

#读取数据


