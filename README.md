# M1：[输入控制](https://github.com/OS-Q/M1) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

嵌入控制节点，运行中不接收控制指令，根据情况可反馈状态信息

#### 归属设备体系：[Q1](https://github.com/OS-Q/Q1)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)


## [节点描述](https://github.com/OS-Q/M1/wiki) 

M1输入控制节点，用于物理数据的转换输入，完成系统最前沿的数据采集过程

### [共用资源](https://github.com/OS-Q/M1/wiki) 

#### [协同输出接口](M2/)

M1节点和M2节点协同规范

#### [集成控制接口](M3/)

M1节点和M3节点协同规范

#### [协同通信接口](M4/)

M1节点和M4节点协同规范

---

- 边缘设备统一命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

## [包含平台](https://github.com/OS-Q/M1/wiki) 

#### W1：[逻辑转换](https://github.com/OS-Q/W1)

用于完成电气逻辑转换和控制实现

#### W2：[状态监控](https://github.com/OS-Q/W2)

用于完成简单的闭环的感知和处理

#### W3：[计量感知](https://github.com/OS-Q/W3)

用于转换物理信号并统计数据呈现

#### W4：[电源管理](https://github.com/OS-Q/W4)

用于按指定逻辑控制电源模式状态

## [同级节点](https://github.com/OS-Q/Q1/wiki/)

#### -> M1：[输入控制](https://github.com/OS-Q/M1)

控制外接信号输入，完成数据采集过程

#### M2：[输出控制](https://github.com/OS-Q/M2)

控制对外信号输出，完成数据消费过程

#### M3：[集成控制](https://github.com/OS-Q/M3)

集成相关资源，组合完成预定控制逻辑

---

####  qitas@qitas.cn
###  [Q redefined the scope of Operation System](http://www.OS-Q.com)
####  2018-12-7
