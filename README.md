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

### ☕️ 加我微信(备注来意)、加入微信群聊、请我一杯咖啡(如果你觉得对你有帮助thanks)

<img src="https://github.com/user-attachments/assets/240deabc-1f0d-4a21-bebb-0947d8169326" width="210px">
<img src="https://github.com/user-attachments/assets/1549eead-0b1f-4013-800d-cec3a332b3ec" width="210px">
<img src="https://github.com/user-attachments/assets/d1cdac40-01ce-4669-ad8d-55ff814a1e24" width="210px">


### ⚠️ 注意事项
- ❗ 使用风险请自行承担
本模块仅供研究与安全分析用途，禁止用于非法活动。
