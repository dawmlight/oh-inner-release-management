# L0L1 Native API Diff

| 模块名称  | 接口名称  | 变更类型  | 变更类型  |
|  --------  |  --------  |  --------  |  --------  |
| 描述模块的名称，例如：Native_layer、Image、Media等 | 描述变更元素的名称，包含结构体、类型定义、枚举、函数等，例如：结构体NativeLayerBuffer、类型定义NativeLayer、函数GetNativeLayer (JNIEnv *env, jobject surface)等。如果整个模块新增，则可以使用 - 符号 | 描述变更的类型，包含新增、删除、废弃、修改 | 如果为废弃，则需要描述替换的组件；如果为修改，则需要描述变化点，例如：新增xxx参数、xxx参数的默认值由xxx变更为xxx；其他情况可以使用 - 符号 |
| global_i18n_lite                                   | static LocaleInfo LocaleInfo ::ForLanguageTag(const char *languageTag, I18nStatus &status); | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | const char LocaleInfo ::*GetExtension(const char *key);      | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | WeekInfo::WeekInfo(const LocaleInfo &localeInfo, I18nStatus &status); | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | uint8_t WeekInfo::GetFirstDayOfWeek();                       | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | uint8_t WeekInfo::GetMinimalDaysInFirstWeek();               | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | uint8_t WeekInfo::GetFirstDayOfWeekend();                    | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | uint8_t WeekInfo::GetLastDayOfWeekend();                     | 新增                                       | 新增接口                                                     |
| global_i18n_lite                                   | int PluralFormat::GetPluralRuleIndex(double number, I18nStatus status); | 新增                                       | 新增接口                                                     |
| powermgr_powermgr_lite                                   | const RunningLock *CreateRunningLock(const char *name, RunningLockType type, RunningLockFlag flag); | 新增                                       | 新增接口                                                     |
| powermgr_powermgr_lite                                   | void DestroyRunningLock(const RunningLock *lock); | 新增                                       | 新增接口                                                     |
| powermgr_powermgr_lite                                   | BOOL AcquireRunningLock(const RunningLock *lock); | 新增                                       | 新增接口                                                     |
| powermgr_powermgr_lite                                   | BOOL ReleaseRunningLock(const RunningLock *lock); | 新增                                       | 新增接口                                                     |
| powermgr_powermgr_lite                                   | BOOL IsRunningLockHolding(const RunningLock *lock); | 新增                                       | 新增接口                                                     |
