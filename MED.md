#  最小熵反褶积(MED)
## 1. 基本原理
最小熵反褶积的出发点即寻找最优的滤波器使的原信号的峭度值最大，最大程度的还原原信号的特性，使冲击成分突出，降噪后的信号最大程度与满足原信号的物理特性。因此最小熵反褶积可以提高原信号的信噪比[5]。
最小熵反褶积(Minimum entropy deconvolution MED)首先由Wiggins[6]提出，是一种自适应的信号处理方法。2007年Sawalhi[6]将MED方法应用于滚动轴承与齿轮故障诊断中，MED算法的目的就是以最大峭度为迭代的终止条件提高信号的信噪比[7]。滚动轴承故障时信号表达可以表达为
![](http://www.forkosh.com/cgi-bin/mathtex.cgi?formdata=W%7BT_f%7D%5Cleft%28+%7Bj%2Ck%7D+%5Cright%29+%3D+%5Cint+%7Bf%5Cleft%28+t+%5Cright%29%5Cpsi+_%7Bj%2Ck%7D%5E+*+%7D+%5Cleft%28+t+%5Cright%29)
