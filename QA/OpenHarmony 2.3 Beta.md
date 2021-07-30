

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
| *1*  | *XXX子系统* | *没有新增特性，XX测试通过，基本功能可用* |      |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

### 4.1.2   新需求评价

*以表格的形式汇总新特性测试执行情况及遗留问题情况的评估,给出特性质量评估结论。*



事件通知特性质量评估：通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果；

| lssue号                                                      | 特性名称                                 | 特性质量评估 | 约束依赖说明 | 备注 |
| ------------------------------------------------------------ | ---------------------------------------- | ------------ | ------------ | ---- |
| [I40PB8](https://gitee.com/open_harmony/dashboard?issue_id=I40PB8) | 应用侧取消本地所有通知                   | 特性基本可用 |              |      |
| [I40PB0](https://gitee.com/open_harmony/dashboard?issue_id=I40PB0) | 应用侧发布本地多行类型通知               | 特性基本可用 |              |      |
| [I40PB1](https://gitee.com/open_harmony/dashboard?issue_id=I40PB1) | 应用侧发布本地长文本通知                 | 特性基本可用 |              |      |
| [I40PB2](https://gitee.com/open_harmony/dashboard?issue_id=I40PB2) | 应用侧发布本地内容资讯类型的普通文本通知 | 特性基本可用 |              |      |
| [ I40PB3](https://gitee.com/open_harmony/dashboard?issue_id=I40PB3) | 应用侧发布本地其他类型的普通文本通知     | 特性基本可用 |              |      |
| [I40PB4](https://gitee.com/open_harmony/dashboard?issue_id=I40PB4) | 应用侧发布本地服务提醒类型的普通文本通知 | 特性基本可用 |              |      |
| [I40PB5](https://gitee.com/open_harmony/dashboard?issue_id=I40PB5) | 应用侧发布本地社交通讯类型的普通文本通知 | 特性基本可用 |              |      |
|                                                              |                                          |              |              |      |

​      

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

NA