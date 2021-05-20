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

| **转测试版本号：OpenHarmony_2.1.1.001**                      |
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
| hispark_taurus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210520_145711/Master_Version-OpenHarmony_2.2_Beta1-20210520_145711-hispark_taurus.tar.gz |
| hispark_pegasus版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210520_145458/Master_Version-OpenHarmony_2.2_Beta1-20210520_145458-hispark_pegasus.tar.gz |
| hispark_aries版本：<br> https://hm-verify.obs.cn-north-4.myhuaweicloud.com/version/Master_Version/OpenHarmony_2.2_Beta1/20210520_145630/Master_Version-OpenHarmony_2.2_Beta1-20210520_145630-hispark_aries.tar.gz |

## OpenHarmony 2.2 beta1版本特性清单：

 状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                  | status     | sig                  | owner                                   |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :------------------- | :-------------------------------------- |
| 1    | [I3ICFO](https://gitee.com/openharmony/utils_native_lite/issues/I3ICFO) | 【分布式数据管理】提供数据库内容的删除能力          | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 2    | [I3ICH0](https://gitee.com/openharmony/utils_native_lite/issues/I3ICH0) | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 3    | [I3ICG4](https://gitee.com/openharmony/utils_native_lite/issues/I3ICG4) | 【分布式数据管理】提供相关数据存储的原子操作能力    | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 4    | [I3ICGH](https://gitee.com/openharmony/utils_native_lite/issues/I3ICGH) | 【分布式数据管理】提供二进制Value的写入读取能力     | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 5    | [I3NSPB](https://gitee.com/openharmony/graphic_ui/issues/I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |
| 7    | [I3NSZH](https://gitee.com/openharmony/graphic_ui/issues/I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |