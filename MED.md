#  最小熵反褶积(MED)
## 1. 基本原理
 最小熵反褶积的出发点即寻找最优的滤波器使的原信号的峭度值最大，最大程度的还原原信号的特性，使冲击成分突出，降噪后的信号最大程度与满足原信号的物理特性。因此最小熵反褶积可以提高原信号的信噪比[5]。
最小熵反褶积(Minimum entropy deconvolution MED)首先由Wiggins[6]提出，是一种自适应的信号处理方法。2007年Sawalhi[6]将MED方法应用于滚动轴承与齿轮故障诊断中，MED算法的目的就是以最大峭度为迭代的终止条件提高信号的信噪比[7]。滚动轴承故障时信号表达可以表达为:   
![](https://github.com/hustcxl/Signal-processing-notes/blob/master/img/mathtex.gif)

## Algotithm 
* [Multipoint Optimal Minimum Entropy Deconvolution with Convolution Adjustment (MOMEDA)](https://ww2.mathworks.cn/matlabcentral/fileexchange/53483-multipoint-optimal-minimum-entropy-deconvolution-with-convolution-adjustment-momeda)
* [Minimum Entropy Deconvolution Multipack (MED, MEDA, OMEDA, MOMEDA, MCKD)](https://ww2.mathworks.cn/matlabcentral/fileexchange/53484-minimum-entropy-deconvolution-multipack-med-meda-omeda-momeda-mckd?s_tid=FX_rc1_behav)

## Papers

- [1] R.A. Wiggins, Minimum entropy deconvolution, Geoexploration 16 (1--2)(1978) 21--35.

- [2] Cabrelli, Carlos A. "Minimum entropy deconvolution and simplicity: A noniterative algorithm." Geophysics 50.3 (1985): 394-413.

- [3] McDonald, Geoff L., Qing Zhao, and Ming J. Zuo. "Maximum correlated Kurtosis deconvolution and application on gear tooth chip fault detection." Mechanical Systems and Signal Processing 33 (2012). For PDF see [blog](http://split-code.com/rotation.html.)

- [4] McDonald, Geoff L., and Qing Zhao. "Multipoint Optimal Minimum Entropy Deconvolution and Convolution Fix: Application to vibration fault detection." Mechanical Systems and Signal Processing 82 (2017): 461-477. For PDF see [blog](http://split-code.com/rotation.html.)
   
[:back:返回主目录](README.me)
