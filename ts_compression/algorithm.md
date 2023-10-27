# Time Series Compression Algorithm
|Paper|Conference|Lossless|Remarks
|--|--|--|--|
|[Time Series Compression Survey](https://dl.acm.org/doi/full/10.1145/3560814)|ACM Computing Surveys 2022.09.21|-|时序数据压缩调查|
|[Robust IoT time series classification with data compression and deeplearning](https://sci-hub.se/10.1016/j.neucom.2020.02.097)|Neurocomputing Jul 2020|×| 提出了一种有效的单变量与多变量时序数据压缩办法，将改进离散小波变换（DWT）结合错误有限有损压缩算法（SZ）来达到数据压缩率与数据质量的最佳权衡|
|[Sprintz: Time Series Compression for the Internet of Things](https://www.sci-hub.se/10.1145/3264903)|Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies（Ubicomp）|✔|提出了一种用于整数时间序列无损压缩的算法Springz,只需要缓存8个样本的同时，只占用<1KB的内存，达到单线程3GB/s的解压速度，以及高压缩比|
|[An Evolving TinyML Compression Algorithm for IoT Environments Based on Data Eccentricity](https://sci-hub.se/10.3390/s21124153)|Sensors 2021|×|主要提出了小型机器学习在时序数据压缩方面应用的潜力，以及一种基于数据偏心率的有损压缩算法|
|[Two-Level Data Compression using Machine Learning in Time Series Database](https://sci-hub.se/10.1109/icde48307.2020.00119)|2020 IEEE 36th International Conference on Data Engineering (ICDE)|-|提出了二级压缩框架，由一级框架确定数据典型适用的压缩方案，二级使用强化学习来自动调整控制参数|
|[A time-series compression technique and its application to the smart grid](https://www.sci-hub.se/10.1007/s00778-014-0368-8)|The VLDB Journal|×|提出了一种贪心分段回归的有损时序数据压缩方法|
|[Titchy: Online Time-series Compression with Random Access for the Internet of Things](https://sci-hub.se/10.1109/jiot.2021.3081868)|IEEE Internet of Things Journal 2021|✔|提出了一种无损的压缩方案，使用设定好的误差将数据近似到相同的基底上，记录公共基底字典和误差，去除数据冗余以达到压缩的目的,可以支持快速随机查询|
|[Chimp: Efficient Lossless Floating Point Compression for Time Series Databases](https://www.vldb.org/pvldb/vol15/p3058-liakos.pdf)|PVLDB 2022|✔|提出了一种无损的浮点数流压缩方案，基于异或编码和前导0在数据集上的分布实现对类似于Gorilla算法的优化，同时提供CHIMP128的算法以相比较慢的速度换取显著提升的压缩率|
|[Model-Free Lossless Data Compression for Real-Time Low-Latency Transmission in Smart Grids](https://sci-hub.se/10.1109/tsg.2020.3040370)|IEEE Transactions on Smart Grid 2021/05/01|✔|提出了一种无状态无模型的智能电网数据无损压缩方案，特别适用于长时间稳定的高分辨率时间序列|
|[A Randomly Accessible Lossless Compression Scheme for Time-Series Data](https://sci-hub.se/10.1109/infocom41043.2020.9155450)|IEEE INFOCOM 2020|✔|提出了一种支持不解压缩，允许随机访问的无损时序数据压缩方案|
|[Lossless Data Compression for Time-Series Sensor Data Based on Dynamic Bit Packing](https://www.mdpi.com/1424-8220/23/20/8575)|Sensors 2023|✔|提出了对于Springz框架的一种优化方案，即动态位压缩|
[Back to index](../README.md)