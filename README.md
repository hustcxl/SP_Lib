# 信号处理算法库
 
 本项目旨在追踪建立最先进的信号处理算法库。从算法理论原理，实现方法，到落地demo。
 目前是个人业余收集和整理，知识和精力都有限，欢迎有识之士参与贡献。
 欢迎大家任意Fork,Star,Watch.
 demo一般来自网络共享开源的资源。或者自己根据论文原理实现。欢迎批评指正。
 如涉及侵权，请随时联系删除。
 声明：本算法库仅作学习交流之用。如未经许可用作其他商业用途，保留追责权利。

## 1.传统方法
### 时域
时域特征计算相对简单，MATLAB都有非常多的库函数。也有人已经进行了总结。直接引用。源自知乎专栏。  
* [时域特征值提取的MATLAB代码实现（均方根、峰值因子、脉冲因子、裕度因子、峭度因子、波形因子和偏度等）](https://zhuanlan.zhihu.com/p/36162561)  
* [信号时域分析方法的理解（峰值因子、脉冲因子、裕度因子、峭度因子、波形因子和偏度等）](https://zhuanlan.zhihu.com/p/35362151)  
* [时域分析——无量纲特征值含义一网打尽](https://zhuanlan.zhihu.com/p/57445453)    
* [时域分析——有量纲特征值含义一网打尽](https://zhuanlan.zhihu.com/p/57153601)  
* [python实现信号时域统计特征提取](https://blog.csdn.net/qq_34705900/article/details/88389319)  

### 频域
* [信号频域分析方法的理解（频谱、能量谱、功率谱、倒频谱、小波分析）](https://zhuanlan.zhihu.com/p/34989414)
* [频域特征值提取的MATLAB代码实现（频谱、功率谱、倒频谱）](https://zhuanlan.zhihu.com/p/36163931)
* fft专题

### 滤波
* 无限长单位脉冲响应（Infinite impulse response,IIR）滤波器
  [Infinite impulse response](https://en.wikipedia.org/wiki/Infinite_impulse_response)  
  * [巴特沃思低通滤波器](https://blog.csdn.net/Stynis/article/details/80531803)  
    [matlab buttord 函数](https://ww2.mathworks.cn/help/signal/ref/buttord.html?searchHighlight=buttord&s_tid=doc_srchtitle)  
  * [MATLAB|切比雪夫低通滤波器设计与滤波实现](https://www.jianshu.com/p/2a0d6d587bc3)  
    [matlab cheb1ord 函数](https://ww2.mathworks.cn/help/signal/ref/cheb1ord.html?s_tid=doc_ta) 
  
* 有限长单位脉冲响应（Finite impulse response,FIR）滤波器
  * [Finite impulse response](https://en.wikipedia.org/wiki/Finite_impulse_response)  
  


### 其他


## 2.信号自适应分解

* EMD
* EEMD
* VMD


## 3.时频分析方法

* STFT
* SST
* EWT


1. [最小熵反褶积](https://github.com/hustcxl/Signal-processing-notes/blob/master/MED.md)
