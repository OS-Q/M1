# M1：[信号采集](https://github.com/OS-Q/M1) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属控制体系：[Q1](https://github.com/OS-Q/Q1)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M1/wiki) 

M1信号采集节点，用于物理转换转换输入，完成系统最前沿的数据采集过程

### [共用资源](https://github.com/OS-Q/M1/wiki) 

#### [协同输出](M2/)

M1节点和M2节点协同完成信号的反馈采集

#### [协同控制](M3/)

M1节点和M3节点协同扩展闭环控制能力

#### [协同通信](M4/)

M1节点和M4节点协同完成数据向上传递

---

- 边缘设备统一命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

## [包含平台](https://github.com/OS-Q/M1/wiki) 

#### W1：[电气信号](https://github.com/OS-Q/W1)

用于电气信号的采集转换

#### W2：[常态转化](https://github.com/OS-Q/W2)

用于处理转化常态信号量

#### W3：[阈值监控](https://github.com/OS-Q/W3)

用于监控阈值状态发生

#### W4：[特殊平台](https://github.com/OS-Q/W4)

用于处理特殊需求情况

## [同级节点](https://github.com/OS-Q/Q1/wiki/)

#### -> M1：[信号采集](https://github.com/OS-Q/M1)

控制外接信号输入，完成数据采集过程

#### M2：[数据驱动](https://github.com/OS-Q/M2)

控制对外信号输出，完成数据消费过程

#### M3：[闭环控制](https://github.com/OS-Q/M3)

集成相关资源，组合完成预定闭环控制

---
####  qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  © 2018-12-11

---
