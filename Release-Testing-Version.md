# OpenHarmony_release_1.0.1_sp1版本转测试信息：

| **转测试版本号：OpenHarmony_release_1.0.1_sp1**              |
| ------------------------------------------------------------ |
| **版本用途：**Openharmoy社区首个LTS稳定版本，支撑OEM三方生态商用 |
| **转测试时间：2021-03-30**                                   |
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-36-58/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-34-56/hispark_pegasus.tar.gz |
| hispark_aries版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1_sp1/2021-03-30_10-36-41/hispark_aries.tar.gz |

# OpenHarmony_release_1.0.1.001版本转测试信息：

| **转测试版本号：OpenHarmony_release_1.0.1.001**              |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony二次增量开源后，质量加固测试，提升版本稳定性 |
| **转测试时间：2021-03-24**                                   |
| hispark_taurus版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-37/hispark_taurus.tar.gz |
| hispark_pegasus版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-35/hispark_pegasus.tar.gz |
| hispark_aries版本：<br/> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Release_Version/OpenHarmony_release_1.0.1.001/2021-03-23-19-36/hispark_aries.tar.gz |

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

# OpenHarmony 2.3.0.2 版本转测试信息：

| **转测试版本号：OpenHarmony 2.3.0.2                   |
| ------------------------------------------------------------ |
| **版本用途：**OpenHarmony码云master迭代二第二轮测试，验收内核、DFX子系统、分布式调度、全球化子系统，轻图像子系统等特性 |
| **API变更：**：本次转测特性涉及启动子系统，全球化子系统，轻图形子系统的API变更，均通过法务评审                     |
| **L0L1转测试时间：2021-07-07**                                   |
| **L0L1转测试版本获取路径：**                                   |
| hispark_taurus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210707_010917/version-Master_Version-OpenHarmony_2.3.0.3-20210707_010917-hispark_taurus.tar.gz    |
| hispark_taurus_linux版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210707_010937/version-Master_Version-OpenHarmony_2.3.0.3-20210707_010937-hispark_taurus_linux.tar.gz  |
| hispark_pegasus版本：<br>http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210707_010713/version-Master_Version-OpenHarmony_2.3.0.3-20210707_010713-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210707_010925/version-Master_Version-OpenHarmony_2.3.0.3-20210707_010925-hispark_aries.tar.gz   |
| **L2转测试时间：2021-07-07**                                   |
 **L2转测试版本获取路径：**                                   |
| hi3516dv300-L2版本：<br> http://download.ci.openharmony.cn/version/Master_Version/OpenHarmony_2.3.0.3/20210707_010745/version-Master_Version-OpenHarmony_2.3.0.3-20210707_010745-L2_hi3516dv300.tar.gz|
