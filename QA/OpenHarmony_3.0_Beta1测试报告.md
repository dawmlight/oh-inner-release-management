

修订记录

 

| 日期 | 修订版本 | 修改章节 | 修改描述 |
| ---- | -------- | -------- | -------- |
|      |          |          |          |

缩略语清单： 

| 缩略语 | 英文全名 | 中文解释 |
| ------ | -------- | -------- |
|        |          |          |
|        |          |          |
|        |          |          |
|        |          |          |

# 

# 1   概述

描述本次被测对象变更内容。

# 2   测试版本说明

描述测试版本信息。

| 版本名称              | 测试起始时间 | 测试结束时间 |
| --------------------- | ------------ | ------------ |
| OpenHarmony 3.0 Beta1 | 2021/8/19    | 2021/8/24    |

描述本次测试的测试环境（包括环境软硬件版本信息，环境组网配置信息, 测试辅助工具等）。

| 硬件型号        | 硬件配置信息 | 备注                                              |
| --------------- | ------------ | ------------------------------------------------- |
| hispark_pegasus | Hi3861开发板 | docs/zh-cn/device-dev/quick-start/Hi3861开发板.md |
| hispark_aries   | Hi3518开发板 | docs/zh-cn/device-dev/quick-start/Hi3518开发板.md |
| hispark_taurus  | Hi3516开发板 | docs/zh-cn/device-dev/quick-start/Hi3516开发板.md |

 

# 3   版本概要测试结论

*本章节概要给出版本测试结论*

# 4   版本详细测试结论

*本章节针对总体测试策略计划的测试内容，给出详细的测试结论。*

## 4.1   特性测试结论



### 4.1.1   继承特性评价

*继承特性进行评价，用表格形式评价，包括特性列表，验证质量评估。*

XXX子系统：特性质量良好

| 序号 | 特性名称    | 特性质量评估                             | 备注 |
| ---- | ----------- | ---------------------------------------- | ---- |
| 1  | 驱动子系统 | 没有新增特性，camera驱动功能不可用（预览白屏、xts失败），其他audio、usb等基本功能可用 |  安全扫描和用例失败问题参考issue    |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*
分布式任务调度子系统：特性质量良好

| 序号 | 特性名称    | 特性质量评估                             | 备注 |
| ---- | ----------- | ---------------------------------------- | ---- |
| 1  | 分布式任务调度子系统 | 没有新增特性，轻设备拉起富设备FA，轻拉富免安装等基本功能可用 |  安全扫描和用例失败问题参考issue    |
| 2  | 内核子系统 | 没有新增特性，基本功能可用 |  |
| 3  | 电源子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| 4  | DFX子系统 | 新增faultlogger功能，覆盖对应的功能、稳定性压测，性能和安全不涉及，功能正常，无异常，其余功能覆盖自动化测试 |      |
| 5  | 多媒体子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| 6  | 数据管理子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| 7  | 启动恢复子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

### 4.1.2   新需求评价

*以表格的形式汇总新特性测试执行情况及遗留问题情况的评估,给出特性质量评估结论。*

| lssue号 | 特性名称 | 特性质量评估 | 约束依赖说明 | 备注 |
| ------- | -------- | ------------ | ------------ | ---- |
|         |          |              |              |      |
|         |          |              |              |      |
|         |          |              |              |      |
|         |          |              |              |      |
|         |          |              |              |      |
|         |          |              |              |      |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

## 4.2   兼容性测试结论

*补充兼容性测试报告*

## 4.3   安全专项测试结论
专项测试评估结论：不通过
1、本版本共有8个子系统有新增需求，均已完成测试，当前还有9个安全issue没有关闭。
2、编码问题较为突出，静态告警和危险函数均未清零。

