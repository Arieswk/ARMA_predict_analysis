# 利用ARMA进行时间序列分析
* [根据历史数据(2012-01-01_to_2018-10-31)](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/bitcoin_2012-01-01_to_2018-10-31.csv),[比特币走势预测(2018-11-30_to_2019-6-30)](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/bitcoin_analysis.py)  
* [根据历史数据(1990-12-19_to_2019-02-28)](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/shanghai_1990-12-19_to_2019-2-28.csv),[上海沪市指数走势预测(2019-3-31_to_2019-12-31)](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/shanghai_analysis.py)   
# AR、MA、ARMA和ARIMA模型区别  
* AR （Auto Regressive），中文叫自回归模型，它认为过去若干时刻的点通过线性组合，再加上白噪声就可以预测未来某个时刻的点。AR 模型还存在一个阶数，称为 AR（p）模型，也叫作 p 阶自回归模型。它指的是通过这个时刻点的前 p 个点，通过线性组合再加上白噪声来预测当前时刻点的值。  
* MA （ Moving Average），中文叫做滑动平均模型。MA 模型存在一个阶数，称为 MA(q) 模型，也叫作 q 阶移动平均模型。MA 模型是通过将一段时间序列中白噪声序列进行加权和。  
* ARMA （ Auto Regressive Moving Average），中文叫做自回归滑动平均模型， ARMA 模型存在 p 和 q 两个阶数，称为 ARMA(p,q) 模型。  
* ARIMA（ Auto Regressive Integrated Moving Average ），中文叫差分自回归滑动平均模型，也叫求合自回归滑动平均模型。相比于 ARMA，ARIMA 多了一个差分的过程，作用是对不平稳数据进行差分平稳，在差分平稳后再进行建模。ARIMA 是一个三元组的阶数 (p,d,q)，称为 ARIMA(p,d,q) 模型。其中 d 是差分阶数。  
# 上海沪市指数走势预测结果及可视化
* 沪市指数
![沪市指数](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/%E7%BB%93%E6%9E%9C%E5%8F%AF%E8%A7%86%E5%8C%96/%E6%B2%AA%E5%B8%82%E6%8C%87%E6%95%B0.jpg)
* 最优模型  
![最优模型](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/%E7%BB%93%E6%9E%9C%E5%8F%AF%E8%A7%86%E5%8C%96/%5BNRH%7BSE(~R%5DPPX%7D%7DD)WFU0L.png)  
* 沪市指数预测(月)
![沪市指数预测(月)](https://github.com/Arieswk/ARMA_predict_analysis/blob/master/%E7%BB%93%E6%9E%9C%E5%8F%AF%E8%A7%86%E5%8C%96/%E6%B2%AA%E5%B8%82%E6%8C%87%E6%95%B0%E9%A2%84%E6%B5%8B(%E6%9C%88).jpg)
