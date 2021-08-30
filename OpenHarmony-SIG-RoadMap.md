 OpenHarmony社区版本发布计划





# OpenHarmony社区版本发布计划：

| **迭代计划** | **版本**号             | **版本构建** | **版本转测试** | **版本测试完成** |
| ------------ | ---------------------- | ------------ | -------------- | ---------------- |
| IT1（API Level：6）          | OpenHarmony 2.2.0.1  | 2021/4/21 | 2021/4/21      | 2021/5/11        |
|              | OpenHarmony 2.2.0.2  | 2021/5/12    | 2021/5/12      | 2021/5/18        |
|              | OpenHarmony 2.2.0.3 | 2021/5/19    | 2021/5/19      | 2021/5/25 |
|              | OpenHarmony 2.2.0.5 | 2021/6/2 | 2021/6/2 | **2021/6/7** |
|              | OpenHarmony 2.3.0.1 | 2021/6/23   | 2021/6/23     | 2021/7/6      |
|              | OpenHarmony 2.3.0.2 | 2021/7/7  | 2021/7/7    | 2021/7/13     |
|              | OpenHarmony 2.3.0.3 | 2021/7/14 | 2021/7/14   | 2021/7/20 |
|              | OpenHarmony 2.2 Beta2 | 2021/7/21 | 2021/7/21 | **2021/7/30** |
| IT2（API Level：7）          | OpenHarmony 3.0.0.1 | 2021/7/28   | 2021/7/28     | 2021/8/3         |
|              | OpenHarmony 3.0.0.2 | 2021/8/4     | 2021/8/4       | 2021/8/10        |
|              | OpenHarmony 3.0.0.3 | 2021/8/11  | 2021/8/11    | 2021/8/17       |
|              | OpenHarmony 3.0 Beta1 | 2021/8/19   | 2021/8/19     | 2021/8/24      |
|              | OpenHarmony 3.0.0.6 | 2021/8/25   | 2021/8/25     | 2021/9/7        |
|              | OpenHarmony 3.0.0.7 | 2021/9/8    | 2021/9/8      | 2021/9/14        |
|              | OpenHarmony 3.0.0.8 | 2021/9/15   | 2021/9/15     | 2021/9/21   |
|              | OpenHarmony 3.0 LTS | 2021/9/22  | 2021/9/22 | **2021/9/28** |
| IT3（API Level：8）          | OpenHarmony 3.1.0.1   | 2021/10/20    | 2021/10/20      | 2021/11/2       |
|              | OpenHarmony 3.1.0.2   | 2021/11/3   | 2021/11/3     | 2021/11/9       |
|              | OpenHarmony 3.1.0.3   | 2021/11/10   | 2021/11/10     | 2021/11/16         |
|              | OpenHarmony 3.1 Beta1 | 2021/11/17    | 2021/11/17      | **2021/11/23**    |
| IT4（API Level：8）          | OpenHarmony 3.1.1.1   | 2021/12/8    | 2021/12/8      | 2021/12/21       |
|              | OpenHarmony 3.1.1.2   | 2021/12/22   | 2021/12/22     | 2021/12/28       |
|              | OpenHarmony 3.1.1.3   | 2021/12/29   | 2021/12/29     | 2022/1/5         |
|              | OpenHarmony 3.1 Beta2 | 2022/1/6    | 2022/1/6      | **2022/1/17**    |

# 各版本特性交付清单：

## OpenHarmony 2.2.0.1版本特性清单：

针对OpenHarmony 2.2.0.1版本解决的缺陷ISSUE列表：

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

