# M4：[桥接管道](https://github.com/OS-Q/M4) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属通信体系：[Q2](https://github.com/OS-Q/Q2)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M4/wiki) 

M4桥接管道节点，作为通信桥梁连接上下两端设备，不作为主动控制单元

### [共用资源](OS-Q/)

#### [网关互联](M6/)

M4节点和M6节点对接规范和资源

- 数据封装协议

- 物理信道规范


---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https://github.com/OS-Q/M4/wiki) 

#### W14：[通道转换](https://github.com/OS-Q/W14)

物理通信通道或通信协议的改变

#### W15：[通道扩展](https://github.com/OS-Q/W15)

通信通道数量和适配的种类扩充

#### W16：[通信中继](https://github.com/OS-Q/W16)

通信信号在传输过程中进行补强

#### W17：[专用模块](https://github.com/OS-Q/W17)

用于适配他人设备专用桥接模块

## [同级节点](https://github.com/OS-Q/Q2/wiki)

#### -> M4：[桥接管道](https://github.com/OS-Q/M4)

作为上下层级设备控制的通信管道

#### M5：[无线终端](https://github.com/OS-Q/M5)

集成无线通信和边缘控制终端设备

#### M6：[数据网关](https://github.com/OS-Q/M6)

数据中转节点，数据的汇集和处理

---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  @ 2018-12-25