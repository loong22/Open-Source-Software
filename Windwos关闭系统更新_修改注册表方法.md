# 1. 打开注册表编辑器：

按 Win + R，输入 regedit，按回车，同意UAC提示。

# 2. 导航到指定路径：

定位到: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings

# 3. 创建DWORD(32位)

数值名称: FlightSettingsMaxPauseDays
数值数据(十六进制): 5000

# 4. 关闭注册表编辑器

打开Windows设置->更新和安全->Windows更新->高级选项->暂停更新截至日期(拉到最下面的一个日期就行)->返回就可以看到更新将在[你选择的日期]后恢复