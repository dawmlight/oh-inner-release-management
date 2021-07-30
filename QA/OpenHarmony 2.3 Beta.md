

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
| *1*  | 标准系统DFX子系统 | 没有新增特性，XTS测试用例测试通过同，XTS用例并发压测场景异常，Hilogd异常退且卡死，开发已定位，解决当中 |https://gitee.com/openharmony/hiviewdfx_hilog/issues/I42B9Y      |
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
| I3XY72                                                             | c++与 js时间\日期和数字国际化能力构建                                         |特性质量良好              |              |      |

​      

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

## 4.2   兼容性测试结论

*补充兼容性测试报告*

## 4.3   安全专项测试结论

*要求：无严重的隐私安全问题遗留，版本通过漏洞扫描，未解决的漏洞满足以下要求：*

本版本共涉及9个子系统（安全需关注）有新增需求，所有子系统均已完成安全合规测试，安全合规组并进行了整机测试，当前遗留18个安全issue没有关闭。
公开漏洞方面，有两个组件存在大量漏洞没有修复：Kernel 4.19存在14个CVE漏洞，其中7个严重级别以上、ffmpeg 4.2.2存在78个CVE漏洞,其中12个严重级别以上。
安全编码告警和危险函数方面，Linux内核、启动恢复、驱动、轻内核等子系统存在危险函数未清零；轻图形、轻内核、驱动、分页式调试等子系统存静态告警未清零。
综合以上结论，安全测试结果评估为不通过。
遗留问题列表如下：
问题描述	问题类型	状态	URL
/etc/passwd里面存在UID一样的用户账号，与规范要求冲突	安全问题	开启的	https://gitee.com/openharmony/startup_init_lite/issues/I42ZO7?from=project-issue
CVE-2021-21781	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42HM6?from=project-issue
CVE-2021-22555	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42HLL?from=project-issue
CVE-2021-35039	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42HL9?from=project-issue
CVE-2021-3609	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42H1R?from=project-issue
CVE-2021-33624	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42H19?from=project-issue
CVE-2021-34693	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42GZO?from=project-issue
CVE-2021-32078	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I42GYZ?from=project-issue
CVE-2021-33200	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421HX?from=project-issue
CVE-2020-36385	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421HO?from=project-issue
CVE-2021-3587	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421HG?from=project-issue
CVE-2021-0512	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421GE?from=project-issue
CVE-2021-3573	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421FB?from=project-issue
CVE-2021-0129	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421FG?from=project-issue
CVE-2021-3564	安全问题	进行中	https://gitee.com/openharmony/kernel_linux/issues/I421EH?from=project-issue
【OpenHarmony】【版本号：2.3.0.3】组件ffmpeg 4.2.2存在78个未修复漏洞	安全问题	开启的	https://gitee.com/openharmony/device_hisilicon_third_party_ffmpeg/issues/I4213Q?from=project-issue
liteipc的创建需要ioctl方式，否则会暴露内核地址。	安全问题	开启的	https://gitee.com/openharmony/communication_ipc_lite/issues/I3SNO5?from=project-issue
构建时ffmpeg目录下的文件属性都变成了rwxrwxrwx	安全问题	开启的	https://gitee.com/openharmony/device_hisilicon_modules/issues/I2C7NP?from=project-issue


## 4.4   稳定性专项测试结论

*a）执行反复开关机压力测试，运行5000次，无不开机问题；*
标准系统稳定性评估结论：无法达到连续开关机5000次的标准，最长的一次维持了56次，并且开关机过程中出现以下几个问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
|标准系统稳定性测试 | 开关机测试  | 开关机5000次无不开机问题  |否  |反复开关机测试过程中打开photo应用，libmedialibrary_proxy.z.so模块异常重启，该问题还在定位当中|https://gitee.com/openharmony/multimedia_medialibrary_standard/issues/I4327J?from=project-issue|
|标准系统稳定性测试 | 开关机测试  | 开关机5000次无不开机问题  |否  |反复执行开关机测试，设备Panic异常卡死，该问题还在定位当中 |https://gitee.com/openharmony/community/issues/I4329Z?from=project-issue |
|标准系统稳定性测试 | 开关机测试  | 开关机5000次无不开机问题  |否  |反复执行开关机测试，设备蓝屏不开机，该问题初步定位是公板DDR的问题 |https://gitee.com/openharmony/community/issues/I4329M?from=project-issue |
|标准系统稳定性测试 | 开关机测试  | 开关机5000次无不开机问题  |否  |反复执行开关机测试，bootanimation进程异常，该问题还在定位当中 |https://gitee.com/openharmony/community/issues/I432HF?from=project-issue|
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
