# M1：[信号采集](https://github.com/OS-Q/M1) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属控制体系：[Q1](https://github.com/OS-Q/Q1)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M1/wiki) 

M1信号采集节点，用于完成系统最前沿的数据采集过程

### [共用资源](OS-Q/) 

#### [协同输出](M2/)

M1节点和M2节点协同完成信号的反馈采集

#### [协同控制](M3/)

M1节点和M3节点协同扩展闭环控制能力

#### [协同通信](M4/)

M1节点和M4节点协同完成数据向上传递

---


- 边缘设备命名规则：体系 Q：[1,4] -> 节点 M：[1,12] -> 平台 W：[1,52] -> 设备 D：[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https://github.com/OS-Q/M1/wiki) 

#### W1：[模拟信号](https://github.com/OS-Q/W1)

用于模拟信号的采集转换

#### W2：[环境监控](https://github.com/OS-Q/W2)

用于监控设备的外部环境

#### W3：[状态监控](https://github.com/OS-Q/W3)

用于监控设备自身的状态

#### W4：[特殊信号](https://github.com/OS-Q/W4)

用于处理特殊信号的采集

## [同级节点](https://github.com/OS-Q/Q1/wiki/)

#### -> M1：[信号采集](https://github.com/OS-Q/M1)

控制外接信号输入，完成数据采集过程

#### M2：[数据驱动](https://github.com/OS-Q/M2)

控制对外信号输出，完成数据消费过程

#### M3：[闭环控制](https://github.com/OS-Q/M3)

集成相关资源，组合完成预定闭环控制

---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  @ 2019-1-3

