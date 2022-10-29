# WiFi_TALNET
This net uses transformer/RNN as the backbone to extract the features in WiFi data(or Time Series data style)..

8500*30的数据，8500算作时间？30算作feature维度。&nbsp adaRNN过一遍提取特征 T*C特征金字塔（是几组数据特征组成的还是一个数据多次提取构成的？）——> 得到特征  用anchor free的方式，分出两个简单的branch网络。
