# SC8P1762_toothbrush_SDK
> 作者: Dog_Egg  
> 说明: record the development process of a toothbrush production use the sc8p1762 as MCU
------
## Contents 
- [产品功能要求](#产品功能要求)
- [设计参考资料](#设计参考资料)
  - [开发环境安装](#开发环境安装)
  - [芯片介绍](#芯片介绍)
  - [示例工程](#示例工程)
  - [开发指南](#开发指南)

### 产品功能要求
序号|功能|描述
--|:--|:--|
1|开机    |单机模式键开始工作,默认上次关机模式,对应指示灯亮
2|关机    |1)所有模式切换1次后,再次单击模式键关机<br>2)模式选择锁定后(开机5s后),再次单机模式键关机<br>3)工作2分钟后关机
3|模式选择|开机5秒内,单击切换模式对应的指示灯常亮
4|换位提示|工作过程每隔30s停0.5s,直到停止工作
5|旅行模式|关机状态长按5s锁键,所有指示灯闪3次(间隔0.5s),单击无效指示灯闪1次,长按5s解锁,闪3次


### 设计参考资料

#### 开发环境安装

#### 芯片介绍

#### 示例工程

#### 开发指南
