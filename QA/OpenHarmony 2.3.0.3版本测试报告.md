

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

| 序号 | 特性名称     | 特性质量评估                                             | 备注 |
| ---- | ------------ | -------------------------------------------------------- | ---- |
| *1*  | 轻内核子系统 | 轻量系统，小型系统，新增需求特性不稳定，内核基础功能可用 |      |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

### 4.1.2   新需求评价

*以表格的形式汇总新特性测试执行情况及遗留问题情况的评估,给出特性质量评估结论。*

| lssue号                                                      | 特性名称                                                  | 特性质量评估               | 约束依赖说明 | 备注                                           |
| ------------------------------------------------------------ | --------------------------------------------------------- | -------------------------- | ------------ | ---------------------------------------------- |
| [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强                          | 特性基本可用，遗留少量问题 |              | 由于toybox相关需求未合入,top/ps/free命令不可用 |
| [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】轻量系统支持轻量级shell框架和常用调测命令 | 无法测试                   |              | wifiiot_hispark_pegasus上不支持，无法测试      |
| [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】轻量系统LiteOS-M支持ARM9架构              | 特性不稳定，风险高         |              |                                                |
| [I41GOS](https://gitee.com/openharmony/distributeddatamgr_file/issues/I41GOS) |【分布式文件子系统】（需求）基于JS语言实现system.file接口|特性基本功能可用，遗留少量问题|              |缺少完整的稳定性测试，待后续阶段补充验证|
|                                                              |                                                           |                            |              |                                                |
|                                                              |                                                           |                            |              |                                                |

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

[【OpenHarmony】【2.3.0.3】【轻内核子系统】集成测试linux内核的L1设备不支持sched_setscheduler](https://gitee.com/openharmony/third_party_musl/issues/I41PQT)

[【OpenHarmony】【20210701】【轻内核子系统】集成测试关于按照开发要求修改的getgroups问题，会造成有些用例用户态异常](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ZJ1D)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试nanosleep函数实现存在缺陷](https://gitee.com/openharmony/kernel_liteos_a/issues/I41U0R)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试 在执行ActsMemApiTest.bin脚本，出现大量多余日志。 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I41PVY)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试toybox命令没有合入影响proc文件系统增强特性验收](https://gitee.com/openharmony/kernel_liteos_a/issues/I41XOY)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试 由于修改了开发的代码，导致Xts里面的IPC模块用例执行出错 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I41PBB)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试gid默认的情况下为0不符合权限最小化的原则 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I41OKR)

[【OpenHarmony】【2.3.0.2】【轻内核子系统】集成测试benchmark稳定性./lat_ctx -P 5 -s 16/64 8执行异常](https://gitee.com/openharmony/kernel_liteos_a/issues/I40YGU)

[【OpenHarmony】【2.3.0.2】【轻内核子系统】集成测试benchmark测试用例执行命令./lat_fs /test_root/kernel... ](https://gitee.com/openharmony/kernel_liteos_a/issues/I40YD4)

[【OpenHarmony】【2.3.0.1】【轻内核子系统】集成测试关于在mq_open失败后，会占用消息队列符，最终导致xml文件打不开](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ZQDA)

[【OpenHarmony】【1.0.1release】【轻内核子系统】集成测试fs模块storage下有失败用例 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I3WU8Y)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试/kernel/arch/arm/arm9/gcc下的代码存在函数冲突](https://gitee.com/openharmony/kernel_liteos_m/issues/I420PQ)

[【OpenHarmony】【20210706】【轻内核子系统】集成测试exec执行bin文件后界面卡死，无法继续使用](https://gitee.com/openharmony/third_party_mksh/issues/I41ARZ)

[【OpenHarmony】【20210419】【轻内核子系统】集成测试发送两个不同的信号，sigwait第二次等到的仍是第一个信号](https://gitee.com/openharmony/kernel_liteos_a/issues/I3M12H)

[【OpenHarmony】【20210414】【轻内核子系统】集成测试不支持功能需要在.h中说明](https://gitee.com/openharmony/kernel_liteos_m/issues/I3IPD7)



























