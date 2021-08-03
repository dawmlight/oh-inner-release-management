

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

# 1   概述

描述本次被测对象变更内容。

# 2   测试版本说明

描述测试版本信息。

| 版本名称              | 测试起始时间 | 测试结束时间 |
| --------------------- | ------------ | ------------ |
| OpenHarmony 2.2 Beta2 |              |              |

描述本次测试的测试环境（包括环境软硬件版本信息，环境组网配置信息, 测试辅助工具等）。

| 硬件型号        | 硬件配置信息 | 备注                                              |
| --------------- | ------------ | ------------------------------------------------- |
| hispark_pegasus | Hi3861开发板 | docs/zh-cn/device-dev/quick-start/Hi3861开发板.md |
| hispark_aries   | Hi3518开发板 | docs/zh-cn/device-dev/quick-start/Hi3518开发板.md |
| hispark_taurus  | Hi3516开发板 | docs/zh-cn/device-dev/quick-start/Hi3516开发板.md |

 

# 3   版本概要测试结论



# 4   版本详细测试结论

*本章节针对总体测试策略计划的测试内容，给出详细的测试结论。*

## 4.1   特性测试结论



### 4.1.1   继承特性评价

*继承特性进行评价，用表格形式评价，包括特性列表，验证质量评估。*

XXX子系统：特性质量良好

| 序号 | 特性名称    | 特性质量评估                             | 备注 |
| ---- | ----------- | ---------------------------------------- | ---- |
| *1*  | 标准系统DFX子系统 | 没有新增特性，XTS测试用例测试通过同，XTS用例并发压测场景异常，Hilogd异常退且卡死，开发已定位，解决当中 |https://gitee.com/openharmony/hiviewdfx_hilog/issues/I42B9Y      |
| *2*  | 轻内核子系统 | 1、轻量系统的特性和变更由于wifiiot_hispark_pegasus不支持，暂时无法测试，不对轻量系统进行评估<br />2、小型系统特性基本功能可用，新增shell及命令集特性该版本不稳定，新增其他特性基本可用<br />3、标准系统无新增特性，特性基本可用 |      |
| *3*  | 泛sensor服务子系统 | 没有新增特性，XTS用例测试通过，特性质量良好 |   小型系统   |
| *4* | 电源子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| *5*  | 启动恢复子系统 | 没有新增特性，L0L1设备XTS测试用例测试通过，特性质量良好，L2设备XTS用例测试通过（设备信息获取和系统属性获取测试通过，特性质量良好），恢复出厂和清除用户数据的两个api（因调用api，设备会重启，用例不在xts，本地手动编译hap包测试）测试不通过，api调用设备未重启，用户数据未清除，已提严重单 | https://gitee.com/openharmony/community/issues/I430Z5?from=project-issue     |
| *6* | 驱动子系统 | 1、camera、audio、usb驱动基本功能正常，遗留少量问题<br />2、WiFi驱动基本功能正常，resetDriver接口调用失败问题<br />3、马达sensor特性质量良好 | 遗留问题参考issue |
| *7*  | *数据管理子系统* | *新增特性测试通过，基本功能可用* |      |

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

### 4.1.2   新需求评价

*以表格的形式汇总新特性测试执行情况及遗留问题情况的评估,给出特性质量评估结论。*



