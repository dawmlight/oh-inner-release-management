## OpenHarmony 3.0.0.6版本转测试信息：
| **转测试版本号：OpenHarmony 3.0.0.6                |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第五轮测试，验收:|
|L0L1:本次转测试涉及应用程序框架和安全动态弹窗需求验收                                                |
|L2: Demo&应用、分布式任务调度、分布式数据管理、语言编译器运行时、驱动、事件通知等子系统特性    |
| **API变更：**：本次转测特性L2的语言编译器运行时涉及API变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-08-28**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.6/20210826_140808/version-Master_Version-OpenHarmony_3.0.0.6-20210826_140808-hispark_taurus.tar.gz |
| hispark_taurus_linux版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.6/20210826_140527/version-Master_Version-OpenHarmony_3.0.0.6-20210826_140527-hispark_taurus_linux.tar.gz |
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.6/20210826_140428/version-Master_Version-OpenHarmony_3.0.0.6-20210826_140428-hispark_pegasus.tar.gz  |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.6/20210826_140548/version-Master_Version-OpenHarmony_3.0.0.6-20210826_140548-hispark_aries.tar.gz|
| **L2转测试时间：2021-08-28**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.6/20210825_154426/version-Master_Version-OpenHarmony_3.0.0.6-20210825_154426-L2_hi3516dv300.tar.gz|
|         |

