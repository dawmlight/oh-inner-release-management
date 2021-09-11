

# 标准系统接口变更

| 模块名称  | 接口名称  | 变更类型  | 变更说明  |
|  --------  |  --------  |  --------  |  --------  |
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
|文件存储- system.file|mkdir|新增|-|
|文件存储- system.file|rmdir|新增|-|
|文件存储- system.file|get|新增|-|
|文件存储- system.file|list|新增|-|
|文件存储- system.file|copy|新增|-|
|文件存储- system.file|move|新增|-|
|文件存储- system.file|delete|新增|-|
|文件存储- system.file|access|新增|-|
|文件存储- system.file|writeText|新增|-|
|文件存储- system.file|writeArrayBuffer|新增|-|
|文件存储- system.file|readText|新增|-|
|文件存储- system.file|readArrayBuffer|新增|-|
|文件存储- fileio|Dir.readSync|新增|-|
|文件存储- fileio|Dir.closeSync|新增|-|
|文件存储- fileio|dirent.name|新增|-|
|文件存储- fileio|dirent.isBlockDevice()|新增|-|
|文件存储- fileio|dirent.isCharacterDevice()|新增|-|
|文件存储- fileio|dirent.isDirectory()|新增|-|
|文件存储- fileio|dirent.isFIFO()|新增|-|
|文件存储- fileio|dirent.isFile()|新增|-|
|文件存储- fileio|dirent.isSocket()|新增|-|
|文件存储- fileio|dirent.isSymbolicLink()|新增|-|
|文件存储- fileio|stat.dev|新增|-|
|文件存储- fileio|stat.ino|新增|-|
|文件存储- fileio|stat.mode|新增|-|
|文件存储- fileio|stat.nlink|新增|-|
|文件存储- fileio|stat.uid|新增|-|
|文件存储- fileio|stat.gid|新增|-|
|文件存储- fileio|stat.rdev|新增|-|
|文件存储- fileio|stat.size|新增|-|
|文件存储- fileio|stat.blocks|新增|-|
|文件存储- fileio|stat.atime|新增|-|
|文件存储- fileio|stat.mtime|新增|-|
|文件存储- fileio|stat.ctime|新增|-|
|文件存储- fileio|stat.isBlockDevice()|新增|-|
|文件存储- fileio|stat.isCharacterDevice()|新增|-|
|文件存储- fileio|stat.isDirectory()|新增|-|
|文件存储- fileio|stat.isFIFO()|新增|-|
|文件存储- fileio|stat.isFile()|新增|-|
|文件存储- fileio|stat.isSocket()|新增|-|
|文件存储- fileio|stat.isSymbolicLink()|新增|-|
|文件存储- fileio|Stream.flushSync()|新增|-|
|文件存储- fileio|Stream.writeSync()|新增|-|
|文件存储- fileio|Stream.readSync()|新增|-|
|文件存储- fileio|Stream.closeSync()|新增|-|
|文件存储- fileio|fileio.accessSync()|新增|-|
|文件存储- fileio|fileio.chmodSync()|新增|-|
|文件存储- fileio|fileio.chownSync()|新增|-|
|文件存储- fileio|fileio.closeSync()|新增|-|
|文件存储- fileio|fileio.copyFileSync()|新增|-|
|文件存储- fileio|fileio.createStreamSync()|新增|-|
|文件存储- fileio|fileio.fchmodSync()|新增|-|
|文件存储- fileio|fileio.fchownSync()|新增|-|
|文件存储- fileio|fileio.fdopenStreamSync()|新增|-|
|文件存储- fileio|fileio.fstatSync()|新增|-|
|文件存储- fileio|fileio.fsyncSync()|新增|-|
|文件存储- fileio|fileio.ftruncateSync()|新增|-|
|文件存储- fileio|fileio.mkdirSync()|新增|-|
|文件存储- fileio|fileio.openSync()|新增|-|
|文件存储- fileio|fileio.opendirSync()|新增|-|
|文件存储- fileio|fileio.readSync()|新增|-|
|文件存储- fileio|fileio.renameSync()|新增|-|
|文件存储- fileio|fileio.rmdirSync()|新增|-|
|文件存储- fileio|fileio.statSync()|新增|-|
|文件存储- fileio|fileio.truncateSync()|新增|-|
|文件存储- fileio|fileio.unlinkSync()|新增|-|
|文件存储- fileio|fileio.writeSync()|新增|-|
|设备管理-DeviceManager|DeviceInfo|新增|-|
|设备管理-DeviceManager|DeviceType|新增|-|
|设备管理-DeviceManager|DeviceStateChangeAction|新增|-|
|设备管理-DeviceManager|SubscribeInfo|新增|-|
|设备管理-DeviceManager|DiscoverMode|新增|-|
|设备管理-DeviceManager|ExchangeMedium|新增|-|
|设备管理-DeviceManager|ExchangeFreq|新增|-|
|设备管理-DeviceManager|SubscribeCap|新增|-|
|设备管理-DeviceManager|createDeviceManager(bundleName: string, callback: AsyncCallback<DeviceManager>): void|新增|-|
|设备管理-DeviceManager|release(): void|新增|-|
|设备管理-DeviceManager|getTrustedDeviceListSync(): Array<DeviceInfo>|新增|-|
|设备管理-DeviceManager|startDeviceDiscovery(subscribeInfo: SubscribeInfo): void|新增|-|
|设备管理-DeviceManager|stopDeviceDiscovery(subscribeId: number): void|新增|-|
|设备管理-DeviceManager|authenticateDevice(deviceInfo: DeviceInfo): void|新增|-|
|设备管理-DeviceManager|on(type: 'deviceStateChange', callback: Callback<{ action: DeviceStateChangeAction, device: DeviceInfo }>): void|新增|-|
|设备管理-DeviceManager|off(type: 'deviceStateChange', callback?: Callback<{ action: DeviceStateChangeAction, device: DeviceInfo }>): void|新增|-|
|设备管理-DeviceManager|on(type: 'deviceFound', callback: Callback<{ subscribeId: number, device: DeviceInfo }>): void|新增|-|
|设备管理-DeviceManager|off(type: 'deviceFound', callback?: Callback<{ subscribeId: number, device: DeviceInfo }>): void|新增|-|
|设备管理-DeviceManager|on(type: 'discoverFail', callback: Callback<{ subscribeId: number, reason: number }>): void|新增|-|
|设备管理-DeviceManager|off(type: 'discoverFail', callback?: Callback<{ subscribeId: number, reason: number }>): void|新增|-|
|设备管理-DeviceManager|on(type: 'authResult', callback: Callback<{ deviceId: string, status: number, reason: number }>): void|新增|-|
|设备管理-DeviceManager|off(type: 'authResult', callback?: Callback<{ deviceId: string, status: number, reason: number }>): void|新增|-|
|设备管理-DeviceManager|on(type: 'serviceDie', callback: () => void): void|新增|-|
|设备管理-DeviceManager|off(type: 'serviceDie', callback?: () => void): void|新增|-|
|播放录制|createAudioPlayer(): AudioPlayer|新增|-|
|播放录制|AudioState|新增|-|
|播放录制|play(): void|新增|-|
|播放录制|pause(): void|新增|-|
|播放录制|stop(): void|新增|-|
|播放录制|seek(timeMs: number): void|新增|-|
|播放录制|setVolume(vol: number): void|新增|-|
|播放录制|reset(): void|新增|-|
|播放录制|release(): void|新增|-|
|播放录制|src: string|新增|-|
|播放录制|loop: boolean|新增|-|
|播放录制|readonly currentTime: number|新增|-|
|播放录制|readonly duration: number|新增|-|
|播放录制|readonly state: AudioState|新增|-|
|播放录制|on(type: 'play' / 'pause' / 'stop' / 'reset' / 'dataLoad' / 'finish' / 'volumeChange', callback: () => void): void|新增|-|
|播放录制|on(type: 'timeUpdate', callback: Callback<number>): void|新增|-|
|播放录制|on(type: 'error', callback: ErrorCallback): void|新增|-|
|音频管理|getAudioManager(): AudioManager|新增|-|
|音频管理|AudioVolumeType|新增|-|
|音频管理|MEDIA|新增|-|
|音频管理|RINGTONE|新增|-|
|音频管理|DeviceFlag|新增|-|
|音频管理|OUTPUT_DEVICES_FLAG|新增|-|
|音频管理|INPUT_DEVICES_FLAG |新增|-|
|音频管理|ALL_DEVICES_FLAG |新增|-|
|音频管理|DeviceRole |新增|-|
|音频管理|INPUT_DEVICE |新增|-|
|音频管理|OUTPUT_DEVICE |新增|-|
|音频管理|DeviceType |新增|-|
|音频管理|INVALID |新增|-|
|音频管理|SPEAKER |新增|-|
|音频管理|WIRED_HEADSET |新增|-|
|音频管理|BLUETOOTH_SCO |新增|-|
|音频管理|BLUETOOTH_A2DP |新增|-|
|音频管理|MIC|新增|-|
|音频管理|AudioRingMode |新增|-|
|音频管理|RINGER_MODE_NORMAL |新增|-|
|音频管理|RINGER_MODE_SILENT|新增|-|
|音频管理|RINGER_MODE_VIBRATE |新增|-|
|音频管理|setVolume(audioType: AudioVolumeType, volume: number,callback: AsyncCallback<void>): void|新增|-|
|音频管理|setVolume(audioType: AudioVolumeType, volume: number): Promise<void>|新增|-|
|音频管理|getVolume(audioType: AudioVolumeType, callback: AsyncCallback<number>): void|新增|-|
|音频管理|getVolume(audioType: AudioVolumeType): Promise<number>|新增|-|
|音频管理|getMinVolume(audioType: AudioVolumeType, callback: AsyncCallback<number>): void|新增|-|
|音频管理|getMinVolume(audioType: AudioVolumeType): Promise<number>|新增|-|
|音频管理|getMaxVolume(audioType: AudioVolumeType, callback: AsyncCallback<number>): void|新增|-|
|音频管理|getMaxVolume(audioType: AudioVolumeType): Promise<number>|新增|-|
|音频管理|getDevices(deviceFlag: DeviceFlag, callback: AsyncCallback<AudioDeviceDescriptors>): void|新增|-|
|音频管理|getDevices(deviceFlag: DeviceFlag): Promise<AudioDeviceDescriptors>|新增|-|
|音频管理|getRingerMode(callback: AsyncCallback<AudioRingMode>): void|新增|-|
|音频管理|getRingerMode(): Promise<AudioRingMode>|新增|-|
|音频管理|setRingerMode(mode: AudioRingMode, callback: AsyncCallback<void>): void|新增|-|
|音频管理|setRingerMode(mode: AudioRingMode): Promise<void>|新增|-|
|音频管理|isMute(volumeType: AudioVolumeType, callback: AsyncCallback<boolean>): void|新增|-|
|音频管理|isMute(volumeType: AudioVolumeType): Promise<boolean>|新增|-|
|音频管理|isActive(volumeType: AudioVolumeType, callback: AsyncCallback<boolean>): void|新增|-|
|音频管理|isActive(volumeType: AudioVolumeType): Promise<boolean>|新增|-|
|音频管理|isMicrophoneMute(callback: AsyncCallback<boolean>): void|新增|-|
|音频管理|isMicrophoneMute(): Promise<boolean>|新增|-|
|音频管理|mute(volumeType: AudioVolumeType, mute: boolean, callback: AsyncCallback<void>) : void|新增|-|
|音频管理|mute(volumeType: AudioVolumeType, mute: boolean): Promise<void>|新增|-|
|音频管理|setMicrophoneMute(mute: boolean, callback: AsyncCallback<void>): void|新增|-|
|音频管理|setMicrophoneMute(mute: boolean): Promise<void>|新增|-|
|音频管理|isDeviceActive(deviceType: DeviceType, callback: AsyncCallback<boolean>): void|新增|-|
|音频管理|isDeviceActive(deviceType: DeviceType): Promise<boolean>|新增|-|
|音频管理|setDeviceActive(deviceType: DeviceType, active: boolean, callback: AsyncCallback<boolean>): void|新增|-|
|音频管理|setDeviceActive(deviceType: DeviceType, active: boolean): Promise<boolean>|新增|-|
|音频管理|getAudioParameter(key: string, callback: AsyncCallback<string>): void|新增|-|
|音频管理|getAudioParameter(key: string): Promise<string>|新增|-|
|音频管理|setAudioParameter(key: string, value: string, callback: AsyncCallback<void>): void|新增|-|
|音频管理|setAudioParameter(key: string, value: string): Promise<void>|新增|-|
|音频管理|AudioDeviceDescriptor|新增|-|
|音频管理|readonly deviceRole: DeviceRole|新增|-|
|音频管理|readonly deviceType: DeviceType|新增|-|
|音频管理|AudioDeviceDescriptors |新增|-|
|语言编译器运行时-worker|postMessage(obj):void|新增|宿主线程与worker通信，传递数据|
|语言编译器运行时-worker|postMessage(message: Object, options?: PostMessageOptions):void|新增|宿主线程与worker通信，转移arrayBuffer的数据控制权|
|语言编译器运行时-worker|terminate():void|新增|宿主线程主动停止worker|
|语言编译器运行时-worker|on(type: string, listener: EventListener): void|新增|向worker添加回调接口|
|语言编译器运行时-worker|once(type: string, listener: EventListener): void|新增|向worker添加回调接口，并且在回调一次会释放回调|
|语言编译器运行时-worker|off(type: string, listener?: EventListener): void|新增|删除worker已添加的回调接口|
|语言编译器运行时-worker|addEventListener(type: string, listener: EventListener): void|新增|向worker添加回调接口|
|语言编译器运行时-worker|removeEventListener(type: string, listener?: EventListener): void|新增|删除worker已添加的回调接口|
|语言编译器运行时-worker|removeAllListener(): void|新增|删除worker所有的回调接口|
|语言编译器运行时-worker|dispatchEvent(event: Event): boolean|新增|向worker发送指定事件，触发回调接口|
|语言编译器运行时-parentPort|postMessage(obj):void|新增|worker与宿主线程通信，传递数据|
|语言编译器运行时-parentPort|postMessage(message: Object, options?: PostMessageOptions):void|新增|worker与宿主线程通信，转移arrayBuffer的数据控制权|
|语言编译器运行时-parentPort|close(): void|新增|worker主动终止|
|语言编译器运行时-Util|printf(format: string, ...args: Object[]): string|新增|-|
|语言编译器运行时-Util|getErrorString(errno: number): string|新增|-|
|语言编译器运行时-Util|callbackWrapper(original: Function): (err: Object, value: Object) => void|新增|-|
|语言编译器运行时-Util|promiseWrapper(original: (err: Object, value: Object) => void): Object|新增|-|
|语言编译器运行时-Util|new TextDecoder([encoding[, options]])|新增|-|
|语言编译器运行时-Util|decode([input[, options]]):string|新增|-|
|语言编译器运行时-Util|new TextEncoder()|新增|-|
|语言编译器运行时-Util|encode(input?: string): Uint8Array;|新增|-|
|语言编译器运行时-Util|"encodeInto(input: string,dest: Uint8Array,): { read: number; written: number };"|新增|-|
|语言编译器运行时-Util|readonly encoding: string;|新增|-|
|语言编译器运行时-Util|readonly fatal: boolean;|新增|-|
|语言编译器运行时-Util|readonly ignoreBOM = false;|新增|-|
|语言编译器运行时-Util|readonly encoding = "utf-8";|新增|-|
|语言编译器运行时-URL|new URL(url: string, base?: string/URL)|新增|-|
|语言编译器运行时-URL|toString(): string;|新增|-|
|语言编译器运行时-URL|toJSON(): string;|新增|-|
|语言编译器运行时-URL|new URSearchParams()|新增|-|
|语言编译器运行时-URL|new URSearchParams(string)|新增|-|
|语言编译器运行时-URL|new URSearchParams(obj)|新增|-|
|语言编译器运行时-URL|new URSearchParams(iterable)|新增|-|
|语言编译器运行时-URL|append(name: string, value: string): void;|新增|-|
|语言编译器运行时-URL|delete(name: string): void;|新增|-|
|语言编译器运行时-URL|entries(): IterableIterator<[string, string]>;|新增|-|
|语言编译器运行时-URL|forEach(callbackfn: (value: string, key: string, parent: this) => void, thisArg?: any,): void;|新增|-|
|语言编译器运行时-URL|get(name: string): string / null;|新增|-|
|语言编译器运行时-URL|getAll(name: string): string[];|新增|-|
|语言编译器运行时-URL|has(name: string): boolean;|新增|-|
|语言编译器运行时-URL|keys(): IterableIterator<string>;|新增|-|
|语言编译器运行时-URL|set(name: string, value: string): void;|新增|-|
|语言编译器运行时-URL|sort():void;|新增|-|
|语言编译器运行时-URL|toString():string|新增|-|
|语言编译器运行时-URL|values(): IterableIterator<string>;|新增|-|
|语言编译器运行时-URL|URSearchParams[Symbol.iterator]()|新增|-|
|语言编译器运行时-URL|hash: string;|新增|-|
|语言编译器运行时-URL|host: string;|新增|-|
|语言编译器运行时-URL|hostname: string;|新增|-|
|语言编译器运行时-URL|href: string;|新增|-|
|语言编译器运行时-URL|readonly origin: string;|新增|-|
|语言编译器运行时-URL|password: string;|新增|-|
|语言编译器运行时-URL|pathname: string;|新增|-|
|语言编译器运行时-URL|port: string;|新增|-|
|语言编译器运行时-URL|protocol: string;|新增|-|
|语言编译器运行时-URL|search: string;|新增|-|
|语言编译器运行时-URL|readonly searchParams: URLSearchParams;|新增|-|
|语言编译器运行时-URL|username: string;|新增|-|
|语言编译器运行时-ChildProcess|readonly pid: number;|新增|-|
|语言编译器运行时-ChildProcess|readonly ppid: number;|新增|-|
|语言编译器运行时-ChildProcess|readonly exitCode: number;|新增|-|
|语言编译器运行时-ChildProcess|readonly killed: boolean;|新增|-|
|语言编译器运行时-ChildProcess|wait(): Promise<number>;|新增|-|
|语言编译器运行时-ChildProcess|getOutput(): Promise<Uint8Array>;|新增|-|
|语言编译器运行时-ChildProcess|getErrorOutput(): Promise<Uint8Array>;|新增|-|
|语言编译器运行时-ChildProcess|close(): void;|新增|-|
|语言编译器运行时-ChildProcess|kill(signal: number): void;|新增|-|
|语言编译器运行时-process|runCmd(command: string,options?: { timeout : number, killSignal : number / string, maxBuffer : number }): ChildProcess;|新增|-|
|语言编译器运行时-process|getPid(): number;|新增|-|
|语言编译器运行时-process|getPpid(): number;|新增|-|
|语言编译器运行时-process|abort(): void;|新增|-|
|语言编译器运行时-process|on(type: string, listener: EventListener): void;|新增|-|
|语言编译器运行时-process|exit(code?:number): void;|新增|-|
|语言编译器运行时-process|cwd(): string;|新增|-|
|语言编译器运行时-process|chdir(dir: string): void;|新增|-|
|语言编译器运行时-process|getEgid(): number;|新增|-|
|语言编译器运行时-process|getEuid(): number;|新增|-|
|语言编译器运行时-process|getGid(): number|新增|-|
|语言编译器运行时-process|getUid(): number;|新增|-|
|语言编译器运行时-process|uptime(): number;|新增|-|
|语言编译器运行时-process|getGroups(): number[];|新增|-|
|语言编译器运行时-process|kill(signal?: number, pid?: number): boolean;|新增|-|
|升级服务子系统-Updater|checkNewVersion(): Promise<NewVersionInfo>;|新增|    -|
|升级服务子系统-Updater|rebootAndCleanUserData(callback: AsyncCallback<number>): void;|新增|    -|
|升级服务子系统-Updater|rebootAndCleanCache(): Promise<number>;|新增|    -|
|升级服务子系统-Updater|function getUpdaterFromOther(device: string, updateType?: UpdateTypes): Updater;|新增|    -|
|升级服务子系统-Updater|cancel(): void;|新增|    -|
|升级服务子系统-Updater|upgrade(): void;|新增|    -|
|升级服务子系统-Updater|off(eventType: 'downloadProgress', callback?: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|getUpdatePolicy(callback: AsyncCallback<UpdatePolicy>): void;|新增|    -|
|升级服务子系统-Updater|function getUpdaterForOther(device: string, updateType?: UpdateTypes): Updater;|新增|    -|
|升级服务子系统-Updater|setUpdatePolicy(policy: UpdatePolicy, callback: AsyncCallback<number>): void;|新增|    -|
|升级服务子系统-Updater|getNewVersionInfo(): Promise<NewVersionInfo>;|新增|    -|
|升级服务子系统-Updater|function getUpdater(updateType?: UpdateTypes): Updater;|新增|    -|
|升级服务子系统-Updater|applyNewVersion(callback: AsyncCallback<number>): void;|新增|    -|
|升级服务子系统-Updater|rebootAndCleanUserData(): Promise<number>;|新增|    -|
|升级服务子系统-Updater|off(eventType: 'verifyProgress', callback?: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|on(eventType: 'upgradeProgress', callback: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|checkNewVersion(callback: AsyncCallback<NewVersionInfo>): void;|新增|    -|
|升级服务子系统-Updater|on(eventType: 'downloadProgress', callback: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|getUpdatePolicy(): Promise<UpdatePolicy>;|新增|    -|
|升级服务子系统-Updater|download(): void;|新增|    -|
|升级服务子系统-Updater|off(eventType: 'upgradeProgress', callback?: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|getNewVersionInfo(callback: AsyncCallback<NewVersionInfo>): void;|新增|    -|
|升级服务子系统-Updater|on(eventType: 'verifyProgress', callback: UpdateProgressCallback): void;|新增|    -|
|升级服务子系统-Updater|verifyUpdatePackage(upgradeFile: string, certsFile: string): void;|新增|    -|
|升级服务子系统-Updater|setUpdatePolicy(policy: UpdatePolicy): Promise<number>;|新增|    -|
|升级服务子系统-Updater|rebootAndCleanCache(callback: AsyncCallback<number>): void;|新增|    -|
|升级服务子系统-Updater|applyNewVersion(): Promise<number>;|新增|    -|
|全球化子系统-I18n|getSystemLanguages(): Array<string>;|新增|    -|
|全球化子系统-I18n|getSystemCountries(language: string): Array<string>;|新增|    -|
|全球化子系统-I18n|isSuggested(language: string, region?: string): boolean;|新增|    -|
|全球化子系统-I18n|getSystemLanguage(): string;|新增|    -|
|全球化子系统-I18n|setSystemLanguage(language: string);|新增|    -|
|全球化子系统-I18n|getSystemRegion(): string;|新增|    -|
|全球化子系统-I18n|setSystemRegion(region: string);|新增|    -|
|全球化子系统-I18n|"getDisplayCountry(locale: string, displayLocale: string,sentenceCase?: boolean): string;"|新增|    -|
|全球化子系统-I18n|getSystemLocale(): string;|新增|    -|
|全球化子系统-I18n|setSystemLocale(locale: string);|新增|    -|
|全球化子系统-I18n|"getDisplayLanguage(locale: string, displayLocale: string,sentenceCase?: boolean): string;"|新增|    -|