| lssue号                                                      | 特性名称                                 | 特性质量评估 | 约束依赖说明 | 备注 |
| ------------------------------------------------------------ | ---------------------------------------- | ------------ | ------------ | ---- |
| [I40PB8](https://gitee.com/open_harmony/dashboard?issue_id=I40PB8) | 应用侧取消本地所有通知                   | 特性基本可用 |  | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [I40PB0](https://gitee.com/open_harmony/dashboard?issue_id=I40PB0) | 应用侧发布本地多行类型通知               | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [I40PB1](https://gitee.com/open_harmony/dashboard?issue_id=I40PB1) | 应用侧发布本地长文本通知                 | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [I40PB2](https://gitee.com/open_harmony/dashboard?issue_id=I40PB2) | 应用侧发布本地内容资讯类型的普通文本通知 | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [ I40PB3](https://gitee.com/open_harmony/dashboard?issue_id=I40PB3) | 应用侧发布本地其他类型的普通文本通知     | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [I40PB4](https://gitee.com/open_harmony/dashboard?issue_id=I40PB4) | 应用侧发布本地服务提醒类型的普通文本通知 | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| [I40PB5](https://gitee.com/open_harmony/dashboard?issue_id=I40PB5) | 应用侧发布本地社交通讯类型的普通文本通知 | 特性基本可用 |              | 通知能力不完整，当前只有发布通知能力，无订阅通知能力（订阅相关需求没有交付）影响：因为无法订阅通知，发布的通知没有任何用户可以感知的效果； |
| I3XY72                                                             | c++与 js时间\日期和数字国际化能力构建                                         |特性质量良好              |              |      |
| [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】轻量系统上支持基于NOR Flash的littlefs文件系统 |无法测试，暂不评估 | | wifiiot_hispark_pegasus不支持，无法测试 |
| [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】轻量系统上对外提供统一的文件系统操作接口 |无法测试，暂不评估 | | wifiiot_hispark_pegasus不支持，无法测试 |
| [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】轻量系统补充120个POSIX接口 |无法测试，暂不评估 | | wifiiot_hispark_pegasus不支持，无法测试 |
| [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器 |特性不稳定，风险高 | rootfs需使用mksh_rootfs_vfat.img | mksh_rootfs_vfat.img和rootfs_vfat.img仅shell及命令集存在差异，其他组件完全一致 |
| [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升 |特性不稳定，风险高 | rootfs需使用mksh_rootfs_vfat.img | mksh_rootfs_vfat.img和rootfs_vfat.img仅shell及命令集存在差异，其他组件完全一致 |
| [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集 |特性不稳定，风险高 | rootfs需使用mksh_rootfs_vfat.img | mksh_rootfs_vfat.img和rootfs_vfat.img仅shell及命令集存在差异，其他组件完全一致 |
| [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块 |特性质量良好 | | |
| [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理 |特性质量良好 | | |
| [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块 |特性质量良好 | | |
| [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强 |特性质量良好 | | |
| [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置 |特性质量良好 | | |
| [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配 |特性基本可用 | | |
| [ I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】轻量系统支持三方组件Mbedtls编译 |特性质量良好 | | |
| [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】轻量系统支持三方组件curl编译 |特性质量良好 | | |
| [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强 |特性基本可用，遗留少量问题 | | 由于toybox相关需求未合入,top/ps/free命令不可用 |
| [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】轻量系统支持轻量级shell框架和常用调测命令 |无法测试 | | wifiiot_hispark_pegasus不支持，无法测试 |
| [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】轻量系统LiteOS-M支持ARM9架构 |特性不稳定，风险高 | | |
| [I3ID9Q](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道 |特性基本功能良好，但端到端流程不通，风险高 | | |
| [I3ID9V](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】轻量设备启动富设备上的Ability |特性基本功能良好，但端到端流程不通，风险高 | | |
|  |  | | | |
| [I3XM04](https://gitee.com/openharmony/multimedia_audio_standard/issues/I3XM04) | 【多媒体子系统】Audio音频管理模块及API |特性基本可用 | |基本功能无问题，性能稳定性，安全待验证 |
| [I3XLZR](https://gitee.com/openharmony/multimedia_audio_standard/issues/I3XLZR) | 【多媒体子系统】AudioService音频服务 |特性不稳定，风险高 | |播放功能可用，录制功能缺乏三方插件无法使用 |
| [I3XM34](https://gitee.com/openharmony/multimedia_media_standard/issues/I3XM34) | 【多媒体子系统】MediaService播放服务 |特性基本可用，遗留少量问题 | |（1）Media模块功能测试场景下设置音量异常（2）Media模块执行hstmediatest /data/1.mp4 win报错：player is null（3）Media模块执行ActsMedia模块用例报错Segmentation fault|
| [I3XM2V](https://gitee.com/openharmony/multimedia_media_standard/issues/I3XM2V) | 【多媒体子系统】Media媒体处理模块及API |特性基本可用  | |基本功能无问题，性能稳定性，安全待验证 |
| [I3XM2C](https://gitee.com/openharmony/multimedia_camera_standard/issues/I3XM2C) | 【多媒体子系统】CameraService 相机服务 |特性基本可用  | |基本功能无问题，性能稳定性，安全待验证 |
| [I3XM1U](https://gitee.com/openharmony/multimedia_camera_standard/issues/I3XM1U) | 【多媒体子系统】Camera相机处理模块及API |特性不稳定，风险高  | |相机拍照预览基本功能可用， 稳定性较差，存在预览黑屏问题。闪光灯、曝光、对焦、调焦设置不生效。 |
| [I41GOS](https://gitee.com/openharmony/distributeddatamgr_file/issues/I41GOS) |【分布式文件子系统】（需求）基于JS语言实现system.file接口|特性基本功能可用，遗留少量问题|              |缺少完整的稳定性测试，待后续阶段补充验证|
| [I3WHJS](https://gitee.com/open_harmony/dashboard?issue_id=I3WHJS) | 基于HDF驱动框架提供马达驱动程序适配 | 特性质量良好 | | |
| [I3ZRA7](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRA7) | 基于HDF驱动框架提供加速度传感器驱动程序适配                  | 特性质量良好 | | |
| [I41HBJ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBJ) | 【驱动子系统】提供Audio HDI接口实现 | 特性基本可用 | | |
| [I41HBK](https://gitee.com/open_harmony/dashboard?issue_id=I41HBK) | 【驱动子系统】Audio 驱动框架用户态接口库 | 特性基本可用 | | |
| [I41HBM](https://gitee.com/open_harmony/dashboard?issue_id=I41HBM) | 【驱动子系统】提供支持MPI接口的用户态接口库 | 特性基本可用 | | |
| [I41HBN](https://gitee.com/open_harmony/dashboard?issue_id=I41HBN) | 【驱动子系统】HDI接口支持跨进程通信 | 特性基本可用 | | |
| [I41HBH](https://gitee.com/open_harmony/dashboard?issue_id=I41HBH) | 【驱动子系统】基于HDF驱动框架提供WIFI支持HDI接口能力 | 特性基本可用，遗留少量问题 | | |
| [I41HBG](https://gitee.com/open_harmony/dashboard?issue_id=I41HBG) | 【驱动子系统】基于HDF驱动框架提供WIFI支持P2P驱动能力 | 无法测试，暂不评估 | | |
| [I41HBI](https://gitee.com/open_harmony/dashboard?issue_id=I41HBI) | 【驱动子系统】提供Audio Driver Model驱动模型框架 | 特性基本可用 | | |
| [I41HBA](https://gitee.com/open_harmony/dashboard?issue_id=I41HBA) | 【驱动子系统】基于HDF驱动框架提供keyboard驱动能力 | 特性基本可用 | | |
| [I41HBZ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBZ) | 【驱动子系统】基于HDF框架提供USB device DDK | 特性基本可用 | | |
| [I41HBU](https://gitee.com/open_harmony/dashboard?issue_id=I41HBU) | 【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层BufferManager | 特性基本可用 | | |
| [I41HBV](https://gitee.com/open_harmony/dashboard?issue_id=I41HBV) | 【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层utils通用组件(thread、event、watchdog) | 特性基本可用 | | |
| [I41HBX](https://gitee.com/open_harmony/dashboard?issue_id=I41HBX) | 【驱动子系统】基于HDF驱动框架提供Camera驱动多平台扩展平台适配 | 特性基本可用 | | |
| [I41HBY](https://gitee.com/open_harmony/dashboard?issue_id=I41HBY) | 【驱动子系统】基于HDF框架提供USB host DDK | 特性基本可用 | | |
| [I41HBP](https://gitee.com/open_harmony/dashboard?issue_id=I41HBP) | 【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备控制（CameraDevice） | 特性基本可用 | | |
| [I41HBQ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBQ) | 【驱动子系统】基于HDF驱动框架提供相机标准南向接口Image流控制（StreamOperator） | 特性基本可用 | | |
| [I41HBR](https://gitee.com/open_harmony/dashboard?issue_id=I41HBR) | 【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera HDI接口 | 特性基本可用 | | |
| [ I41HBS](https://gitee.com/open_harmony/dashboard?issue_id=I41HBS) | 【驱动子系统】基于HDF驱动框架提供Pipeline管理 | 特性基本可用 | | |
| [I41HBT](https://gitee.com/open_harmony/dashboard?issue_id=I41HBT) | 【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层设备管理DeviceManager | 特性基本可用 | | |
| [I41HBO](https://gitee.com/open_harmony/dashboard?issue_id=I41HBO) | 【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备管理（CameraHost） | 特性基本可用 | | |
| 无  | 软总线-支持自组网 | 特性基本可用,特定场景下风险高 |                                                      | 1、开发自测：在wlan（网线直连）连接下，自组网功能稳定，重启设备/开关网络典型场景可以成功自组网；  2、在wifi组网下，基本功能可用，但是在开关网络/重启设备典型场景下自组网失败，涉及4个缺陷issue：[I4312A](https://gitee.com/openharmony/communication_dsoftbus/issues/I4312A), [I4311S](https://gitee.com/openharmony/communication_dsoftbus/issues/I4311S) , [I43118](https://gitee.com/openharmony/communication_dsoftbus/issues/I43118), [I43107](https://gitee.com/openharmony/communication_dsoftbus/issues/I43107)                                                 |
| 无  | 软总线-支持IPC/RPC | 特性质量良好 |                                 |  1、本特性代码复用富鸿蒙代码，当前开发自测用例全部pass，上层分布式音乐使用RPC特性，无RPC遗留问题；2、特性的JS API未交付，测试侧将基于JS API进行特性测试                   |
| [I3ZMUM](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMUM) |【本地数据库轻量级数据库JS API交付，对标开源+小程序 | 特性基本可用 |      |      |
| [I3ZMW4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMW4) |【本地数据库】提供RDB和PREFERENCES的能力 | 特性基本可用 |              |      |
| [I3ZMX5](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMX5) |【本地数据库】 支持ResultSet滑动窗口能力 | 特性基本可用 |              |      |
| [I3YC8O](https://gitee.com/open_harmony/dashboard?issue_id=I3YC8O) |【分布式数据库】支持JS接口创建分布式数据库 | 特性基本可用 |              |      |
| [I3ZN3M](https://gitee.com/open_harmony/dashboard?issue_id=I3ZN3M) |【分布式数据管理子系统】【分布式数据库】鸿蒙单框架支持分布式数据管理能力 | 特性基本可用 |              |      |
| [I42IMT](https://gitee.com/open_harmony/dashboard?issue_id=I42IMT) |RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式计算器| 特性不稳定，风险高 |              |分布式计算器，本端计算器可以调起对端设备的计算器，但数据不能同步，必现问题|
| [I42IKN](https://gitee.com/open_harmony/dashboard?issue_id=I42IKN) |RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式音乐播放器| 特性不稳定，风险高 |              |1：分布式音乐，本端正在播放的音乐，点击流转，无法流转到对端设备播放，必现问题；2：分布式音乐，本端无播放任务，点击流转到对端设备，对端设备音乐正常拉起后退出，概率问题|

*特性质量评估可选项：特性不稳定，风险高\特性基本可用，遗留少量问题\特性质量良好*

## 4.2   兼容性测试结论

NA

## 4.3   安全专项测试结论

本版本共涉及9个子系统（安全需关注）有新增需求，所有子系统均已完成安全合规测试，安全合规组并进行了整机测试，当前遗留18个安全issue没有关闭。
公开漏洞方面，有两个组件存在大量漏洞没有修复：Kernel 4.19存在14个CVE漏洞，其中7个严重级别以上、ffmpeg 4.2.2存在78个CVE漏洞,其中12个严重级别以上。
安全编码告警和危险函数方面，Linux内核、启动恢复、驱动、轻内核等子系统存在危险函数未清零；轻图形、轻内核、驱动、分页式调试等子系统存静态告警未清零。
综合以上结论，安全测试结果评估为不通过。
遗留问题列表如下：

| 问题描述 | 问题类型 | 状态 | URL |
|---|---|---|---|
| /etc/passwd里面存在UID一样的用户账号，与规范要求冲突| 安全问题| 开启的| https://gitee.com/openharmony/startup_init_lite/issues/I42ZO7?from=project-issue|
| CVE-2021-21781|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42HM6?from=project-issue|
| CVE-2021-22555|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42HLL?from=project-issue|
| CVE-2021-35039|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42HL9?from=project-issue|
| CVE-2021-3609	|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42H1R?from=project-issue|
| CVE-2021-33624|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42H19?from=project-issue|
| CVE-2021-34693|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42GZO?from=project-issue|
| CVE-2021-32078|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I42GYZ?from=project-issue|
| CVE-2021-33200|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421HX?from=project-issue|
| CVE-2020-36385|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421HO?from=project-issue|
| CVE-2021-3587|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421HG?from=project-issue|
| CVE-2021-0512|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421GE?from=project-issue|
| CVE-2021-3573|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421FB?from=project-issue|
| CVE-2021-0129|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421FG?from=project-issue|
| CVE-2021-3564|安全问题|进行中|https://gitee.com/openharmony/kernel_linux/issues/I421EH?from=project-issue|
| 【OpenHarmony】【版本号：2.3.0.3】组件ffmpeg 4.2.2存在78个未修复漏洞| 安全问题| 开启的| https://gitee.com/openharmony/device_hisilicon_third_party_ffmpeg/issues/I4213Q?from=project-issue|
| liteipc的创建需要ioctl方式，否则会暴露内核地址。| 安全问题| 开启的| https://gitee.com/openharmony/communication_ipc_lite/issues/I3SNO5?from=project-issue|
| 构建时ffmpeg目录下的文件属性都变成了rwxrwxrwx| 安全问题| 开启的| https://gitee.com/openharmony/device_hisilicon_modules/issues/I2C7NP?from=project-issue|

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
| 基础性能 | 轻量系统静态模型 | 静态KPI通过率100% | 满足   |  轻量系统无感配网满足版本质量 |           |
| 基础性能 | 小型系统静态模型 | 静态KPI通过率100% | 不满足 |  小型系统图库、查看图片、拍照、录像均满足测试要求，设置以及相机启动时延劣化 | https://gitee.com/openharmony/community/issues/I434RE  |
| 基础性能 | 标准系统静态模型 | 静态KPI通过率100% | 无法评估 |  标准系统在部分单板烧板后无法启动、图库应用异常 | 当前标准系统无静态基线 |
| 基础性能 | 轻量系统内存专项 | 开机以及动态内存整机达标，子系统无严重问题 | 满足   |  轻量系统无感配网满足版本质量 |           |
| 基础性能 | 小型系统内存专项 | 开机以及动态内存整机达标，子系统无严重问题 | 不满足 |  3516以及3518常驻内存均未达标 | https://gitee.com/openharmony/community/issues/I434AD  https://gitee.com/openharmony/community/issues/I434P1|
| 基础性能 | 标准系统静态模型 | 开机以及动态内存整机达标，子系统无严重问题 | 无法评估 |  标准系统在部分单板烧板后无法启动、图库应用异常 | 当前标准系统无内存基线 |

## 4.6   功耗专项测试结论

*以表格形式汇总各专项测试执行情况及遗留问题情况的评估，给出专项质量评估结论*

*要求：无严重问题

| 测试分类 | 测试评估项 | 质量目标 | 是否满足 | 测试结果及关键遗留问题/风险 | 备注issue |
| -------- | ---------- | -------- | -------- | --------------------------- | --------- |
| 待机/场景功耗 | 小型系统待机/场景功耗 | 待机功耗达标 |  满足  | 待机/场景质量满足版本质量要 |           |
| 待机/场景功耗 | 标准系统待机/场景功耗 | 待机功耗达标 |  无法评估  | 标准系统无待机/场景功耗基线  |           |


# 5   问题单统计

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试/kernel/arch/arm/arm9/gcc下的代码存在函数冲突](https://gitee.com/openharmony/kernel_liteos_m/issues/I420PQ)

[【OpenHarmony】【2.3.0.3】【轻内核子系统】集成测试linux内核的L1设备不支持sched_setscheduler](https://gitee.com/openharmony/third_party_musl/issues/I41PQT)

[【OpenHarmony】【20210701】【轻内核子系统】集成测试testBarrierAlwaysWait在执行时会挂住，不往下执行](https://gitee.com/openharmony/kernel_liteos_a/issues/I40QOM)

[【openHarmony】【2.3 beta】【轻内核子系统】集成测试 ROM数据统计超出基线值](https://gitee.com/openharmony/kernel_liteos_a/issues/I42MR8)

[【OpenHarmony】【2.3_Beta】【轻内核子系统】集成测试pread函数返回值与之前版本不一致](https://gitee.com/openharmony/kernel_liteos_a/issues/I42G3N)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试toybox命令没有合入影响proc文件系统增强特性验收](https://gitee.com/openharmony/kernel_liteos_a/issues/I41XOY)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试 ipc_posix里面的pipe_fifo模块的testFifoNonblack用例出错 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I41PBB)

[【openHarmony】【2.3.0.3】【轻内核子系统】集成测试gid默认的情况下为0不符合权限最小化的原则](https://gitee.com/openharmony/kernel_liteos_a/issues/I41OKR)

[【OpenHarmony】【2.3.0.2】【轻内核子系统】集成测试benchmark稳定性./lat_ctx -P 5 -s 16/64 8执行异常](https://gitee.com/openharmony/kernel_liteos_a/issues/I40YGU)

[【OpenHarmony】【2.3.0.2】【轻内核子系统】集成测试benchmark测试用例执行命令./lat_fs /test_root/kernel... ](https://gitee.com/openharmony/kernel_liteos_a/issues/I40YD4)

[【OpenHarmony】【2.3.0.1】【轻内核子系统】集成测试关于在mq_open失败后，会占用消息队列符，最终导致xml文件打不开 ](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ZQDA)

[【openHarmony】【轻内核子系统】集成测试开发板移植指导中需增加线程不足的确认方法和配置线程个数的方法](https://gitee.com/openharmony/kernel_liteos_m/issues/I42LCU)

[【OpenHarmony】【20210419】【轻内核子系统】集成测试发送两个不同的信号，sigwait第二次等到的仍是第一个信号](https://gitee.com/openharmony/kernel_liteos_a/issues/I3M12H)

[【OpenHarmony】【20210414】【轻内核子系统】集成测试不支持功能需要在.h中说明 ](https://gitee.com/openharmony/kernel_liteos_m/issues/I3IPD7)

shell命令相关问题单：

[【OpenHarmony】【20210726】【轻内核子系统】集成测试每日构建20210726版本toybox umount失败](https://gitee.com/openharmony/third_party_toybox/issues/I42OHU)

[【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令kill、cp、mv等命令有些操作提示信息不合理，有些操作回显中有e... ](https://gitee.com/openharmony/third_party_toybox/issues/I42VH1)

[【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox命令cp文件到不存在的目录，没有报错，并且在cp的当前目录下生成了一个名为...](https://gitee.com/openharmony/third_party_toybox/issues/I42V8S)

[【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令chmod修改文件权限后查出与预期不一致以及nfs挂载目录下的文件权...](https://gitee.com/openharmony/third_party_toybox/issues/I42V89)

[【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令rmdir删除mount路径下的mkdir的子目录失败，rm -r同...](https://gitee.com/openharmony/third_party_toybox/issues/I42TTN)

[【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令kill -s 9 10杀10号进程不生效，kill 9 10可以，其他](https://gitee.com/openharmony/third_party_toybox/issues/I42TP2)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试toybox ls -l查看自己创建的文件目录大小时间日期以及total统计不正确](https://gitee.com/openharmony/third_party_toybox/issues/I42OOU)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试uname r v top a支持,help中缺少,chmod R不支持,help中有；](https://gitee.com/openharmony/third_party_toybox/issues/I42OMN)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试toybox ping自己发送10个包，实际发送20个包，以及包的丢失率计算错误 ](https://gitee.com/openharmony/third_party_toybox/issues/I42OJ0)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试toybox命令集需求实现30个toybox命令，实际目前只支持22个 ](https://gitee.com/openharmony/third_party_toybox/issues/I42OI4)

[【OpenHarmony】【20210726】【轻内核子系统】集成测试直接执行cat后无法退出，需要重启设备恢复](https://gitee.com/openharmony/third_party_mksh/issues/I42N33)

[【OpenHarmony】【20210706】【轻内核子系统】集成测试exec执行bin文件后界面卡死，无法继续使用](
[【startup_standard】【master】L2-Beta2版本测试恢复出厂和清除用户数据的api测试失败](https://gitee.com/openharmony/community/issues/I430Z5?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】Media模块功能测试场景下设置音量异常](https://gitee.com/openharmony/multimedia_media_standard/issues/I4342U?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】Media模块执行hstmediatest /data/1.mp4 win报错：player is null](https://gitee.com/openharmony/multimedia_media_standard/issues/I4344Z?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】Media模块执行ActsMedia模块用例报错Segmentation fault](https://gitee.com/openharmony/multimedia_camera_standard/issues/I43699?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】L2-Beta2版本 使用JSDemo测试，相机拍照结束后，点击缩率查看照片，相机Crash，再次打开相机黑屏](https://gitee.com/openharmony/multimedia_media_standard/issues/I43489?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】L2-Beta2版本 使用JSDemo测试，打开应用，home切回后台，重复几次, 预览黑屏](https://gitee.com/openharmony/multimedia_camera_standard/issues/I4364S?from=project-issue)

[【OpenHarmony】【2.3 beta】【多媒体子系统】L2-Beta2版本 camera用例执行失败](https://gitee.com/openharmony/multimedia_camera_standard/issues/I435E5?from=project-issue)

[【OpenHarmony 2.2 Beta2】【驱动子系统】L2单板camera DFx测试用例失败](https://gitee.com/openharmony/drivers_peripheral/issues/I43339?from=project-issue)

[【OpenHarmony 2.2 Beta2】【驱动子系统】L2单板audio接口测试用例失败](https://gitee.com/openharmony/drivers_peripheral/issues/I4331P?from=project-issue)

[【OpenHarmony 2.3 Beta 】【驱动子系统】L2单板上wifi ResetDriver接口测试失败](https://gitee.com/openharmony/drivers_peripheral/issues/I422US?from=project-issue)

标准系统DFX子系统

[并发运行多个hilog测试用例，hilogd进程异常，且hilog命令会卡住](https://gitee.com/openharmony/hiviewdfx_hilog/issues/I42B9Y)

标准系统启动恢复子系统

[【startup_standard】【master】L2-Beta2版本测试恢复出厂和清楚用户数据的api测试失败](https://gitee.com/openharmony/community/issues/I430Z5?from=project-issue)

标准系统软总线子系统

[【2.2 Beta2】【软总线】已组网，断1端网络后，自组网失败(GetAllNodeDeviceInfo返回null)](https://gitee.com/openharmony/communication_dsoftbus/issues/I4312A)
[【2.2 Beta2】【软总线】发送数据成功后，close session必现无回调](https://gitee.com/openharmony/communication_dsoftbus/issues/I4311S)
[【2.2 Beta2】【软总线】已组网，重启设备配网后，自组网不成功](https://gitee.com/openharmony/communication_dsoftbus/issues/I43118)
[【2.2 Beta2】【软总线】重启2个设备，配网后组网成功，opensession失败](https://gitee.com/openharmony/communication_dsoftbus/issues/I43107)

安全专项

[/etc/passwd里面存在UID一样的用户账号，与规范要求冲突](https://gitee.com/openharmony/startup_init_lite/issues/I42ZO7?from=project-issue) 
[ CVE-2021-21781](https://gitee.com/openharmony/kernel_linux/issues/I42HM6?from=project-issue )
[CVE-2021-22555  ](https://gitee.com/openharmony/kernel_linux/issues/I42HLL?from=project-issue)
[CVE-2021-35039 ](https://gitee.com/openharmony/kernel_linux/issues/I42HL9?from=project-issue)
[CVE-2021-3609 ](https://gitee.com/openharmony/kernel_linux/issues/I42H1R?from=project-issue)
[CVE-2021-33624](https://gitee.com/openharmony/kernel_linux/issues/I42H19?from=project-issue)
[CVE-2021-34693](https://gitee.com/openharmony/kernel_linux/issues/I42GZO?from=project-issue)
[CVE-2021-32078](https://gitee.com/openharmony/kernel_linux/issues/I42GYZ?from=project-issue)
[CVE-2021-33200](https://gitee.com/openharmony/kernel_linux/issues/I421HX?from=project-issue)
[CVE-2020-36385](https://gitee.com/openharmony/kernel_linux/issues/I421HO?from=project-issue)
[CVE-2021-3587](https://gitee.com/openharmony/kernel_linux/issues/I421HG?from=project-issue)
[CVE-2021-0512](https://gitee.com/openharmony/kernel_linux/issues/I421GE?from=project-issue)
[CVE-2021-3573](https://gitee.com/openharmony/kernel_linux/issues/I421FB?from=project-issue)
[CVE-2021-0129 ](https://gitee.com/openharmony/kernel_linux/issues/I421FG?from=project-issue)
[CVE-2021-3564](https://gitee.com/openharmony/kernel_linux/issues/I421EH?from=project-issue)
[【OpenHarmony】【版本号：2.3.0.3】组件ffmpeg 4.2.2存在78个未修复漏洞](https://gitee.com/openharmony/device_hisilicon_third_party_ffmpeg/issues/I4213Q?from=project-issue)
[liteipc的创建需要ioctl方式，否则会暴露内核地址](https://gitee.com/openharmony/communication_ipc_lite/issues/I3SNO5?from=project-issue)
[构建时ffmpeg目录下的文件属性都变成了rwxrwxrwx](https://gitee.com/openharmony/device_hisilicon_modules/issues/I2C7NP?from=project-issue)

稳定性专项

[反复开关机测试过程中打开photo应用，libmedialibrary_proxy.z.so模块异常重启，该问题还在定位当中](https://gitee.com/openharmony/multimedia_medialibrary_standard/issues/I4327J?from=project-issue)
[反复执行开关机测试，设备Panic异常卡死，该问题还在定位当中](https://gitee.com/openharmony/community/issues/I4329Z?from=project-issue)
[反复执行开关机测试，设备蓝屏不开机，该问题初步定位是公板DDR的问题](https://gitee.com/openharmony/community/issues/I4329M?from=project-issue)
[反复执行开关机测试，bootanimation进程异常，该问题还在定位当中](https://gitee.com/openharmony/community/issues/I432HF?from=project-issue)

性能专项

[小型系统图库、查看图片、拍照、录像均满足测试要求，设置以及相机启动时延劣化](https://gitee.com/openharmony/community/issues/I434RE)
[3516以及3518常驻内存均未达标](https://gitee.com/openharmony/community/issues/I434AD  https://gitee.com/openharmony/community/issues/I434P1)