## OpenHarmony 3.0.0.6版本特性清单：
L1需求列表:
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3NN1Z](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3NN1Z) | 【应用程序框架】轻量级实现弹窗授权动态授权机制               | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 2    | [I3NTAZ](https://gitee.com/openharmony/security_huks/issues/I3NTAZ) | 【安全】轻量级实现弹窗授权动态授权机制                       | developing | SIG_Security         | [@scuteehuangjun](https://gitee.com/scuteehuangjun) |

L2需求列表:
L2 issue列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[I44BYM](https://gitee.com/open_harmony/dashboard?issue_id=I44BYM)|【2.2 Beta2】【软总线】L2与手机已组网，开关L2网络后无法再发现手机|
|[I46C6R](https://gitee.com/open_harmony/dashboard?issue_id=I46C6R)|【2.2 Beta2】【软总线】【发现】手机默认状态无法被L2发现，需要在超级终端中修改设置|
|[I45GRF](https://gitee.com/open_harmony/dashboard?issue_id=I45GRF)|【2.2 Beta2】【软总线】存在未close的session，remove session server无close回调，与上个版本不一致 |
|[I4311S](https://gitee.com/open_harmony/dashboard?issue_id=I4311S)|【2.2 Beta2】【软总线】发送数据成功后，close session必现无回调|
|[I46C6R](https://gitee.com/open_harmony/dashboard?issue_id=I46C6R)|【2.2 Beta2】【软总线】【发现】手机默认状态无法被L2发现，需要在超级终端中修改设置|

## OpenHarmony 3.0 Beta1版本转测试信息：
| **转测试版本号：OpenHarmony 3.0 Beta1                 |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代三Beta1测试，验收:|
|L0L1:软总线                                                |
|L2: 升级、用户程序框架等子系统特性     |
| **API变更：**：本次转测特性不涉及API变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-08-20**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0_Beta1/20210819_101714/version-Master_Version-OpenHarmony_3.0_Beta1-20210819_101714-hispark_taurus.tar.gz |
| hispark_taurus_linux版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0_Beta1/20210819_101510/version-Master_Version-OpenHarmony_3.0_Beta1-20210819_101510-hispark_taurus_linux.tar.gz  |
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0_Beta1/20210819_101448/version-Master_Version-OpenHarmony_3.0_Beta1-20210819_101448-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0_Beta1/20210819_101610/version-Master_Version-OpenHarmony_3.0_Beta1-20210819_101610-hispark_aries.tar.gz     |
| **L2转测试时间：2021-08-20**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0_Beta1/20210820_104612/version-Master_Version-OpenHarmony_3.0_Beta1-20210820_104612-L2_hi3516dv300.tar.gz|
|         |

## OpenHarmony 3.0 Beta1版本特性清单：
L1需求列表

| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
|1|[I3NIOF](https://gitee.com/openharmony/communication_dsoftbus/issues/I3NIOF)|【传输】传输SDK|developing|SIG_SoftBus|[@jiangkuaixue](https://gitee.com/jiangkuaixue)|

L2 需求列表：
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
|1|[I3XHVJ](https://gitee.com/open_harmony/dashboard?issue_id=I3XHVJ)|支持全量升级包升级|Testing|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|2|[I3XHVP](https://gitee.com/open_harmony/dashboard?issue_id=I3XHVP)|支持差分升级包升级|Testing|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|3|[I436VT](https://gitee.com/open_harmony/dashboard?issue_id=I436VT)|安装读取shortcut信息|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|

## 针对OpenHarmony 3.0 Beta1版本解决的缺陷ISSUE列表：

L0L1 issue列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I43KLC](https://gitee.com/open_harmony/dashboard?issue_id=I43KLC) |【2.2 Beta2】【软总线】注册节点状态监听，设备上线，设备再离线，offline回调调用了2次|
| [I43V23](https://gitee.com/open_harmony/dashboard?issue_id=I43V23) |【OpenHarmony】【3.0.0.1】【轻内核子系统】集成测试benchmark稳定性有个别命令存在执行异常和长时间跑不出结果的情况 |		
| [I43WIJ](https://gitee.com/open_harmony/dashboard?issue_id=I43WIJ) |【2.2 Beta2】【软总线】已组网，一端切换网络再切回，过程中组网未下线(无上下线回调)  |

L2 issue列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[I4312A](https://gitee.com/open_harmony/dashboard?issue_id=I4312A)|【2.2 Beta2】【软总线】已组网，断1端网络后，自组网失败(GetAllNodeDeviceInfo返回null) |
|[I43WIJ](https://gitee.com/open_harmony/dashboard?issue_id=I43WIJ)|【2.2 Beta2】【软总线】已组网，一端切换网络再切回，过程中组网未下线(无上下线回调)|
|[I43KLC](https://gitee.com/open_harmony/dashboard?issue_id=I43KLC)|【2.2 Beta2】【软总线】注册节点状态监听，设备上线，设备再离线，offline回调调用了2次|
|[I43118](https://gitee.com/open_harmony/dashboard?issue_id=I43118)|【2.2 Beta2】【软总线】已组网，重启设备配网后，自组网不成功|

# OpenHarmony 3.0.0.3 版本转测试信息：

| **转测试版本号：OpenHarmony 3.0.0.3                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代三第三轮测试，验收:|
|L0L1:应程序框架、多媒体等特性                                                |
|L2: 图形、Demo&应用子系统、驱动子系统、应用等特性    |
| **API变更：**：本次转测特性不涉及API变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-08-12**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.3/20210811_093832/version-Master_Version-OpenHarmony_3.0.0.3-20210811_093832-hispark_taurus.tar.gz   |
| hispark_taurus_linux版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.3/20210811_093621/version-Master_Version-OpenHarmony_3.0.0.3-20210811_093621-hispark_taurus_linux.tar.gz   |
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.3/20210811_093636/version-Master_Version-OpenHarmony_3.0.0.3-20210811_093636-hispark_pegasus.tar.gz   |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.3/20210811_093757/version-Master_Version-OpenHarmony_3.0.0.3-20210811_093757-hispark_aries.tar.gz  |
| **L2转测试时间：2021-08-12**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.3/20210811_094238/version-Master_Version-OpenHarmony_3.0.0.3-20210811_094238-L2_hi3516dv300.tar.gz  |

## OpenHarmony 3.0.0.3 版本特性清单：

L0L1 需求列表：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1   | [I3XCB5](https://gitee.com/openharmony/appexecfwk_appexecfwk_lite/issues/I3XCB5) | 【应用程序框架】按照应用粒度的存储资源使用统计       | testing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)            |
| 2   | [I3NK7D](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NK7D) | 【多媒体子系统】适配新南向接口                           | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 3   | [I3NM60](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM60) | 【多媒体子系统】相机metadata管理及相机静态能力查询        | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 4   | [I3NM6F](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM6F) | 【多媒体子系统】相机设备管理                            | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 5   | [I3NM73](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM73) | 【多媒体子系统】相机图像帧管理                           | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 6   | [I3NM8J](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM8J) | 【多媒体子系统】本地mp3播放支持                          | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 7   | [I3NMMU](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMMU) | 【多媒体子系统】编码视频流和音频流处理支持                 | testing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |

L2 需求列表：
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
|1|[I43G6T](https://gitee.com/open_harmony/dashboard?issue_id=I43G6T)|WM Client架构演进|Testing|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|2|[I43HMM](https://gitee.com/open_harmony/dashboard?issue_id=I43HMM)|WM Server架构演进|Testing|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|3|[I43I3O](https://gitee.com/open_harmony/dashboard?issue_id=I43I3O)|RQ-[图形子系统][vsync模块][vsync]vsync架构演进|Testing|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|4|[I44TNC](https://gitee.com/open_harmony/dashboard?issue_id=I44TNC)|RQ-[Demo&应用子系统][JSUI][Menu/Option]JSMenu|Testing|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|5|[I452UD](https://gitee.com/open_harmony/dashboard?issue_id=I452UD)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】工具栏|Testing|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|6|[I44TN0](https://gitee.com/open_harmony/dashboard?issue_id=I44TN0)|RQ-[Demo&应用子系统][JSUI][滑动条] slider|Testing|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|7|[I41HC0](https://gitee.com/open_harmony/dashboard?issue_id=I41HC0)|【驱动子系统】基于HDF驱动框架提供Display HDI的服务化|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|8|[I41LWL](https://gitee.com/open_harmony/dashboard?issue_id=I41LWL)|【SystemUI】状态栏最大最小化|Testing|SIG_SystemApplication|[@liuzhenyu2021](https://gitee.com/liuzhenyu2021)|

## 针对OpenHarmony 3.0.0.3版本解决的缺陷ISSUE列表：

L0L1 issue列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I42OMN](https://gitee.com/open_harmony/dashboard?issue_id=I42OMN) |【OpenHarmony】【20210726】【轻内核子系统】集成测试uname r v top a支持,help中缺少,chmod R不支持,help中有 |
| [I42SJL](https://gitee.com/open_harmony/dashboard?issue_id=I42SJL) |3516DV300图形子系统未在3分钟内完全启动，导致内存测试数据偏低 |		
| [I42TP2](https://gitee.com/open_harmony/dashboard?issue_id=I42TP2) |【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令kill -s 9 10杀10号进程不生效，kill  9 10可以，其他  |
| [I42UIE](https://gitee.com/open_harmony/dashboard?issue_id=I42UIE) |3516DV300包管理bundle_daemon内存数据超过转维前的版本60kb（6.5%）|
| [I42UIZ](https://gitee.com/open_harmony/dashboard?issue_id=I42UIZ) |3516DV300轻量级系统服务框架foundation内存数据超过转维前版本352kb（10%）| 
| [I42V8S](https://gitee.com/open_harmony/dashboard?issue_id=I42V8S) |【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox命令cp文件到不存在的目录，没有报错，并且在cp的当前目录下生成了一个名为目的目录的文件|
| [I430Z5](https://gitee.com/open_harmony/dashboard?issue_id=I430Z5) |【startup_standard】【master】L2-Beta2版本测试恢复出厂和清楚用户数据的api测试失败|


# OpenHarmony 3.0.0.2 版本转测试信息：

| **转测试版本号：OpenHarmony 3.0.0.2                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代三第一轮测试，验收:|
|L0L1:分布式调度                                                |
|L2: Demo&应用子系统、驱动子系统   |
| **API变更：**：本次转测特性不涉及API变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-08-04**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.2/20210804_161420/version-Master_Version-OpenHarmony_3.0.0.2-20210804_161420-hispark_taurus.tar.gz |
| hispark_taurus_linux版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.2/20210804_154143/version-Master_Version-OpenHarmony_3.0.0.2-20210804_154143-hispark_taurus_linux.tar.gz   |
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.2/20210804_160829/version-Master_Version-OpenHarmony_3.0.0.2-20210804_160829-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.2/20210804_161041/version-Master_Version-OpenHarmony_3.0.0.2-20210804_161041-hispark_aries.tar.gz     |
| **L2转测试时间：2021-08-04**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_3.0.0.2/20210804_161930/version-Master_Version-OpenHarmony_3.0.0.2-20210804_161930-L2_hi3516dv300.tar.gz   |

## OpenHarmony 3.0.0.2 版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L0L1 需求列表
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3QEVG](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3QEVG) | 【分布式调度】轻设备获取调用者APP的APPID并传输到富设备      | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)            |

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
|1|[I43W4L](https://gitee.com/open_harmony/dashboard?issue_id=I43W4L)|RQ-[Demo&应用子系统][JSUI][基础组件]JS基础组件|Testing|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|2|[I43XA7](https://gitee.com/open_harmony/dashboard?issue_id=I43XA7)|RQ-[Demo&应用子系统][JSUI][图表组件]chart|Testing|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|3|[I43W8L](https://gitee.com/open_harmony/dashboard?issue_id=I43W8L)|RQ-[Demo&应用子系统][JSUI][滑动选择器组件] picker|Testing|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|4|[I41HBB](https://gitee.com/open_harmony/dashboard?issue_id=I41HBB)|【驱动子系统】基于HDF驱动框架提供mouse驱动能力|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|

## 针对OpenHarmony 3.0.0.2版本解决的缺陷ISSUE列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I420PQ](https://gitee.com/openharmony/kernel_liteos_m/issues/I420PQ) | 【openHarmony】【2.3.0.3】【轻内核子系统】集成测试/kernel/arch/arm/arm9/gcc下的代码存在函数冲突 |
| [I41PQT](https://gitee.com/openharmony/third_party_musl/issues/I41PQT) | 【OpenHarmony】【2.3.0.3】【轻内核子系统】集成测试linux内核的L1设备不支持sched_setscheduler |
| [I40QOM](https://gitee.com/openharmony/kernel_liteos_a/issues/I40QOM) | 【OpenHarmony】【20210701】【轻内核子系统】集成测试testBarrierAlwaysWait在执行时会挂住，不往下执行 |
| [I42G3N](https://gitee.com/openharmony/kernel_liteos_a/issues/I42G3N) | 【OpenHarmony】【2.3_Beta】【轻内核子系统】集成测试pread函数返回值与之前版本不一致|
| [I40YD4](https://gitee.com/openharmony/kernel_liteos_a/issues/I40YD4) | 【OpenHarmony】【2.3.0.2】【轻内核子系统】集成测试benchmark测试用例执行命令./lat_fs /test_root/kernel|
| [I3ZQDA](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ZQDA) |【OpenHarmony】【2.3.0.1】【轻内核子系统】集成测试关于在mq_open失败后，会占用消息队列符，最终导致xml文件打不开|
| [I3M12H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3M12H) |【OpenHarmony】【20210419】【轻内核子系统】集成测试发送两个不同的信号，sigwait第二次等到的仍是第一个信号|
| [I42OHU](https://gitee.com/openharmony/third_party_toybox/issues/I42OHU) |【OpenHarmony】【20210726】【轻内核子系统】集成测试每日构建20210726版本toybox umount失败|
| [I42V8S](https://gitee.com/openharmony/third_party_toybox/issues/I42V8S) |【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox命令cp文件到不存在的目录，没有报错，并且在cp的当前目录下生成了一个名为...|
| [I42V89](https://gitee.com/openharmony/third_party_toybox/issues/I42V89) |【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令chmod修改文件权限后查出与预期不一致以及nfs挂载目录下的文件权...|
| [I42TTN](https://gitee.com/openharmony/third_party_toybox/issues/I42TTN) |【OpenHarmony】【1.1.541】【轻内核子系统】集成测试toybox 命令rmdir删除mount路径下的mkdir的子目录失败，rm -r同...|
| [I42OOU](https://gitee.com/openharmony/third_party_toybox/issues/I42OOU) |【OpenHarmony】【20210726】【轻内核子系统】集成测试toybox ls -l查看自己创建的文件目录大小时间日期以及total统计不正确|
| [I42OMN](https://gitee.com/openharmony/third_party_toybox/issues/I42OMN) |【OpenHarmony】【20210726】【轻内核子系统】集成测试uname r v top a支持,help中缺少,chmod R不支持,help中有|
| [I41U0R](https://gitee.com/openharmony/kernel_liteos_a/issues/I41U0R) |【openHarmony】【2.3.0.3】【轻内核子系统】集成测试nanosleep函数实现存在缺陷|
| [I41U0R](https://gitee.com/openharmony/kernel_liteos_a/issues/I41U0R) |【openHarmony】【2.3.0.3】【轻内核子系统】集成测试 在执行ActsMemApiTest.bin脚本，出现大量多余日志|
| [I42ZO7](https://gitee.com/openharmony/startup_init_lite/issues/I42ZO7) |/etc/passwd里面存在UID一样的用户账号，与规范要求冲突|

# OpenHarmony 3.0.0.1 版本转测试信息：

| **转测试版本号：OpenHarmony 3.0.0.1                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代三第一轮测试，验收:分布式调度特性|
|L2:事件通知、软总线、DEMO&应用、语言编译运行时、账号、用户程序框架、ACE、分布式文件、驱动等子系统|
| **API变更：**：本次转测特性不涉及API变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-07-29**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.6/20210803_091007/version-Master_Version-OpenHarmony_2.3.0.6-20210803_091007-hispark_taurus.tar.gz  z|
| hispark_taurus_linux版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.6/20210803_091007/version-Master_Version-OpenHarmony_2.3.0.6-20210803_091007-hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.6/20210803_090712/version-Master_Version-OpenHarmony_2.3.0.6-20210803_090712-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.6/20210803_090827/version-Master_Version-OpenHarmony_2.3.0.6-20210803_090827-hispark_aries.tar.gz  |
| **L2转测试时间：2021-07-29**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.6/20210729_092257/version-Master_Version-OpenHarmony_2.3.0.6-20210729_092257-L2_hi3516dv300.tar.gz   |

## OpenHarmony 3.0.0.1 版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L0/L1需求列表：
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3QEVG](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3QEVG) | 【分布式调度】轻设备获取调用者APP的APPID并传输到富设备      | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)            |

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1 | [I40PAV](https://gitee.com/open_harmony/dashboard?issue_id=I40PAV) | 发布开启一个有页面的Ability的WantAgent通知 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 2 | [I40PAW](https://gitee.com/open_harmony/dashboard?issue_id=I40PAW) | 通知删除接口 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 3 | [I40PAX](https://gitee.com/open_harmony/dashboard?issue_id=I40PAX) | 查看Active通知内容和Active通知个数的接口 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 4 | [I40PAY](https://gitee.com/open_harmony/dashboard?issue_id=I40PAY) | 通知取消订阅 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 5 | [I40PAZ](https://gitee.com/open_harmony/dashboard?issue_id=I40PAZ) | 通知订阅 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 6 | [I426IT](https://gitee.com/open_harmony/dashboard?issue_id=I426IT) | 【组网】组网单框架FWK | Testing | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 7 | [I426IM](https://gitee.com/open_harmony/dashboard?issue_id=I426IM) | 【组网】组网框架构建：安全 | Testing | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 8 | [I426IQ](https://gitee.com/open_harmony/dashboard?issue_id=I426IQ) | 【组网】节点信息管理 | Testing | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 9 | [I3NIMY](https://gitee.com/open_harmony/dashboard?issue_id=I3NIMY) | 【连接】BR/EDR模块管理 | Testing | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 10 | [I426J0](https://gitee.com/open_harmony/dashboard?issue_id=I426J0) | 【传输】通道管理 | Testing | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 11 | [I3NIZD](https://gitee.com/open_harmony/dashboard?issue_id=I3NIZD) | 【连接】连接策略的定义与管理 | Testing | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 12 | [I426IW](https://gitee.com/open_harmony/dashboard?issue_id=I426IW) | 【连接】连接状态机功能实现 | Testing | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 13 | [I42UO1](https://gitee.com/open_harmony/dashboard?issue_id=I42UO1) | RQ-[Demo&应用子系统][JSUI][容器组件]JS堆叠容器（stack） | Testing | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 14 | [I42X0C](https://gitee.com/open_harmony/dashboard?issue_id=I42X0C) | RQ-[Demo&应用子系统][JSUI][容器组件]JS步骤导航器（stepper） | Testing | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 15 | [I42WY6](https://gitee.com/open_harmony/dashboard?issue_id=I42WY6) | RQ-[Demo&应用子系统][JSUI][容器组件]JS滑动容器（swiper） | Testing | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 16 | [I42UNK](https://gitee.com/open_harmony/dashboard?issue_id=I42UNK) | RQ-[Demo&应用子系统][JSUI][容器组件]JS页签容器（tabs） | Testing | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 17 | [I42S96](https://gitee.com/open_harmony/dashboard?issue_id=I42S96) | RQ-[Demo&应用子系统][数据][HarmonyOS]融合搜索 | Testing | SIG_SystemApplication | [@guojin26](https://gitee.com/guojin26) |
| 18 | [I40PB6](https://gitee.com/open_harmony/dashboard?issue_id=I40PB6) | 应用侧增加slot | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 19 | [I40PB7](https://gitee.com/open_harmony/dashboard?issue_id=I40PB7) | 应用侧删除slot | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 20 | [I42WA2](https://gitee.com/open_harmony/dashboard?issue_id=I42WA2) | L2 提供 OHOS LLVM编译 | Testing | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 21 | [I3U4DP](https://gitee.com/open_harmony/dashboard?issue_id=I3U4DP) | musl侵入式修改分离 | Testing | SIG_CompileRuntime | [@caoruihong](https://gitee.com/caoruihong) |
| 22 | [I42WDD](https://gitee.com/open_harmony/dashboard?issue_id=I42WDD) | L2 musl c库支持 | Testing | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 23 | [I4014F](https://gitee.com/open_harmony/dashboard?issue_id=I4014F) | 【帐号子系统】JS API交付，开源+小程序 | Testing | SIG_BasicSoftwareService | [@verystone](https://gitee.com/verystone) |
| 24 | [I436VH](https://gitee.com/open_harmony/dashboard?issue_id=I436VH) | 创建串行任务分发器，使用串行任务分发器执行任务 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 25 | [I436VI](https://gitee.com/open_harmony/dashboard?issue_id=I436VI) | 创建专有任务分发器，使用专有任务分发器执行任务 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 26 | [I436VJ](https://gitee.com/open_harmony/dashboard?issue_id=I436VJ) | 创建全局并发任务分发器，使用全局并发任务分发器执行任务 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 27 | [I436VK](https://gitee.com/open_harmony/dashboard?issue_id=I436VK) | 创建并发任务分发器，使用并发任务分发器执行任务 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 28 | [I436VL](https://gitee.com/open_harmony/dashboard?issue_id=I436VL) | ces部件化改造 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 29 | [I436VM](https://gitee.com/open_harmony/dashboard?issue_id=I436VM) | ans部件化改造 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 30 | [I436VX](https://gitee.com/open_harmony/dashboard?issue_id=I436VX) | 提供分布式的回调Native接口 | Testing | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 31 | [I436N0](https://gitee.com/open_harmony/dashboard?issue_id=I436N0) | 支持应用包信息分布式存储能力 | Testing | SIG_ApplicationFramework | [@fuzhangHW](https://gitee.com/fuzhangHW) |
| 32 | [I4312I](https://gitee.com/open_harmony/dashboard?issue_id=I4312I) | 支持全新开发范式 | Testing | SIG_ApplicationFramework | [@zhanghaibo0](https://gitee.com/zhanghaibo0) |
| 33 | [I4313W](https://gitee.com/open_harmony/dashboard?issue_id=I4313W) | 【分布式文件子系统】（需求）ext4&f2fs拍包工具 | Testing | SIG_DataManagement | [@panqinxu](https://gitee.com/panqinxu) |
| 34 | [I41H57](https://gitee.com/open_harmony/dashboard?issue_id=I41H57) | 【驱动子系统】基于HDF驱动框架提供ADC平台总线驱动 | Testing | SIG_DriverFramework | [@zianed](https://gitee.com/zianed) |


# OpenHarmony 2.2 Beta2 版本转测试信息：

| **转测试版本号：OpenHarmony 2.2 Beta2                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第四轮测试，验收:|
|L2:应用子系统、全球化、多媒体、文件系统、分布式硬件、电源、HDF驱动等 |
| **API变更：**：本次转测特性L2 API有变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L2转测试时间：2021-07-28**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.2_Beta2/20210728_100015/version-Master_Version-OpenHarmony_2.2_Beta2-20210728_100015-L2_hi3516dv300.tar.gz  |

## OpenHarmony 2.2 Beta2 版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
|1|[I3XLZR](https://gitee.com/open_harmony/dashboard?issue_id=I3XLZR)|AudioService音频服务|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|2|[I3XM04](https://gitee.com/open_harmony/dashboard?issue_id=I3XM04)|Audio音频管理模块及API|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|3|[I3XM2C](https://gitee.com/open_harmony/dashboard?issue_id=I3XM2C)|CameraService 相机服务|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|4|[I3XM1U](https://gitee.com/open_harmony/dashboard?issue_id=I3XM1U)|Camera相机处理模块及API|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|5|[I3XM34](https://gitee.com/open_harmony/dashboard?issue_id=I3XM34)|MediaService播放录制服务|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|6|[I3XM2V](https://gitee.com/open_harmony/dashboard?issue_id=I3XM2V)|Media媒体处理模块及API|Testing|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|7|[I41GOS ](https://gitee.com/open_harmony/dashboard?issue_id=I41GOS)|【分布式文件子系统】（需求）基于JS语言实现system.file接口|Testing|SIG_DataManagement|[@panqinxu](https://gitee.com/panqinxu)|
|8|[I426IN](https://gitee.com/open_harmony/dashboard?issue_id=I426IN)|【组网】自组网管理|Testing|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|9|[I40NBW](https://gitee.com/open_harmony/dashboard?issue_id=I40NBW)|WLAN设置项|Testing|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|10|[I400ZM](https://gitee.com/open_harmony/dashboard?issue_id=I400ZM)|【应用子系统】【Launcher】桌面设置界面UX优化，Grid布局桌面支持图标拖动|Testing|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|11|[I41J7Q](https://gitee.com/open_harmony/dashboard?issue_id=I41J7Q)|支持Video组件|Testing|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|12|[I41JBF](https://gitee.com/open_harmony/dashboard?issue_id=I41JBF)|支持Camera组件|Testing|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|13|[I41JG4](https://gitee.com/open_harmony/dashboard?issue_id=I41JG4)|支持JS与NAPI混合开发接口|Testing|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|14|[I3ZRBA](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBA)|提供系统电源状态机管理能力|Testing|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|15|[I3ZRBV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBV)|提供休眠运行锁（RunningLock）管理能力|Testing|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|16|[I3ZRCV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRCV)|提供休眠、唤醒流程管理及实现|Testing|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|17|[I3WHJS](https://gitee.com/open_harmony/dashboard?issue_id=I3WHJS)|基于HDF驱动框架提供马达驱动程序适配|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|18|[I3ZRA7](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRA7)|基于HDF驱动框架提供加速度传感器驱动程序适配|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|19|[I41HBJ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBJ)|【驱动子系统】提供Audio HDI接口实现|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|20|[I41HBK](https://gitee.com/open_harmony/dashboard?issue_id=I41HBK)|【驱动子系统】Audio 驱动框架用户态接口库|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|21|[I41HBM](https://gitee.com/open_harmony/dashboard?issue_id=I41HBM)|【驱动子系统】提供支持MPI接口的用户态接口库|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|22|[I41HBN](https://gitee.com/open_harmony/dashboard?issue_id=I41HBN)|【驱动子系统】HDI接口支持跨进程通信|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|23|[I41HBH](https://gitee.com/open_harmony/dashboard?issue_id=I41HBH)|【驱动子系统】基于HDF驱动框架提供WIFI支持HDI接口能力|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|24|[I41HBG](https://gitee.com/open_harmony/dashboard?issue_id=I41HBG)|【驱动子系统】基于HDF驱动框架提供WIFI支持P2P驱动能力|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|25|[I41HBI](https://gitee.com/open_harmony/dashboard?issue_id=I41HBI)|【驱动子系统】提供Audio Driver Model驱动模型框架|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|26|[I41HBA](https://gitee.com/open_harmony/dashboard?issue_id=I41HBA)|【驱动子系统】基于HDF驱动框架提供keyboard驱动能力|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|27|[I41HBZ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBZ)|【驱动子系统】基于HDF框架提供USB device DDK|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|28|[I41HBU](https://gitee.com/open_harmony/dashboard?issue_id=I41HBU)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层BufferManager|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|29|[I41HBV](https://gitee.com/open_harmony/dashboard?issue_id=I41HBV)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层utils通用组件(thread、event、watchdog)r|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|30|[I41HBX](https://gitee.com/open_harmony/dashboard?issue_id=I41HBX)|【驱动子系统】基于HDF驱动框架提供Camera驱动多平台扩展平台适配|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|31|[I41HBY](https://gitee.com/open_harmony/dashboard?issue_id=I41HBY)|【驱动子系统】基于HDF框架提供USB host DDK|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|32|[I41HBP](https://gitee.com/open_harmony/dashboard?issue_id=I41HBP)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备控制（CameraDevice）|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|33|[I41HBQ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBQ)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Image流控制（StreamOperator）|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|34|[I41HBR](https://gitee.com/open_harmony/dashboard?issue_id=I41HBR)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera HDI接口|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|35|[I41HBS](https://gitee.com/open_harmony/dashboard?issue_id=I41HBS)|【驱动子系统】基于HDF驱动框架提供Pipeline管理 |Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|36|[I41HBT](https://gitee.com/open_harmony/dashboard?issue_id=I41HBT)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层设备管理DeviceManager|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|37|[I41HBO](https://gitee.com/open_harmony/dashboard?issue_id=I41HBO)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备管理（CameraHost）|Testing|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|38|[I3ZVIO](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVIO)|Hi3516DV300开发板上，提供账号无关的设备认证能力|Testing|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|39|[I40PB8](https://gitee.com/open_harmony/dashboard?issue_id=I40PB8)|应用侧取消本地所有通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|40|[I40PB0](https://gitee.com/open_harmony/dashboard?issue_id=I40PB0)|应用侧发布本地多行类型通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|41|[I40PB1](https://gitee.com/open_harmony/dashboard?issue_id=I40PB1)|应用侧发布本地长文本通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|42|[I40PB2](https://gitee.com/open_harmony/dashboard?issue_id=I40PB2)|应用侧发布本地内容资讯类型的普通文本通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|43|[I40PB3](https://gitee.com/open_harmony/dashboard?issue_id=I40PB3)|应用侧发布本地其他类型的普通文本通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|44|[I40PB4](https://gitee.com/open_harmony/dashboard?issue_id=I40PB4)|应用侧发布本地服务提醒类型的普通文本通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|45|[I40PB5](https://gitee.com/open_harmony/dashboard?issue_id=I40PB5)|应用侧发布本地社交通讯类型的普通文本通知|Testing|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|46|[I3XY72](https://gitee.com/open_harmony/dashboard?issue_id=I3XY72)|c++与 js时间\日期和数字国际化能力构建|Testing|SIG_ApplicationFramework|[@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat)|
|47|[I42IMT](https://gitee.com/open_harmony/dashboard?issue_id=I42IMT)|RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式计算器|Testing|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|48|[I42IKN](https://gitee.com/open_harmony/dashboard?issue_id=I42IKN)|RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式音乐播放器|Testing|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|49|[I41JB1](https://gitee.com/openharmony/applications_photos/issues/I41JB1)|【应用子系统】【图库】图库基础功能-大图浏览|Testing|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|50|[I41J2Y](https://gitee.com/openharmony/applications_photos/issues/I41J2Y)|【应用子系统】【图库】图库基础功能-相册管理|Testing|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|51|[I41JBB](https://gitee.com/openharmony/applications_photos/issues/I41JBB)|【应用子系统】【图库】图库基础功能-Toolbar操作|Testing|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|

# OpenHarmony 2.3 Beta 版本转测试信息：

| **转测试版本号：OpenHarmony 2.3 Beta                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第四轮测试，验收:|
|L0L1: |
|L2:应用子系统、全球化 |
| **API变更：**：本次转测特性L2 API有变更，具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-07-23**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3_Beta/20210721_011042/version-Master_Version-OpenHarmony_2.3_Beta-20210721_011042-hispark_taurus.tar.gz|
| hispark_taurus_linux版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3_Beta/20210721_011017/version-Master_Version-OpenHarmony_2.3_Beta-20210721_011017-hispark_taurus_linux.tar.gz    |
| hispark_pegasus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3_Beta/20210721_010513/version-Master_Version-OpenHarmony_2.3_Beta-20210721_010513-hispark_pegasus.tar.gz |
| hispark_aries版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3_Beta/20210721_011130/version-Master_Version-OpenHarmony_2.3_Beta-20210721_011130-hispark_aries.tar.gz  |
| **L2转测试时间：2021-07-23**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3_Beta/20210723_085435/version-Master_Version-OpenHarmony_2.3_Beta-20210723_085435-L2_hi3516dv300.tar.gz  |

## 针对OpenHarmony 2.3 Beta版本解决的缺陷ISSUE列表：

L0L1 issue问题单列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I3I31W](	https://gitee.com/open_harmony/dashboard?issue_id=I3I31W) | 【OpenHarmony】【20210409】【轻内核子系统】集成测试ActsNFSTest.bin会引起内核crash |
| [I3IE6L](	https://gitee.com/open_harmony/dashboard?issue_id=I3IE6L) | 需求test |
| [I3ILIK](	https://gitee.com/open_harmony/dashboard?issue_id=I3ILIK) | 	音视频播放时，设置audio source 或者 设置 player source出现crash |
| [I3IPB8](	https://gitee.com/open_harmony/dashboard?issue_id=I3IPB8) | 	【OpenHarmony】【20210414】【轻内核子系统】集成测试osThreadNew函数attr为NULL时创建线程失败 |
| [I3IPQ3](	https://gitee.com/open_harmony/dashboard?issue_id=I3IPQ3) | 	DAC测试用例中rmdir操作失败 |
| [I3J2O3](	https://gitee.com/open_harmony/dashboard?issue_id=I3J2O3) | 	3516 执行umount指令概率出现栈溢出 |
| [I3J2XE](	https://gitee.com/open_harmony/dashboard?issue_id=I3J2XE) | 	在jffs2上umount文件夹后，再删除该文件夹，概率出现内核崩溃 |
| [I3N06L](	https://gitee.com/open_harmony/dashboard?issue_id=I3N06L) | 	【OpenHarmony】【20210420】【轻内核子系统】集成测试FsStatTest.cpp在3518 master跑不过，但是在release上可以跑通 |
| [I3N1E4](	https://gitee.com/open_harmony/dashboard?issue_id=I3N1E4) | 	【OpenHarmony】【20210420】【轻内核子系统】集成测试：IO模块在相关接口的测试中会导致设备crash |
| [I3OSYA](	https://gitee.com/open_harmony/dashboard?issue_id=I3OSYA) | 【内核子系统集成测试】无法单独编译内核组件 |
| [I3QQA9](	https://gitee.com/open_harmony/dashboard?issue_id=I3QQA9) | 	【OpenHarmony】【20210511】【轻内核子系统】集成测试pthread_cancel发送的信号可能会对别的用例中父进程对子进程中发送信号产生影响 |
| [I3R3ZR](	https://gitee.com/open_harmony/dashboard?issue_id=I3R3ZR) | 	【OpenHarmony】【20210511】【轻内核子系统】集成测试NET模块的用例testDnCompExpandAbnormal Faield |
| [I3R61Y](	https://gitee.com/open_harmony/dashboard?issue_id=I3R61Y) | 	优化L1 测试执行时长 |
| [I3RCQZ](	https://gitee.com/open_harmony/dashboard?issue_id=I3RCQZ) | 	【OpenHarmony】【20210514】【轻内核子系统】集成测试：usleep精度测试中当usleep(100)，usleep(1000)测试概率性失败 |
| [I3RLSJ](	https://gitee.com/open_harmony/dashboard?issue_id=I3RLSJ) | 	ActsUiInterfaceTest测试套在3516master分支出现系统崩溃 |
| [I3S6IZ](	https://gitee.com/open_harmony/dashboard?issue_id=I3S6IZ) | 	支持hb -t notest不编译全部的测试用例，提高开发者编译速度 |
| [I3SNG3](	https://gitee.com/open_harmony/dashboard?issue_id=I3SNG3) | 	【OpenHarmony】【20210521】【轻内核子系统】集成测试：clock_nanosleep异常测试（不支持的clock_id测试）失败 |
| [I3SNS1](	https://gitee.com/open_harmony/dashboard?issue_id=I3SNS1) | 	3518和3516release分支media模块 ActsAudioPlayerTest 用例失败 |
| [I3SYGZ](	https://gitee.com/open_harmony/dashboard?issue_id=I3SYGZ) | 	aafwk_lite/ability_posix测试套ldflags项增加-ldl选项，提交master |
| [I3TDBK](	https://gitee.com/open_harmony/dashboard?issue_id=I3TDBK) | 	3516release分支 ActsVFATCapabilityTest#CapabilityTestSuite#CapabilityTest2300用例失败 |
| [I3TH1U](	https://gitee.com/open_harmony/dashboard?issue_id=I3TH1U) | 	 轻量ace tdd门禁用例偶现崩溃 |
| [I3TYOA](	https://gitee.com/open_harmony/dashboard?issue_id=I3TYOA) | 	aafwk_lite/ability_posix测试套ldflags项增加-ldl选项，提交release |
| [I3TYVR](	https://gitee.com/open_harmony/dashboard?issue_id=I3TYVR) | 	xts_acts仓下，图片没有正常显示 |
| [I3U959](	https://gitee.com/open_harmony/dashboard?issue_id=I3U959) | 	player_sample无法播放aac音频文件 |
| [I3U95A](	https://gitee.com/open_harmony/dashboard?issue_id=I3U95A) | 	player_sample无法播放MP4视频 |
| [I3UCY2](	https://gitee.com/open_harmony/dashboard?issue_id=I3UCY2) | 	libwpa.so存在漏洞CVE-2021-30004未修复 |
| [I3UOOX](	https://gitee.com/open_harmony/dashboard?issue_id=I3UOOX) | 	3516master分支用例概率失败 ActsVFATCapabilityTest/CapabilityTestSuite/CapabilityTest2200  |
| [I3UOZH](	https://gitee.com/open_harmony/dashboard?issue_id=I3UOZH) | 	 3516master用例概率失败ActsAiEngineTest/AieClientPrepareFunctionTest/ |
| [I3V0RP](	https://gitee.com/open_harmony/dashboard?issue_id=I3V0RP) | 	3516DV300开机后整机内存占用超标 |
| [I3V0V3](	https://gitee.com/open_harmony/dashboard?issue_id=I3V0V3) | 	3518EV300开机后整机内存占用超标 |
| [I3V91E](	https://gitee.com/open_harmony/dashboard?issue_id=I3V91E) | 	horizonprogress用例重复执行崩溃 |
| [I3VA5D](	https://gitee.com/open_harmony/dashboard?issue_id=I3VA5D) | 	3861 XTS压测CmsisTaskFuncTestSuite必现13条用例失败 |
| [I3VD3M](	https://gitee.com/open_harmony/dashboard?issue_id=I3VD3M) | 	L1_3518_TDD graphic_test_utils_door.bin模块用例异常 |
| [I3VDC1](	https://gitee.com/open_harmony/dashboard?issue_id=I3VDC1) | 	L1_3518 ActsMediaRecorderTest#ActsMediaRecorderNDKTest#Test_GetSurface01用例fail |
| [I3VEF8](	https://gitee.com/open_harmony/dashboard?issue_id=I3VEF8) | 	ActsNetTest.bin在3516 XTS压测中crash |
| [I3VJEI](	https://gitee.com/open_harmony/dashboard?issue_id=I3VJEI) | 	js_frameworks_tdd_door.bin在测试框架中执行无法获取结果 |
| [I3ZG62](	https://gitee.com/open_harmony/dashboard?issue_id=I3ZG62) | 	L1_XTS_3518&3516 ActsSamgrTest模块 LiteIPCClientTest 测试套6条用例必现失败 |
| [I40QOM](	https://gitee.com/open_harmony/dashboard?issue_id=I40QOM) | 	【OpenHarmony】【20210701】【轻内核子系统】集成测试testBarrierAlwaysWait在执行时会挂住，不往下执行 |
| [I3D49E](	https://gitee.com/open_harmony/dashboard?issue_id=I3D49E) | 	uboot的路径不对 |
| [I3EH4E](	https://gitee.com/open_harmony/dashboard?issue_id=I3EH4E) | 【OpenHarmony】【master】【流水线问题】高概率出现：uname无响应，然后执行reset也无响应 |
| [I3EQJA](	https://gitee.com/open_harmony/dashboard?issue_id=I3EQJA) | 	【OpenHarmony】【20210402】【轻内核子系统】集成测试文件系统：cat /proc/mounts功能不可用 |
| [I3EQRC](	https://gitee.com/open_harmony/dashboard?issue_id=I3EQRC) | 	【OpenHarmony】【20210402】【轻内核子系统】集成测试磁盘文件映射延迟测试：并发3个测试进程，系统crash |
| [I3HVL0](	https://gitee.com/open_harmony/dashboard?issue_id=I3HVL0) | 	3861编译失败，报错[OHOS ERROR] Fatal error: invalid -march= option: `rv32imac' |
| [I3W0NS](	https://gitee.com/open_harmony/dashboard?issue_id=I3W0NS) | 	hap包第一次卸载失败 |
| [I3YWSQ](	https://gitee.com/open_harmony/dashboard?issue_id=I3YWSQ) | 	【OpenHarmony 2.3.0.1】【驱动子系统】L1 l单板上进行sensor驱动压力测试，概率性出现sensor数据无上报现象 |

## OpenHarmony 2.3 Beta 版本特性清单：	

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1 | [I41LYF](https://gitee.com/open_harmony/dashboard?issue_id=I41LYF) | 导航栏支持显示BACK、HOME、RECENT菜单 | Testing | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 2 | [I41LSC](https://gitee.com/open_harmony/dashboard?issue_id=I41LSC) | 【SystemUI】SystemUI权限系统弹窗能力 | Testing | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 3 | [I3XY72](https://gitee.com/open_harmony/dashboard?issue_id=I3XY72) | c++与 js时间\日期和数字国际化能力构建 | Testing | SIG_ApplicationFramework | [@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat) |

# OpenHarmony 2.3.0.3 版本转测试信息：

| **转测试版本号：OpenHarmony 2.3.0.3                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第三轮测试，验收:|
|L0L1:DFX子系统、轻内核子系统、电源管理等特性 |
|L2:Demo&应用子系统、分布式数据管理子系统、应用子系统 |
| **API变更：**：本次转测特性涉及电源管理API变更（新增），均通过法务评审，L2本次不涉及。具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-07-16**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210716_112829/version-Master_Version-OpenHarmony_2.3.0.3-20210716_112829-hispark_taurus.tar.gz|
| hispark_taurus_linux版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210716_112547/version-Master_Version-OpenHarmony_2.3.0.3-20210716_112547-hispark_taurus_linux.tar.gz |
| hispark_pegasus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210716_112819/version-Master_Version-OpenHarmony_2.3.0.3-20210716_112819-hispark_pegasus.tar.gz |
| hispark_aries版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210716_112700/version-Master_Version-OpenHarmony_2.3.0.3-20210716_112700-hispark_aries.tar.gz |
| **L2转测试时间：2021-07-16**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210714_011351/version-Master_Version-OpenHarmony_2.3.0.3-20210714_011351-L2_hi3516dv300.tar.gz|


## 针对OpenHarmony 2.3.0.3版本解决的缺陷ISSUE列表：

L0L1 issue问题单列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I3TS1Y](https://gitee.com/openharmony/kernel_liteos_a/issues/I3TS1Y) | 压力场景下文件相关胡VnodeAlloc资源耗尽                             |
| [I3TXT8](https://gitee.com/openharmony/startup_init_lite/issues/I3TXT8) | 孤儿进程无法回收，压力场景下TCB资源耗尽                                               |
| [I3UWXI](https://gitee.com/openharmony/applications_sample_wifi_iot/issues/I3UWXI) |libwap.so 存在已知一般漏洞： CVE-2021-30004，CVSS：5.3；漏洞发布日期：2021-04-02，不符合产品发布要求，需要解决。 |
| [I3SWY2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3SWY2) | 高概率出现KProcess进程挂死，质量不达标 |
| [I3YJRO](https://gitee.com/openharmony/kernel_liteos_m/issues/I3YJRO) | liteos-a內核模块可配置编译失败  |
| [I3YNWM](https://gitee.com/openharmony/kernel_liteos_a/issues/I3YNWM) | 文件系统维测增强功能在该版本有问题               |
| [I3VEOG](https://gitee.com/openharmony/kernel_liteos_a/issues/I3VEOG) | bin目录下没有mksh和toybox，导致已转测的toybox命令集和shell交互友好性提升无法测试 |

## OpenHarmony 2.3.0.3 版本特性清单：	

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L0L1需求列表：
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3NN88](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN88) | 【DFX子系统】【HiDumper】LiteOS_M系统信息dump工具 | testing | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 2    | [I3NN7D](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7D) | 【DFX子系统】【HiDumper】LiteOS_A系统信息dump工具 | testing | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 3    | [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强                             | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 4    | [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】L0支持轻量级shell框架和常用调测命令           | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 5    | [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】L0 LiteOS-M支持ARM9架构                     | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 6    | [I3NE8P](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NE8P) | 【电源管理】充放电状态查询接口                               | testing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 7    | [I3NIEJ)](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIEJ) | 【电源管理】电量查询接口                                     | testing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 8    | [I3NIFG](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFG) | 【电源管理】实现并提供低功耗模式                             | testing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 9    | [I3NIFR](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFR) | 【电源管理】提供低功耗模式统一API                            | testing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 10   | [I3NN7V](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7V) | 【DFX子系统】【BBoxDetector】LiteOS_A死机重启维测框架        | testing | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 11   | [I3NN9B](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN9B) | 【DFX子系统】【BBoxDetector】LiteOS_M死机重启维测框架        | testing | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
|	1	|	[I3ZN3M](https://gitee.com/open_harmony/dashboard?issue_id=I3ZN3M)	|	【分布式数据管理】鸿蒙单框架L2分布式数据管理开源	|	Testing	|	SIG_DataManagement	|	[@widecode](https://gitee.com/widecode)	|
|	2	|	[I40K12](https://gitee.com/open_harmony/dashboard?issue_id=I40K12)	|	【Samples】【JSUI】【容器组件】JS气泡（popup）	|	Testing	|	SIG_Samples	|	[@illybyy](https://gitee.com/illybyy)	|
|	3	|	[I40K1P](https://gitee.com/open_harmony/dashboard?issue_id=I40K1P)	|	【Samples】【JSUI】【容器组件】下拉刷新容器（refresh）	|	Testing	|	SIG_Samples	|	[@illybyy](https://gitee.com/illybyy)	|
|	4	|	[I40K2A](https://gitee.com/open_harmony/dashboard?issue_id=I40K2A)	|	【Samples】【数据】【HarmonyOS】轻量级偏好数据库	|	Testing	|	SIG_Samples	|	[@illybyy](https://gitee.com/illybyy)	|
|	5	|	[I40NBW](https://gitee.com/open_harmony/dashboard?issue_id=I40NBW)	|	【应用子系统】鸿蒙单框架L2系统应用-设置开源-WLAN	|	Testing	|	SIG_SysApplication	|	[@nicolaswang](https://gitee.com/nicolaswang)	|


# OpenHarmony 2.3.0.2 版本转测试信息：

| **转测试版本号：OpenHarmony 2.3.0.2                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第二轮测试，验收:|
|L0L1:轻图形、编译构建、全球化子系统特性 |
|L2:Demo&应用子系统、分布式数据管理子系统、电源管理子系统、驱动子系统特性 |
| **API变更：**：本次转测特性涉及全球化API变更（新增），均通过法务评审，L2本次不涉及。具体参见：https://gitee.com/openharmony-sig/oh-inner-release-management/blob/master/API_Change_Record/                  |
| **L0L1转测试时间：2021-07-08**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.2/20210707_092546/version-Master_Version-OpenHarmony_2.3.0.2-20210707_092546-hispark_taurus.tar.gz|
| hispark_taurus_linux版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.2/20210708_165611/version-Master_Version-OpenHarmony_2.3.0.2-20210708_165611-hispark_taurus_linux.tar.gz |
| hispark_pegasus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.2/20210707_092259/version-Master_Version-OpenHarmony_2.3.0.2-20210707_092259-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.2/20210707_092352/version-Master_Version-OpenHarmony_2.3.0.2-20210707_092352-hispark_aries.tar.gz|
| **L2转测试时间：2021-07-08**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Daily_Version/OpenHarmony_2.3.0.2/20210708_090935/version-Daily_Version-OpenHarmony_2.3.0.2-20210708_090935-L2_hi3516dv300.tar.gz|

## OpenHarmony 2.3.0.2 版本特性清单：	

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L0L1需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1    | [I3NCB9](https://gitee.com/openharmony/third_party_Linux_Kernel/issues/I3NCB9) | 【L1 Linux开源】编译器替换后的内核代码适配                   | Testing | SIG_Kernel           | [@zzzuo](https://gitee.com/zzzuo)                 |
| 2   | [I3NBVI](https://gitee.com/openharmony/build_lite/issues/I3NBVI) | 【L1 Linux开源】clang替换                                    | Testing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 3   | [I3NC8H](https://gitee.com/openharmony/build_lite/issues/I3NC8H) | 【L1 Linux开源】musl库替换                                   | Testing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 4    | [I3NCEF](https://gitee.com/openharmony/build_lite/issues/I3NCEF) | 【L1 Linux开源】工具集替换                                   | Testing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 5   | [I3NCF7](https://gitee.com/openharmony/build_lite/issues/I3NCF7) | 【L1 Linux开源】rootfs替换                                   | Testing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 6   | [I3NCG0](https://gitee.com/openharmony/build_lite/issues/I3NCG0) | 【L1 Linux开源】镜像制作工具替换                             | Testing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 7   | [I3NCGM](https://gitee.com/openharmony/build_lite/issues/I3NCGM) | 【L1 Linux开源】开源编译构建                                 | Testing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 8   | [I3NCCT](https://gitee.com/openharmony/drivers_adapter/issues/I3NCCT) | 【L1 Linux开源】编译器替换后的HDF适配                        | Testing | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)               |
| 9   | [I3N0LP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0LP?from=project-issue) | 【全球化子系统】构建自定义数据编译能力                       | Testing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 10   | [I3N0OP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0OP?from=project-issue) | 【全球化子系统】构建星期、单复数、数字开关国际化能力         | Testing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 11   | [I3NSY0](https://gitee.com/openharmony/graphic_ui/issues/I3NSY0) | 【轻量级图形】支持A4\A8、LUT8、TSC图片格式作为输入           | Testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 12   | [I3NT0R](https://gitee.com/openharmony/graphic_ui/issues/I3NT0R) | 【轻量级图形】支持多语言字体对齐                             | Testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 13   | [I3SNGO](https://gitee.com/openharmony/build_lite/issues/I3SNGO) | 【编译子系统】build_lite支持开源软件的通用patch框架          | Testing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1 | [I3ZDIF](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIF) | RQ-[Demo&应用子系统][JSUI]【通用】JS动画（动画样式、渐变样式、转场样式、自定义字体样式） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 2 | [I3ZDIG](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIG) | RQ-[Demo&应用子系统][JSUI]【通用】原子布局 | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 3 | [I3ZDIH](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIH) | RQ-[Demo&应用子系统][JSUI]【容器组件】新事件提醒（badge） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 4 | [I3ZDII](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDII) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义组件（CustomComponent） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 5 | [I3ZDIJ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIJ) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义布局（CustomLayout） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 6 | [I3ZDIK](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIK) | RQ-[Demo&应用子系统][JS UI]【HarmonyOS】FA卡片（JsFACard） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 7 | [I3ZDIL](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIL) | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入（MultiModeInput） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 8 | [I3ZDIM](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIM) | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入事件标准化（MultimodalEvent） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 9 | [I3ZDIN](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIN) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】Fraction | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 10 | [I3ZDIO](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIO) | RQ-[Demo&应用子系统][ServiceAbility]【HarmonyOS】前台服务（ForegroundService） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 11 | [I3ZDIP](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIP) | RQ-[Demo&应用子系统][Ability测试]【HarmonyOS】Ability的自动化测试（Delegator） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 12 | [I3ZDIQ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIQ) | RQ-[Demo&应用子系统][无障碍]【HarmonyOS】accessibility | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 13 | [I3ZDIR](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIR) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】AbilityForm | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 14 | [I3ZDIS](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIS) | RQ-[Demo&应用子系统][AI]【HarmonyOS】AI | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 15 | [I3ZDIT](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIT) | RQ-[Demo&应用子系统][媒体]【HarmonyOS】Audio | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 16 | [I3ZDIU](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIU) | RQ-[Demo&应用子系统][媒体]【HarmonyOS】AudioPlayer | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 17 | [I3ZDIW](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIW) | RQ-[Demo&应用子系统][设备]【HarmonyOS】BatteryInfo | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 18 | [I3ZDIX](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIX) | RQ-[Demo&应用子系统][设备]【HarmonyOS】指南针Compass | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 19 | [I3ZDIY](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIY) | RQ-[Demo&应用子系统][安全]【HarmonyOS】DataSecurity | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 20 | [I3ZDIZ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIZ) | RQ-[Demo&应用子系统][网络]【HarmonyOS】DistributedAbility | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 21 | [I3ZDJ0](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ0) | RQ-[Demo&应用子系统][通用]【HarmonyOS】DistributedCommonEvent | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 22 | [I3ZDJ1](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ1) | RQ-[Demo&应用子系统][数据]【HarmonyOS】DistributedPictures | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 23 | [I3ZDJ3](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ3) | RQ-[Demo&应用子系统][安全]【HarmonyOS】FaceRecognition | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 24 | [I3ZDJ4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ4) | RQ-[Demo&应用子系统][设备]【HarmonyOS】NFC | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 25 | [I3ZDJ5](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ5) | RQ-[Demo&应用子系统][数据]【HarmonyOS】关系型数据库 | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 26 | [I3ZDJ6](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ6) | RQ-[Demo&应用子系统][数据]【HarmonyOS】对象关系映射数据库 | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 27 | [I3ZRBA](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBA) | 提供系统电源状态机管理能力 | Testing | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 28 | [I3ZRBV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBV) | 提供休眠运行锁（RunningLock）管理能力 | Testing | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 29 | [I3ZRCV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRCV) | 提供休眠、唤醒流程管理及实现 | Testing | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 30 | [I3ZMUM](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMUM) | 【分布式数据管理子系统】【本地数据库】 轻量级数据库JS API交付，对标开源+小程序 | Testing | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 31 | [I3ZMW4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMW4) | 【分布式数据管理子系统】【本地数据库】提供RDB和PREFERENCES的能力 | Testing | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 32 | [I3ZMX5](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMX5) | 【分布式数据管理子系统】【本地数据库】 支持ResultSet滑动窗口能力 | Testing | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 33 | [I3YC8O](https://gitee.com/open_harmony/dashboard?issue_id=I3YC8O) | 【分布式数据管理】【分布式数据库】支持JS接口创建分布式数据库 | Testing | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 34 | [I3WHJS](https://gitee.com/open_harmony/dashboard?issue_id=I3WHJS) | 基于HDF驱动框架提供马达驱动程序适配 | Testing | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |
| 35 | [I3ZRA7](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRA7) | 基于HDF驱动框架提供加速度传感器驱动程序适配 | Testing | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |


# OpenHarmony 2.3.0.1 版本转测试信息：

| **转测试版本号：OpenHarmony 2.3.0.1                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第一轮测试，验收内核、DFX子系统、分布式调度、全球化子系统，轻图像子系统等特性 |
| **API变更：**：本次转测特性涉及启动子系统，全球化子系统，轻图形子系统的API变更，均通过法务评审                     |
| **转测试时间：2021-06-24**                                   |
| hispark_taurus版本：<br> hispark-taurus版本：http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.1/20210623_114632/version-Master_Version-OpenHarmony_2.3.0.1-20210623_114632-hispark_taurus.tar.gz
| hispark_pegasus版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.1/20210623_114013/version-Master_Version-OpenHarmony_2.3.0.1-20210623_114013-hispark_pegasus.tar.gz|
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.1/20210623_114314/version-Master_Version-OpenHarmony_2.3.0.1-20210623_114314-hispark_aries.tar.gz |
| **L2转测试时间：2021-06-25**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.1/20210625_090828/version-Master_Version-OpenHarmony_2.3.0.1-20210625_090828-L2_hi3516dv300.tar.gz |

## OpenHarmony 2.3.0.1版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统      | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 2    | [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】L0上对外提供统一的文件系统操作接口           | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 3    | [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】L0 补充120个POSIX接口                        | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 4    | [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器                           | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 5    | [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升                          | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 6    | [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集                             | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 7    | [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块                                | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 8    | [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理                                    | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 9    | [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块                                   | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 10   | [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强                             | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 11   | [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置                       | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 12   | [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配                   | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 13   | [I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】L0支持三方组件Mbedtls编译                    | testing  | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】L0支持三方组件curl编译                       | testing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15  | [I3NIME](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NIME) | 【启动恢复子系统】支持恢复出厂设置                           | testing  | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 16   | [I3NTBC](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTBC) | 【启动恢复子系统】L0/L1/L2接口优化                           | testing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 17   | [I3NN4H](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN4H) | 【DFX子系统】【HiLog】L0系统HiLog功能增强                    | testing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 18  | [I3NN53](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN53) | 【DFX子系统】【HiEvent】L0系统HiEvent功能增强                | testing  | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 19   | [I3ID9Q](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道             | testing  | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 20  | [I3ID9V](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9V) | 【分布式调度】轻量设备启动富设备上的Ability                  | testing  | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 21  | [I3I1V8](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1V8)         | 【全球化子系统】构建应用资源解析和加载机制                   | testing  | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 22  | [I3I1VJ](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1VJ) | 【全球化子系统】构建资源回溯机制                             | testing  | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 23   | [I3QE85](https://gitee.com/openharmony/drivers_framework/issues/I3QE85) | 【驱动子系统】L0支持HDF框架                                  | testing  | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 24   | [I3NSVQ](https://gitee.com/openharmony/graphic_ui/issues/I3NSVQ) | 【轻量级图形】DFX维测能力：UIKit支持显示控件轮廓             | testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 25   | [I3NSWY](https://gitee.com/openharmony/graphic_ui/issues/I3NSWY) | 【轻量级图形】ScrollView/List支持通过弧形进度条展示滑动进度  | testing  | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 26   | [I3NSZZ](https://gitee.com/openharmony/graphic_ui/issues/I3NSZZ) | 【轻量级图形】支持开关按钮/复选框/单选按钮动效               | testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 27   | [I3NSQ6](https://gitee.com/openharmony/graphic_ui/issues/I3NSQ6) | 【轻量级图形】UIKit支持点阵字体产品化解耦                    | testing  | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 28   | [I3NSZ1](https://gitee.com/openharmony/graphic_ui/issues/I3NSZ1) | 【轻量级图形】UI框架提供统一多后端框架支持多芯片平台         | testing  | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |

# OpenHarmony 2.2 beta1版本转测试信息：

| **转测试版本号：OpenHarmony 2.2 beta1                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代一beta1测试，验收分布式数据管理、轻图形子系统特性 |
| **API变更：**：本次转测特性涉及轻图形API变更                     |
| **转测试时间：2021-05-20**                                   |
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210521_142211/Master_Version-OpenHarmony_2.2_Beta1-20210521_142211-hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210521_142023/Master_Version-OpenHarmony_2.2_Beta1-20210521_142023-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210521_142154/Master_Version-OpenHarmony_2.2_Beta1-20210521_142154-hispark_aries.tar.gz |

## OpenHarmony 2.2 beta1版本特性清单：

 状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                  | status     | sig                  | owner                                   |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :------------------- | :-------------------------------------- |
| 1    | [I3ICFO](https://gitee.com/openharmony/utils_native_lite/issues/I3ICFO) | 【分布式数据管理】提供数据库内容的删除能力          | Testing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 2    | [I3ICH0](https://gitee.com/openharmony/utils_native_lite/issues/I3ICH0) | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | Testing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 3    | [I3ICG4](https://gitee.com/openharmony/utils_native_lite/issues/I3ICG4) | 【分布式数据管理】提供相关数据存储的原子操作能力    | Testing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 4    | [I3ICGH](https://gitee.com/openharmony/utils_native_lite/issues/I3ICGH) | 【分布式数据管理】提供二进制Value的写入读取能力     | Testing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 5    | [I3NSPB](https://gitee.com/openharmony/graphic_ui/issues/I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | Testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |
| 7    | [I3NSZH](https://gitee.com/openharmony/graphic_ui/issues/I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | Testing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |

# OpenHarmony 2.2.2版本转测试信息：

| **转测试版本号：OpenHarmony 2.2.2                  |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代一第二轮α测试，验收hilog增强特性、AI子系统特性 |
| **API变更：**：本次转测特性不涉及API变更                     |
| **转测试时间：2021-04-28**                                   |
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_release_2.2.2/2021-04-28_17-33-00/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_release_2.2.2/2021-04-28_17-32-27/hispark_pegasus.tar.gz |
| hispark_aries版本：<br>https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_release_2.2.2/2021-04-28_17-33-21/hispark_aries.tar.gz |

## OpenHarmony 2.2.2转测特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                              | status  | sig            | owner                                         |
| :--- | ------------------------------------------------------------ | :---------------------------------------------- | :------ | :------------- | :-------------------------------------------- |
| 1    | [I3HX0V](https://gitee.com/openharmony/hiviewdfx_hilog_lite/issues/I3HX0V) | 【HiLog】L1系统HiLog功能增强                    | Testing | SIG_BscSoftSrv | [@shenchenkai](https://gitee.com/shenchenkai) |
| 2    | [I3NPEL](https://gitee.com/openharmony/ai_engine/issues/I3NPEL) | 【AI子系统】AI子系统添加linux内核适配，编译选项 | Testing | SIG_AI         | [@armylee0](https://gitee.com/armylee0)       |
| 3    | [I3INEZ](https://gitee.com/openharmony/ai_engine/issues/I3INEZ) | 【AI子系统】AI引擎支持基于共享内存的数据传输    | Testing | SIG_AI         | [@armylee0](https://gitee.com/armylee0)       |
# OpenHarmony 2.1.1版本转测试信息：

| **转测试版本号：OpenHarmony 2.1.1**                      |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代一第一轮α测试，回归ISSUE问题单 |
| **转测试时间：2021-04-14**                                   |
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.1.1.001/2021-04-14_08-41-09/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.1.1.001/2021-04-14_08-38-01/hispark_pegasus.tar.gz |
| hispark_aries版本：<br>https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.1.1.001/2021-04-14_08-39-54/hispark_aries.tar.gz |

## 针对OpenHarmony 2.1.1版本解决的缺陷ISSUE列表：
| ISSUE                                                        | 问题描述                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [I3I31W](https://e.gitee.com/open_harmony/unset_project?issue=I3I31W) | ActsNFSTest.bin会引起内核crash                               |
| [I3D49E](https://e.gitee.com/open_harmony/issues/list?issue=I3D49E) | uboot的路径不对                                              |
| [I3D71U](https://e.gitee.com/open_harmony/issues/list?issue=I3D71U) | 【驱动子系统】反复reset，启动到hmac_main_init SUCCESSULLY后，高概率出现系统挂死 |
| [I3DGZW](https://e.gitee.com/open_harmony/issues/list?issue=I3DGZW) | 【应用程序框架子系统】HI3516开源板进入屏保后 ，点击触摸屏，出现蓝屏问题 |
| [I3DHIL](https://e.gitee.com/open_harmony/issues/list?issue=I3DHIL) | 【系统问题】HI3518开源板剩余空间不足，导致ACTS用例大量失败   |
| [I3DU36](https://e.gitee.com/open_harmony/issues/list?issue=I3DU36) | 【应用程序框架子系统】ipcamera bm 查询命令失效               |
| [I3EALU](https://e.gitee.com/open_harmony/issues/list?issue=I3EALU) | 【媒体子系统】cameraActs 用例执行时，找不到相机配置文件，初始失败 |
| [I3EGUX](https://e.gitee.com/open_harmony/issues/list?issue=I3EGUX) | 【可靠性问题】反复reset，出现一次KIdle进程crash，系统挂死无法启动 |
| [I3EH4E](https://e.gitee.com/open_harmony/issues/list?issue=I3EH4E) | 【流水线问题】高概率出现：uname无响应，然后执行reset也无响应 |
| [I3EQJA](https://e.gitee.com/open_harmony/issues/list?issue=I3EQJA) | 【文件系统】cat /proc/mounts功能不可用                       |
| [I3EQRC](https://e.gitee.com/open_harmony/issues/list?issue=I3EQRC) | 磁盘文件映射延迟测试：并发3个测试进程，系统crash             |
| [I3HVL0](https://e.gitee.com/open_harmony/issues/list?issue=I3HVL0) | 3861编译失败，报错[OHOS ERROR] Fatal error: invalid -march= option:rv32imac |

# OpenHarmony_release_1.0.1.001版本转测试信息：

| **转测试版本号：OpenHarmony_release_1.0.1.001**              |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony二次增量开源后，质量加固测试，提升版本稳定性 |
| **转测试时间：2021-03-24**                                   |
| hispark_taurus版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-37/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-35/hispark_pegasus.tar.gz |
| hispark_aries版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-36/hispark_aries.tar.gz |

# OpenHarmony_release_1.0.1_sp1版本转测试信息：

| **转测试版本号：OpenHarmony_release_1.0.1_sp1**              |
| ------------------------------------------------------------ |
| **版本用途：**Openharmoy社区首个LTS稳定版本，支撑OEM三方生态商用 |
| **转测试时间：2021-03-30**                                   |
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-36-58/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-34-56/hispark_pegasus.tar.gz |
| hispark_aries版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-36-41/hispark_aries.tar.gz |
