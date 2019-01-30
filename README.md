# 代码总览

代码总共分为三部分。第一部分是用于数据分析以及词袋模型建立的,名称为Data Analysis and n gram models.ipynb。第二部分是用于深度学习模型的，名称叫做：Deep learning models.ipynb。第三部分适用于模型融合的，名称叫做Data Analysis and n gram models.ipynb。请确保第一部分和第二部分代码运行完毕之后再运行第三部分

## 第一部分和第三部分
第一部分代码和第三部分代码都是在本地运行完成的，使用的库包括Keras, matplotlib, numpy, pandas, sklean, scipy. 我的本地设备配置为：Processor: Intel(R) Core(TM) i7-8550U CPU @ 1.80 GHZ 1.99GHz; RAM: 16.0GB；无GPU

## 第二部分
第二部分代码实在Google Datalab上运行完成的。Compute Engine的配置为：CPU platform: Intel Sandy Bridge; Machine type: n1-highmem-8 (8 vCPUs, 52 GB memory) GPU: NVIDIA Tesla V100, GPU数量：1.用到的库包括：Keras, matplotlib, numpy, pandas, sklean, scipy，google，io，gensim，random，warnings， gc， time

## 输出文件
最终模型的输出文件为"my_sub.csv", 两个深度学习模型的预测输出为”J_sub.csv“（GRU）和“D_sub.csv”(LSTM + GRU). 词袋模型的输出为"LR_submission.csv"
