# ChangeLog
## xxx子系统（该段落为示例，请不要修改或删除）
已经release的版本发生了影响契约兼容性（契约兼容：也称语义兼容，指版本演进后，开发者原有程序行为不发生变化）的变更（包括不限于接口名、参数、返回值、所需要的权限、调用顺序、枚举值、配置参数、路径等），则需要在ChangeLog中对变更进行阐述。
### cl.subsystemname.x xxx功能变更， 例：DeviceType属性变更、相机权限变更（尽量概括，不要超过15个字）
每个变更标题前需要附加编号：cl.subsystemname.x。cl为ChangeLog首字母缩写，subsystemname请填写子系统英文标准名称，x表示变更序号（从低到高逐位增加）。
以功能维度对变更点进行概括描述。例如：xxx功能的xxx、xxx等发生了xxx变化，开发者需要根据以下说明对应用进行适配。
如果有此变更有对应的需求或设计文档，可以在描述中附上对应的设计文档编号。

**变更影响**

是否影响已release的接口或者接口行为发生变更等；影响的是JS接口、Java接口还是Native接口。

**关键的接口/组件变更**

列举此功能变更涉及的接口/组件变更。

**适配指导（可选，不涉及则可以删除）**

（前面空一行）提供指导，帮助开发者针对相关变更进行适配，使应用可以与新版本兼容。例：
在xxx文件中将xxx参数修改为xxx。
```
sample code
```
### cl.subsystemname.x xxx功能变更
每个功能变更点在自己的子系统章节内新增一个功能变更章节。

## xxx子系统
每个子系统有且只能有一个子系统章节。

## 全球化子系统

### cl.global.1 新增WeekInfo、小数单复数和数字体系设置功能

**变更影响**

新增星期相关数据、小数单复数接口和数字体系设置功能。

**关键的接口/组件变更**

新增以下接口：

*LocaleInfo类：*
static LocaleInfo ForLanguageTag(const char *languageTag, I18nStatus &status);

const char *GetExtension(const char *key);

```
LocaleInfo locale = LocaleInfo::ForLanguageTag("zh-Hant-CN-u-nu-arab", status);
const char *numberDigits = locale.GetExtension("nu");
```

*WeekInfo类：*
WeekInfo(const LocaleInfo &localeInfo, I18nStatus &status);
uint8_t GetFirstDayOfWeek();
uint8_t GetMinimalDaysInFirstWeek();
uint8_t GetFirstDayOfWeekend();
uint8_t GetLastDayOfWeekend();

```
WeekInfo weekInfo(locale, status);
uint8_t ret1 = weekInfo.GetFirstDayOfWeek(); // Return 1
uint8_t ret2 = weekInfo.GetMinimalDaysInFirstWeek(); // Return 1
uint8_t ret3 = weekInfo.GetFirstDayOfWeekend(); // Return 7
uint8_t ret4 = weekInfo.GetLastDayOfWeekend(); // Return 1
```

*PluralFormat类：*
int GetPluralRuleIndex(double number, I18nStatus status);

```
LocaleInfo locale("hr", "", "");
I18nStatus status = I18nStatus::ISUCCESS;
PluralFormat formatter(locale, status);
double number = 2.3;
int out = formatter.GetPluralRuleIndex(number, status); // Return 3
```


## 电源管理子系统

### powermgr_lite 新增增休眠唤醒锁管理，包括所的创建、持有、释放、销毁等功能。

**变更影响**

新增休眠唤醒锁管理，包括所的创建、持有、释放、销毁等功能。

**关键的接口/组件变更**

新增以下接口：

const RunningLock *CreateRunningLock(const char *name, RunningLockType type, RunningLockFlag flag);
void DestroyRunningLock(const RunningLock *lock);
BOOL AcquireRunningLock(const RunningLock *lock);
BOOL ReleaseRunningLock(const RunningLock *lock);
BOOL IsRunningLockHolding(const RunningLock *lock);

```
const RunningLock *lock = CreateRunningLock("runinglock_example", RUNNINGLOCK_BACKGROUND, RUNNINGLOCK_FLAG_NONE);
if (lock == NULL) {   
   return;
}
BOOL ret = AcquireRunningLock(lock);
if (ret == FLASE) {
   DestroyRunningLock(lock);
   return;
}
ReleaseRunningLock(lock);
DestroyRunningLock(lock); // Must release runninglock before destroyed
```

### 
