## 1. 说明：

- 基于Verilog的数字时钟设计，仿真版本。

## 2. 平台：

- Quartus 17.1
- Modelsim仿真

## 3. 功能实现：

- 数字时钟，具有时、分、秒显示；
- 具有时间校准及闹钟功能；
- 采用数码管显示时钟值（仿真中看不出数码管显示效果）。

## 4. 补充说明：

- 模块说明：
	```
	TOP.v		顶层文件
	time_control.v	数字钟实现模块
	display_ctrl.v	数码管驱动模块
	tb_TOP.v	测试文件
	```

- RTL结构图：

	![RTL图](https://user-images.githubusercontent.com/29295862/40353222-88119fd2-5de3-11e8-8386-eee87dd0fbd3.png)

- 仿真图：

	![仿真图](https://user-images.githubusercontent.com/29295862/40353569-62f78832-5de4-11e8-9dfd-8950000d44f2.png)
	![仿真图](https://user-images.githubusercontent.com/29295862/40353572-64ea39f0-5de4-11e8-8658-1fc40eef2632.png)
	![仿真图](https://user-images.githubusercontent.com/29295862/40353576-66da9d40-5de4-11e8-8de2-431d39147bda.png)