## OpenHarmony 2.2.0.2版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                           | status     | sig            | owner                                         |
| :--- | ------------------------------------------------------------ | :------------------------------------------- | :--------- | :------------- | :-------------------------------------------- |
| 1    | [I3HX0V](https://gitee.com/openharmony/hiviewdfx_hilog_lite/issues/I3HX0V) | 【HiLog】L1系统HiLog功能增强                 | developing | SIG_BscSoftSrv | [@shenchenkai](https://gitee.com/shenchenkai) |
| 2    | I3INEZ                                                       | 【AI子系统】AI引擎支持基于共享内存的数据传输 | developing | SIG_AI         | [@armylee0](https://gitee.com/armylee0)       |

## OpenHarmony 2.2.0.3版本特性清单：

暂无

## OpenHarmony 2.2 Beta版本特性清单：

 状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                  | status     | sig                  | owner                                   |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :------------------- | :-------------------------------------- |
| 1    | [I3ICFO](https://gitee.com/openharmony/utils_native_lite/issues/I3ICFO) | 【分布式数据管理】提供数据库内容的删除能力          | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 2    | [I3ICH0](https://gitee.com/openharmony/utils_native_lite/issues/I3ICH0) | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 3    | [I3ICG4](https://gitee.com/openharmony/utils_native_lite/issues/I3ICG4) | 【分布式数据管理】提供相关数据存储的原子操作能力    | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 4    | [I3ICGH](https://gitee.com/openharmony/utils_native_lite/issues/I3ICGH) | 【分布式数据管理】提供二进制Value的写入读取能力     | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 5    | [I3NSPB](https://gitee.com/openharmony/graphic_ui/issues/I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |
| 7    | [I3NSZH](https://gitee.com/openharmony/graphic_ui/issues/I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |

## OpenHarmony 2.3.0.1版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统      | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 2    | [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】L0上对外提供统一的文件系统操作接口           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 3    | [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】L0 补充120个POSIX接口                        | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 4    | [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器                           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 5    | [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升                          | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 6    | [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 7    | [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块                                | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 8    | [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理                                    | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 9    | [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块                                   | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 10   | [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 11   | [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置                       | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 12   | [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配                   | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 13   | [I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】L0支持三方组件Mbedtls编译                    | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】L0支持三方组件curl编译                       | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15  | [I3NIME](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NIME) | 【启动恢复子系统】支持恢复出厂设置                           | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 16   | [I3NTBC](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTBC) | 【启动恢复子系统】L0/L1/L2接口优化                           | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 17   | [I3NN4H](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN4H) | 【DFX子系统】【HiLog】L0系统HiLog功能增强                    | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 18  | [I3NN53](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN53) | 【DFX子系统】【HiEvent】L0系统HiEvent功能增强                | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 19   | [I3ID9Q](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道             | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 20  | [I3ID9V](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9V) | 【分布式调度】轻量设备启动富设备上的Ability                  | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 21  | [I3I1V8](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1V8)         | 【全球化子系统】构建应用资源解析和加载机制                   | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 22  | [I3I1VJ](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1VJ) | 【全球化子系统】构建资源回溯机制                             | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 23   | [I3QE85](https://gitee.com/openharmony/drivers_framework/issues/I3QE85) | 【驱动子系统】L0支持HDF框架                                  | developing | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 24   | [I3NSVQ](https://gitee.com/openharmony/graphic_ui/issues/I3NSVQ) | 【轻量级图形】DFX维测能力：UIKit支持显示控件轮廓             | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 25   | [I3NSWY](https://gitee.com/openharmony/graphic_ui/issues/I3NSWY) | 【轻量级图形】ScrollView/List支持通过弧形进度条展示滑动进度  | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 26   | [I3NSZZ](https://gitee.com/openharmony/graphic_ui/issues/I3NSZZ) | 【轻量级图形】支持开关按钮/复选框/单选按钮动效               | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 27   | [I3NSQ6](https://gitee.com/openharmony/graphic_ui/issues/I3NSQ6) | 【轻量级图形】UIKit支持点阵字体产品化解耦                    | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 28   | [I3NSZ1](https://gitee.com/openharmony/graphic_ui/issues/I3NSZ1) | 【轻量级图形】UI框架提供统一多后端框架支持多芯片平台         | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |           |

## OpenHarmony 2.3.0.2 版本特性清单：	

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

L0/L1需求列表:
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1    | [I3NCB9](https://gitee.com/openharmony/third_party_Linux_Kernel/issues/I3NCB9) | 【L1 Linux开源】编译器替换后的内核代码适配                   | developing | SIG_Kernel           | [@zzzuo](https://gitee.com/zzzuo)                 |
| 2   | [I3NBVI](https://gitee.com/openharmony/build_lite/issues/I3NBVI) | 【L1 Linux开源】clang替换                                    | developing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 3   | [I3NC8H](https://gitee.com/openharmony/build_lite/issues/I3NC8H) | 【L1 Linux开源】musl库替换                                   | developing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 4    | [I3NCEF](https://gitee.com/openharmony/build_lite/issues/I3NCEF) | 【L1 Linux开源】工具集替换                                   | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 5   | [I3NCF7](https://gitee.com/openharmony/build_lite/issues/I3NCF7) | 【L1 Linux开源】rootfs替换                                   | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 6   | [I3NCG0](https://gitee.com/openharmony/build_lite/issues/I3NCG0) | 【L1 Linux开源】镜像制作工具替换                             | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 7   | [I3NCGM](https://gitee.com/openharmony/build_lite/issues/I3NCGM) | 【L1 Linux开源】开源编译构建                                 | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 8   | [I3NCCT](https://gitee.com/openharmony/drivers_adapter/issues/I3NCCT) | 【L1 Linux开源】编译器替换后的HDF适配                        | developing | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)               |
| 9   | [I3N0LP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0LP?from=project-issue) | 【全球化子系统】构建自定义数据编译能力                       | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 10   | [I3N0OP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0OP?from=project-issue) | 【全球化子系统】构建星期、单复数、数字开关国际化能力         | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 11   | [I3NSY0](https://gitee.com/openharmony/graphic_ui/issues/I3NSY0) | 【轻量级图形】支持A4\A8、LUT8、TSC图片格式作为输入           | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 12   | [I3NT0R](https://gitee.com/openharmony/graphic_ui/issues/I3NT0R) | 【轻量级图形】支持多语言字体对齐                             | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 13   | [I3SNGO](https://gitee.com/openharmony/build_lite/issues/I3SNGO) | 【编译子系统】build_lite支持开源软件的通用patch框架          | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |

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


## OpenHarmony 2.3.0.3版本特性清单：
L0/L1需求列表:
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3NN88](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN88) | 【DFX子系统】【HiDumper】LiteOS_M系统信息dump工具 | developing | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 2    | [I3NN7D](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7D) | 【DFX子系统】【HiDumper】LiteOS_A系统信息dump工具 | developing | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 3    | [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 4    | [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】L0支持轻量级shell框架和常用调测命令           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 5    | [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】L0 LiteOS-M支持ARM9架构                     | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 6    | [I3NE8P](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NE8P) | 【电源管理】充放电状态查询接口                               | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 7    | [I3NIEJ)](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIEJ) | 【电源管理】电量查询接口                                     | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 8    | [I3NIFG](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFG) | 【电源管理】实现并提供低功耗模式                             | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 9   | [I3NIFR](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFR) | 【电源管理】提供低功耗模式统一API                            | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 10   | [I3NN7V](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7V) | 【DFX子系统】【BBoxDetector】LiteOS_A死机重启维测框架        | developing | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 11   | [I3NN9B](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN9B) | 【DFX子系统】【BBoxDetector】LiteOS_M死机重启维测框架        | developing | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
L2需求列表:
| 1 | [I3ZN3M](https://gitee.com/open_harmony/dashboard?issue_id=I3ZN3M) | 【分布式数据管理】鸿蒙单框架L2分布式数据管理开源 | Testing | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 2 | [I40K12](https://gitee.com/open_harmony/dashboard?issue_id=I40K12) | 【Samples】【JSUI】【容器组件】JS气泡（popup） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 3 | [I40K1P](https://gitee.com/open_harmony/dashboard?issue_id=I40K1P) | 【Samples】【JSUI】【容器组件】下拉刷新容器（refresh） | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 4 | [I40K2A](https://gitee.com/open_harmony/dashboard?issue_id=I40K2A) | 【Samples】【数据】【HarmonyOS】轻量级偏好数据库 | Testing | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 5 | [I40NBW](https://gitee.com/open_harmony/dashboard?issue_id=I40NBW) | 【应用子系统】鸿蒙单框架L2系统应用-设置开源-WLAN | Testing | SIG_SysApplication | [@nicolaswang](https://gitee.com/nicolaswang) |

## OpenHarmony 2.3.0.3版本特性清单：

L2需求列表：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1 | [I41LYF](https://gitee.com/open_harmony/dashboard?issue_id=I41LYF) | 导航栏支持显示BACK、HOME、RECENT菜单 | Testing | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 2 | [I41LSC](https://gitee.com/open_harmony/dashboard?issue_id=I41LSC) | 【SystemUI】SystemUI权限系统弹窗能力 | Testing | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 3 | [I3XY72](https://gitee.com/open_harmony/dashboard?issue_id=I3XY72) | c++与 js时间\日期和数字国际化能力构建 | Testing | SIG_ApplicationFramework | [@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat) |

## OpenHarmony 2.2 Beta2 版本特性清单：

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


## OpenHarmony 3.0.0.1版本特性清单：

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


## OpenHarmony 3.0.0.2版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
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

## OpenHarmony 3.0.0.3版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1   | [I3XCB5](https://gitee.com/openharmony/appexecfwk_appexecfwk_lite/issues/I3XCB5) | 【应用程序框架】按照应用粒度的存储资源使用统计       | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)            |
| 2   | [I3NK7D](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NK7D) | 【多媒体子系统】适配新南向接口                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 3   | [I3NM60](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM60) | 【多媒体子系统】相机metadata管理及相机静态能力查询           | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 4   | [I3NM6F](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM6F) | 【多媒体子系统】相机设备管理                                 | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 5   | [I3NM73](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM73) | 【多媒体子系统】相机图像帧管理                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 6   | [I3NM8J](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM8J) | 【多媒体子系统】本地mp3播放支持                              | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 7   | [I3NMMU](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMMU) | 【多媒体子系统】编码视频流和音频流处理支持                   | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |

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

## OpenHarmony 3.0.0.6版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I3NN1Z](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3NN1Z) | 【应用程序框架】轻量级实现弹窗授权动态授权机制               | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 2    | [I3NTAZ](https://gitee.com/openharmony/security_huks/issues/I3NTAZ) | 【安全】轻量级实现弹窗授权动态授权机制                       | developing | SIG_Security         | [@scuteehuangjun](https://gitee.com/scuteehuangjun) |

L2 需求列表：
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
|1|[I45ZKP](https://gitee.com/open_harmony/dashboard?issue_id=I45ZKP)|RQ-[Demo&应用子系统][JSUI][画布组件] JsCanvas|Testing|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|2|[I466KX](https://gitee.com/open_harmony/dashboard?issue_id=I466KX)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】 栅格布局|Testing|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|3|[I45YM2](https://gitee.com/open_harmony/dashboard?issue_id=I45YM2)|RQ-[Demo&应用子系统][JS UI]【OpenHarmony】JS自定义组件（JSUICustomComponent）|Testing|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|4|[I44Y4J](https://gitee.com/open_harmony/dashboard?issue_id=I44Y4J)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应卡片（AdaptiveServiceWidget）|Testing|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|5|[I44Y0N](https://gitee.com/open_harmony/dashboard?issue_id=I44Y0N)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应页面（AdaptivePortalPage）|Testing|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|6|[I44Y15](https://gitee.com/open_harmony/dashboard?issue_id=I44Y15)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应效率型首页（AdaptivePortalList）|Testing|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|7|[I46ZCN](https://gitee.com/open_harmony/dashboard?issue_id=I46ZCN)|RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】添加NativeLayer示例|Testing|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|8|[I3ZVTJ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVTJ)|【分布式任务调度子系统】接收远端拉起FA请求，跨设备拉起远端FA|Testing|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|9|[I3ZVTT](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVTT)|【分布式任务调度子系统】鸿蒙单框架L2分布式能力建设-SAMGR模块构建|Testing|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|10|[I3ZMY9](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMY9)|【分布式数据管理子系统】【本地数据库】 XTS测试用例|Testing|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|11|[I41H55](https://gitee.com/open_harmony/dashboard?issue_id=I41H55)|【驱动子系统】基于HDF驱动框架提供I2S/PCM平台总线驱动|Testing|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|12|[I41HBF](https://gitee.com/open_harmony/dashboard?issue_id=I41HBF)|【驱动子系统】基于HDF驱动框架提供Display驱动模型兼容DRM显示框架|Testing|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|13|[I46J19](https://gitee.com/open_harmony/dashboard?issue_id=I46J19)|add jsapi in compileruntime|Testing|SIG_CompileRuntime|[@xliu-huanwei](https://gitee.com/xliu-huanwei)|
|14|[I46N37](https://gitee.com/open_harmony/dashboard?issue_id=I46N37)|升级quickjs使用worker|Testing|SIG_CompileRuntime|[@wpyhuawei](https://gitee.com/wpyhuawei)|
|15|[I40PBC](https://gitee.com/open_harmony/dashboard?issue_id=I40PBC)|应用侧发布本地分组的普通通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|16|[I40PBF](https://gitee.com/open_harmony/dashboard?issue_id=I40PBF)|在免打扰模式下发布通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|17|[I40PBG](https://gitee.com/open_harmony/dashboard?issue_id=I40PBG)|发布开启一个无页面的Ability的wantAgent|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|18|[I40PBH](https://gitee.com/open_harmony/dashboard?issue_id=I40PBH)|取消WantAgent的实例|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|19|[I40PBI](https://gitee.com/open_harmony/dashboard?issue_id=I40PBI)|发布公共事件的WantAgent通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|20|[I40PBM](https://gitee.com/open_harmony/dashboard?issue_id=I40PBM)|应用侧取消本地通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|21|[I40PBN](https://gitee.com/open_harmony/dashboard?issue_id=I40PBN)|应用侧发布声音通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|22|[I40PBO](https://gitee.com/open_harmony/dashboard?issue_id=I40PBO)|应用侧发布振动通知|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|23|[I40PBP](https://gitee.com/open_harmony/dashboard?issue_id=I40PBP)|应用侧发布本地有输入框的通知（NotificationUserInput）|Testing|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|

## OpenHarmony 3.0.0.7版本特性清单:
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| no   | issue                                                        | feture description                                | status     | sig            | owner                                 |
| :--- | ------------------------------------------------------------ | :------------------------------------------------ | :--------- | :------------- | :------------------------------------ |
| 1    | [I46W6Q](https://gitee.com/openharmony/global_i18n_lite/issues/I46W6Q) | 【全球化】新增31种语言支持              | developing | SIG_AppFramework     | [@zhiweilai](https://gitee.com/zhiweilai)              |

## OpenHarmony 3.0.0.8 版本特性清单：

| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1    | [I3ND6Y](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ND6Y) | 【性能】OS内核&驱动启动优化                           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 2    | [I3NT3F](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT3F) | 【轻内核子系统】内核支持trace功能                            | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 3    | [I3NT63](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT63) | 【轻内核子系统】pagecache功能完善                            | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 4    | [I3NTCT](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTCT) | 【启动恢复子系统】Linux版本init支持热插拔                    | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)         |
| 5    | [I3O2G8](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3O2G8?from=project-issue) | 【应用程序框架】轻量级应用实现entity标签                     | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)|

## OpenHarmony 3.0 LTS版本特性清单：
暂无


## OpenHarmony 3.1.0.1版本特性清单：

暂无

## OpenHarmony 3.1.0.2版本特性清单：
| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1   | [I3NTDP](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTDP) | 【电话服务】支持轻量级mbed TLS协议栈                      | developing | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |

## OpenHarmony 3.1.0.3版本特性清单：

暂无

## OpenHarmony 3.1 Beta1版本特性清单：

暂无
## OpenHarmony 3.1.1.1版本特性清单：

暂无

## OpenHarmony 3.1.1.2版本特性清单：

暂无

## OpenHarmony 3.1.1.3版本特性清单：

暂无

## OpenHarmony 3.1 Beta2版本特性清单：

暂无
>  


###### 以上计划由OpenHarmony社区版本发布SIG组织发布