遗留问题列表如下：
| 标题 | 问题类型 | 归属子系统 | 状态属性 | URL |
| ---- | -------- | ---------- | -------- | --- |
|Softbus_server在执行socketfuzz时，出现crash	|安全|	软总线|开启的|	https://gitee.com/openharmony/communication_dsoftbus/issues/I480Z1?from=project-issue|
|【openHarmony】【3.0 Beta1】【轻内核子系统】集成测试 在执行ActsIpcShmTest.bin脚本，出现大量未释放的共享内存。|	安全	|内核子系统	|开启的|	https://gitee.com/openharmony/kernel_liteos_a/issues/I47X2Z?from=project-issue|
|【3.0 beta1】【软总线-传输】session id范围校验不严谨（有效范围1-16，校验时判断的是>17）	|安全	|软总线	|开启的	|https://gitee.com/openharmony/communication_dsoftbus/issues/I47WTY?from=project-issue|
|【OpenHarmony 3.0 Beta1】权限校验没有生效，使用测试 bin 直接调用无权限 hap，期望查询失败返回 0，结果查询成功	|安全|	用户程序框架子系统	|进行中	|https://gitee.com/openharmony/appexecfwk_appexecfwk_lite/issues/I47ETO?from=project-issue|
|【OpenHarmony 3.0 Beta1】【驱动子系统】不安全函数和安全编译选项	|安全|	驱动子系统	|待办的	|https://gitee.com/openharmony/drivers_peripheral/issues/I47DE6?from=project-issue|
|【OpenHarmony 3.0 Beta1】安全SecBinaryCheck扫描：libappexecfwk_base.z.so与libeventhandler_native.z.so存在stack-protector疑似告警，需要解决	|安全	|用户程序框架子系统|	进行中	|https://gitee.com/openharmony/appexecfwk_standard/issues/I479YY?from=project-issue|
|BUG-[轻鸿蒙多媒体子系统][相机] [音频][视频]代码安全编码规范	|安全	|多媒体子系统|	进行中	|https://gitee.com/openharmony/multimedia_media_lite/issues/I46I6K?from=project-issue|
|L0 内核模块编译添加-Werror编译选项	|安全|	内核子系统	|修复中	|https://gitee.com/openharmony/kernel_liteos_m/issues/I46E6S?from=project-issue|
|【2.2 Beta2】【软总线】断本端网络，组网未成功（无法获取node），但是却成功opensession发送数据|	安全	|软总线|	修复中	|https://gitee.com/openharmony/communication_dsoftbus/issues/I439J1?from=project-issue|

## 4.4   稳定性专项测试结论

a）执行反复开关机压力测试，运行5000次，无不开机问题；

a）执行单模块应用界面随机压力测试，无卡死、Crash问题； 当前由于无界面随机压测工具，该测试项暂时无法评估

b）执行整机应用界面随机压力测试，无卡死、Crash问题； 当前由于无界面随机压测工具，该测试项暂时无法评估

c）执行反复开关机压力测试，运行50000次，无不开机问题； 当前版本未覆盖反复开关机压力测试

d）执行整机XTS MTBF压力测试，无卡死、Crash问题； 当前版本未覆盖XTS MTBF压力测试

## 4.5   性能专项测试结论

*以表格形式汇总各专项测试执行情况及遗留问题情况的评估，给出专项质量评估结论*

*要求：1、静态KPI通过率100%，2、开关机及动态内存整机达标，子系统无严重问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
|          |            |          |          |                             |           |
|          |            |          |          |                             |           |

## 4.6   功耗专项测试结论

*以表格形式汇总各专项测试执行情况及遗留问题情况的评估，给出专项质量评估结论*

*要求：无严重问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
|          |            |          |          |                             |           |
|          |            |          |          |                             |           |

# 5   问题单统计

https://gitee.com/openharmony/drivers_peripheral/issues/I43339 【OpenHarmony 2.2 Beta2】【驱动子系统】L2单板camera DFx测试用例失败
https://gitee.com/openharmony/drivers_peripheral/issues/I47DE6 【OpenHarmony 3.0 Beta1】【驱动子系统】不安全函数和安全编译选项
https://gitee.com/openharmony/drivers_peripheral/issues/I46HH7 【OpenHarmony 3.0.0.3】【驱动子系统】L2单板wifi测试用例失败

[【openHarmony】【3.0 Beta1】【轻内核子系统】集成测试 在执行ActsIpcShmTest.bin脚本，出现大量未释放的共享内存](https://gitee.com/openharmony/kernel_liteos_a/issues/I47X2Z)

[【WIP】【OpenHarmony】【3.0.0.2】【轻内核子系统】集成测试toybox需提供用户手册，手册中需要将各命令的限制详细说明，以便更好的指导... ](https://gitee.com/openharmony/third_party_toybox/issues/I44YLY)

[【openHarmony】【轻内核子系统】集成测试开发板移植指导中需增加线程不足的确认方法和配置线程个数的方法 ](https://gitee.com/openharmony/kernel_liteos_m/issues/I42LCU)

[【OpenHarmony】【20210414】【轻内核子系统】集成测试不支持功能需要在.h中说明](https://gitee.com/openharmony/kernel_liteos_m/issues/I3IPD7)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试直接执行cat后无法退出，需要重启设备恢复](https://gitee.com/openharmony/third_party_mksh/issues/I42N33)

[【OpenHarmony】【20210419】【轻内核子系统】集成测试发送两个不同的信号，sigwait第二次等到的仍是第一个信号](https://gitee.com/openharmony/kernel_liteos_a/issues/I3M12H)

