# 各 Android 手机厂商 Bootloader 解锁 / 内核开源 / 解锁后保修情况

> 本页面纯属本人临时起意整理，如有错漏欢迎 PR

- ✅ 支持/是 | **可点击**
- ⏹ 部分支持/部分开源/部分保修 | **可点击**
- ❌ 不支持/否
- -- 不详/无

| 品牌 | Bootloader 解锁 | 解锁等待时长（分钟） | Linux 内核开源 | 解锁后保修状态 | 备注 |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 360 手机 | ✅ | -- | ❌ | -- | -- |
| 酷派 (Coolpad) | ✅ | -- | ❌ | -- | -- |
| 荣耀 (HONOR) | ❌ | ❌ | [⏹](https://www.hihonor.com/global/opensource/) | -- | -- |
| 华为 (HUAWEI) | ❌ | -- | [⏹](https://consumer.huawei.com/en/opensource/) | ❌ | • 官方已关闭解锁渠道，部分早期机型可利用第三方服务解锁 |
| HTC | [✅](https://www.htcdev.com/bootloader/) | 3~15<br/>（秒解） | [✅](https://www.htcdev.com/devcenter/downloads) | ✅ | • 解锁需注册 HTCdev 账户<br/>• 提交后会在几分钟内（通常不超过 24 小时）将解锁文件发至邮箱 |
| 联想 (Lenovo) | [✅](https://www.zui.com/iunlock) | 3~1440<br/>（秒解） | ✅ | -- | • 提交后会在几分钟内（通常不超过 24 小时）将解锁文件发至邮箱 |
| 乐视 (Letv) | ✅ | -- | ❌ | -- | -- |
| LG | [❌](https://developer.lge.com/resource/mobile/RetrieveBootloader.dev) | -- | [✅](https://opensource.lge.com/index) | -- | • 官方解锁渠道已随手机业务同步下线 |
| 魅族 (MEIZU) | [❌](https://mroot.flyme.cn/) | ❌ | [⏹](https://github.com/meizuosc) | ❌ | • 官方仅支持 root，root 后 OTA 功能失效<br/>• 部分机型可利用第三方服务解锁<br/>• 仅少部分早期机型内核开源 |
| 摩托罗拉 (Motorola) | [✅](https://motorola-global-portal.custhelp.com/app/standalone/bootloader/unlock-your-device-a) | 3~1440<br/>（秒解） | [✅](https://github.com/MotorolaMobilityLLC) | ❌ | • 解锁后无法恢复出厂 `oem_locked` 状态<br/>• 解锁需绑定 My Moto Care<br/>• 提交后会在几分钟内（通常不超过 24 小时）将解锁文件发至邮箱 |
| 诺基亚 (Nokia) | ❌ | -- | [✅](https://www.nokia.com/phones/en_int/opensource) | ❌ | • 官方未提供解锁，可利用第三方工具解锁 |
| 努比亚 (nubia) | ✅ | -- | [⏹](https://github.com/ztemt) | -- | -- |
| 一加 (OnePlus) | ✅ | 0<br/>（秒解） | [✅](https://github.com/OnePlusOSS) | ✅ | • 无需申请解锁码，无任何解锁限制 |
| OPPO | [⏹](https://www.oppo.cn/thread-397164526-1) | 43200<br/>（1 月） | [✅](https://github.com/oppo-source) | ✅ | • 仅部分机型支持解锁 |
| 真我 (realme) | [⏹](https://www.realmebbs.com/post-details/1275426081138028544) | 3~15<br/>（秒解） | [✅](https://github.com/realme-kernel-opensource) | ✅ | • 仅部分机型支持解锁 |
| 三星 (Samsung) | ✅ | 0<br/>（秒解） | [✅](https://opensource.samsung.com/main) | ❌ | • 解锁 BL 将导致 KNOX 熔断，部分功能失效 |
| 索尼 (SONY) | [✅](https://developer.sony.com/develop/open-devices/get-started/unlock-bootloader) | 0<br/>（秒解） | [✅](https://github.com/sonyxperiadev/kernel) | ❌ | • 需申请解锁码 |
| 坚果 (Smartisan) | ✅ | -- | [⏹](https://github.com/SmartisanTech/SmartisanOS_Kernel_Source) | -- | • 缺少部分机型内核源码 |
| vivo | ⏹ | -- | [⏹](https://opensource.vivo.com/Project) | ❌ | • 官方未提供解锁，可利用第三方服务解锁<br/>• 缺少部分机型内核源码 |
| 小米 (Xiaomi) | [⏹](https://www.miui.com/unlock/index.html) | 10080\~172800<br/>（7 天\~2 月） | [⏹](https://github.com/MiCode) | ⏹ | • 仅小米与红米设备支持解锁，黑鲨官方不支持解锁<br/>• 解锁需手机插入 SIM 卡并绑定小米账号，等待时长从小米账号绑定之时起开始计算，随账号解锁次数增加，部分用户出现等待后不允许解锁的情况<br/>• 每账号每月仅允许解锁 1 次设备，每年仅允许解锁 4 次设备，重复绑定解锁单台设备重复计算解锁次数<br/>• 部分机型开源不完整或无提交历史记录（例如 MTK 机型），开源后内核源码不随系统更新<br/>• 秋大已离职，新设备开源进度十分缓慢<br/>• 解锁后主板等部分部件失去保内免费维修资格，刷机等操作易触发永久性熔断机制 |
| 中兴 (ZTE) | ✅ | -- | [✅](https://opensource.ztedevices.com/) | -- | -- |
