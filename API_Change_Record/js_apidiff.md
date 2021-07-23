# L0L1 JS API Diff
## 组件

| 组件类型  | 组件名称  | 变更类型  | 变更类型  |
|  --------  |  --------  |  --------  |  --------  |
| 描述组件的类型，例如：容器组件、基础组件、媒体组件等      | 描述组件名称，例如：div、button等      | 描述变更的类型，包含新增、删除、废弃、修改      | 如果为废弃，则需要描述替换的组件；如果为修改，则需要描述变化点，例如：新增xxx参数、xxx参数的默认值由xxx变更为xxx；其他情况可以使用 - 符号      |

## 接口变更

| 模块名称  | 接口名称  | 变更类型  | 变更说明  |
|  --------  |  --------  |  --------  |  --------  |
| 描述接口所属的模块，例如：数据存储、文件存储等      | 描述接口名称，例如：storage.get(OBJECT)。如果整个模块新增，则可以使用 - 符号      | 描述变更的类型，包含新增、删除、废弃、修改      | 如果为废弃，则需要描述替换的接口；如果为修改，则需要描述变化点，例如：新增xxx参数、xxx参数的默认值由xxx变更为xxx；其他情况可以使用 - 符号      |

# L2 JS API Diff
| 组件类型  | 组件名称  | 变更类型  | 变更类型  |
|  --------  |  --------  |  --------  |  --------  |
| 描述组件的类型，例如：容器组件、基础组件、媒体组件等      | 描述组件名称，例如：div、button等      | 描述变更的类型，包含新增、删除、废弃、修改      | 如果为废弃，则需要描述替换的组件；如果为修改，则需要描述变化点，例如：新增xxx参数、xxx参数的默认值由xxx变更为xxx；其他情况可以使用 - 符号      |
| 全球化      | 时间日期数字模块      | 新增      | -      |

## 接口变更

| 模块名称  | 接口名称  | 变更类型  | 变更说明  |
|  --------  |  --------  |  --------  |  --------  |
| 描述接口所属的模块，例如：数据存储、文件存储等      | 描述接口名称，例如：storage.get(OBJECT)。如果整个模块新增，则可以使用 - 符号      | 描述变更的类型，包含新增、删除、废弃、修改      | 如果为废弃，则需要描述替换的接口；如果为修改，则需要描述变化点，例如：新增xxx参数、xxx参数的默认值由xxx变更为xxx；其他情况可以使用 - 符号      |
  |  时间日期数字模块-Locale  |  constructor(locale: string, options?:options)  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  toString(): string  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  maximize(): Locale  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  minimize(): Locale  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  calendar  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  caseFirst  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  collation  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  hourCycle  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  numberingSystem  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  numeric  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  language  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  script  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  region  |  新增  |  -  |
  |  时间日期数字模块-Locale  |  baseName  |  新增  |  -  |
  |  时间日期数字模块-DateTimeFormat  |  constructor(locale: string, options?:options)  |  新增  |  -  |
  |  时间日期数字模块-DateTimeFormat  |  constructor(locale: string[], options?:options)  |  新增  |  -  |
  |  时间日期数字模块-DateTimeFormat  |  resolvedOptions(): DateTimeOptions  |  新增  |  -  |
  |  时间日期数字模块-DateTimeFormat  |  format(date: Date): string;  |  新增  |  -  |
  |  时间日期数字模块-DateTimeFormat  |  formatRange(fromDate: Date, toDate: Date): string;  |  新增  |  -  |
  |  时间日期数字模块-NumberFormat  |  constructor(locale: string, options?:options)  |  新增  |  -  |
  |  时间日期数字模块-NumberFormat  |  constructor(locale: string[], options?:options)  |  新增  |  -  |
  |  时间日期数字模块-NumberFormat  |  resolvedOptions(): NumberOptions  |  新增  |  -  |
  |  时间日期数字模块-NumberFormat  |  format(number: number): string;  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  locale  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  dateStyle  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  timeStyle  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  calendar  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  dayPeriod  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  numberingSystem  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  localeMatcher  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  timeZone  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  hour12  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  hourCycle  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  formatMatcher  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  weekday  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  era  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  year  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  month  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  day  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  hour  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  minute  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  second  |  新增  |  -  |
  |  时间日期数字模块-DateTimeOptions  |  timeZoneName  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  locale  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  compactDisplay  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  currency  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  currencyDisplay  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  currencySign  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  localeMatcher  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  notation  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  numberingSystem  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  signDisplay  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  style  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  unit  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  unitDisplay  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  useGrouping  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  minimumIntegerDigits  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  minimumFractionDigits  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  maximumFractionDigits  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  minimumSignificantDigits  |  新增  |  -  |
  |  时间日期数字模块-NumberOptions  |  maximumSignificantDigits  |  新增  |  -  |

