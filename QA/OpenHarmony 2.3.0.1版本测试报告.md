

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

| 版本名称 | 测试起始时间 | 测试结束时间 |
| -------- | ------------ | ------------ |
|          |              |              |

描述本次测试的测试环境（包括环境软硬件版本信息，环境组网配置信息, 测试辅助工具等）。

| 硬件型号 | 硬件配置信息 | 备注 |
| -------- | ------------ | ---- |
|          |              |      |
|          |              |      |
|          |              |      |

 

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
| *1*  | *启动恢复子系统* | *没有新增特性，测试用例执行通过，基本功能可用* |      |
| 2 | 轻内核子系统 | 1、L0上支持POSIX接口和littlefs文件系统特性无法测试，不对这些特性进行评估<br />2、L1上shell相关特性和文件系统维测增强特性没有合入2.3.0.1版本，特性不可用<br />3、其余特性质量良好，遗留少量问题 | |
| 3 | 驱动子系统 | L1基本功能良好，L0支持HDF框架无法测试，不对该特性进行评估 | |
| 4 | 泛sensor服务子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| 5 | 安全子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

### 4.1.2   新需求评价

*以表格的形式汇总新特性测试执行情况及遗留问题情况的评估,给出特性质量评估结论。*

| lssue号 | 特性名称 | 特性质量评估 | 约束依赖说明 | 备注 |
| ------- | -------- | ------------ | ------------ | ---- |
| I3I1V8  | 【全球化子系统】构建应用资源解析和加载机制    | 特性质量良好     | 不涉及             |      |
| I3I1VJ  | 【全球化子系统】构建资源回溯机制             | 特性质量良好     | 不涉及             |      |
| [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统 | 无法测试 |              | wifiiot_hispark_pegasus上不支持，无法测试 |
| [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】L0上对外提供统一的文件系统操作接口 | 无法测试 |              | wifiiot_hispark_pegasus上不支持，无法测试 |
| [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】L0 补充120个POSIX接口 | 无法测试 |              | wifiiot_hispark_pegasus上不支持，无法测试 |
| [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器 | 特性不可用 |              | 特性在2.3.0.1版本没有合入 |
| [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升 | 特性不可用 | | 特性在2.3.0.1版本没有合入 |
| [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集 | 特性不可用 | | 特性在2.3.0.1版本没有合入 |
| [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块 | 特性质量良好 | | |
| [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理 | 特性质量良好 | | |
| [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块 | 特性质量良好 | | |
| [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强 | 特性不可用 | | 特性在2.3.0.1版本没有合入 |
| [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置 | 特性质量良好 | | |
| [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配 | 特性质量良好 | | |
| [ I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】L0支持三方组件Mbedtls编译 | 遗留少量问题 | | |
| [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】L0支持三方组件curl编译 | 遗留少量问题 | | |
| [ I3QE85](https://gitee.com/openharmony/drivers_framework/issues/I3QE85) | 【驱动子系统】L0支持HDF框架 | 无法测试 | | wifiiot_hispark_pegasus上不支持，无法测试 |
| | | | | |
| | | | | |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

## 4.2   兼容性测试结论

*补充兼容性测试报告*

## 4.3   安全专项测试结论

*要求：无严重的隐私安全问题遗留，版本通过漏洞扫描，未解决的漏洞满足以下要求：*

*a）无严重及以上公开漏洞；*

*b）无已公开60天但未修复的一般（CVSS得分4及以上）安全漏洞；*

*c）不存在已知CVE安全漏洞，业界未解决的已知CVE安全漏洞可例外；*

*d）无法修复，且经过社区开发团队综合评估备案允许遗留的漏洞；*

## 4.4   稳定性专项测试结论

*a）执行反复开关机压力测试，运行5000次，无不开机问题；*

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
|          |            |          |          |                             |           |
|          |            |          |          |                             |           |

## 4.5   性能专项测试结论

*以表格形式汇总各专项测试执行情况及遗留问题情况的评估，给出专项质量评估结论*

*要求：1、静态KPI通过率100%，2、开关机及动态内存整机达标，子系统无严重问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ------------- | -------------- | -------- | --------------------------- | --------- |
| 基础性能  |轻量系统静态模型|静态KPI通过率100%| 满足     | 轻量系统无感配网满足版本质量   |           |
| 基础性能  |小型系统静态模型|静态KPI通过率100%| 不满足   | 小型系统图库、相机、设置、查看图片、拍照均满足测试要求。录像模块存在异常  |https://gitee.com/openharmony/multimedia_camera_lite/issues/I3YD64?from=project-issue|
| 基础性能  |轻量系统内存专项|开机以及动态内存整机达标，子系统无严重问题| 满足     | 轻量系统开机内存以及动态内存满足版本质量   |           |
| 基础性能  |小型系统内存专项|开机以及动态内存整机达标，子系统无严重问题| 不满足   | 小型系统图库、相机、设置、查看图片、拍照均满足测试要求。录像模块存在异常  |https://gitee.com/openharmony/multimedia_camera_lite/issues/I3YD64?from=project-issue|

## 4.6   功耗专项测试结论

*以表格形式汇总各专项测试执行情况及遗留问题情况的评估，给出专项质量评估结论*

*要求：无严重问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
| 待机功耗  | 待机功耗   |待机功耗达标|  满足    | 待机质量满足版本质量要求      |           |
| 场景功耗  | 场景功耗   |场景测试达标|  不满足  | 相机拍照、预览满足测试要求。录像场景存在异常 | https://gitee.com/openharmony/multimedia_camera_lite/issues/I3YD64?from=project-issue|

# 5   问题单统计

【OpenHarmony】【2.3.0.1】【轻内核子系统】 L0支持三方组件curl编译失败 https://gitee.com/openharmony/kernel_liteos_m/issues/I3YJU8

【OpenHarmony】【2.3.0.1】【轻内核子系统】liteos-a內核模块可配置编译失败https://gitee.com/openharmony/kernel_liteos_m/issues/I3YJRO

【OpenHarmony】【2.3.0.1】【轻内核子系统】文件系统维测增强功能在该版本有问题https://gitee.com/openharmony/kernel_liteos_a/issues/I3YNWM

【OpenHarmony】【2.3.0.1】【轻内核子系统】bin目录下没有mksh和toybox，导致已转测的toybox命令集和shell交互友好性提升无法测试https://gitee.com/openharmony/kernel_liteos_a/issues/I3VEOG

【OpenHarmony】【2.3.0.1】【轻内核子系统】 clock_getres 函数传入非法ID值-29，会返回0 https://gitee.com/openharmony/kernel_liteos_m/issues/I3YVPB

【轻内核子系统集成测试】关于在mq_open失败后，会占用消息队列符，使用mq_close也会失败，最终导致xml文件打不开https://gitee.com/openharmony/kernel_liteos_a/issues/I3ZQDA

【轻内核子系统集成测试】发送两个不同的信号，sigwait第二次等到的仍是第一个信号https://gitee.com/openharmony/kernel_liteos_a/issues/I3M12H

录像模块异常 https://gitee.com/openharmony/multimedia_camera_lite/issues/I3YD64?from=project-issue