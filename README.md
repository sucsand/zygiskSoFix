# zygiskSoFix
Fix target ELF File via Zygisk. Only supports arm64

### ⚙️ 功能简介
- ⚡ 从内存中修复指定so文件
- 📱 适用于已 **Root** 的 Android 设备，要求 **Magisk** 、**KernelSU**、**Apatch** 已启用**Zygisk 环境**。

### 🍽️ 安装与使用步骤

```bash
1. 前往项目仓库：https://github.com/sucsand/ZygiskSoFix，进入 Release 页面下载最新的 ZIP 安装包。

2. 将 ZIP 文件推送到手机，在 Magisk 、KernelSU、Apatch 中刷入该模块。

3. 刷入完成后重启手机，系统将自动安装 `sucsand.apk`。
   - 打开 App，勾选你需要注入的目标 App；
   - 第一个框填写so名称。
   - 第二个框填写延迟时间，建议设置启动延迟为 300ms 以提升注入稳定性。
```

勾选后，启动目标 App。手机端进入shell执行以下命令。
```
logcat |grep ZygiskSoFix
```