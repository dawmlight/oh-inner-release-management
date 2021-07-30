

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
| *2*  | 轻内核子系统 | 1、轻量系统的特性和变更由于wifiiot_hispark_pegasus不支持，暂时无法测试，不对轻量系统进行评估<br />2、小型系统特性基本功能可用，新增shell及命令集特性该版本不稳定，新增其他特性基本可用<br />3、标准系统无新增特性，特性基本可用 |      |
| *3*  | 泛sensor服务子系统 | 没有新增特性，XTS用例测试通过，特性质量良好 |   小型系统   |
| *4* | 电源子系统 | 无新增特性，测试用例执行通过，特性质量良好 | |
| *5*  | 启动恢复子系统 | 没有新增特性，L0L1设备XTS测试用例测试通过，特性质量良好，L2设备XTS用例测试通过（设备信息获取和系统属性获取测试通过，特性质量良好），恢复出厂和清除用户数据的两个api（因调用api，设备会重启，用例不在xts，本地手动编译hap包测试）测试不通过，api调用设备未重启，用户数据未清除，已提严重单 | https://gitee.com/openharmony/community/issues/I430Z5?from=project-issue     |

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
|  |  | | | |

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
