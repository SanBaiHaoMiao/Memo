win+r  → 输入：regedit

HKEY_LOCAL_MACHINE → SOFTWARE → Microsoft → WindowsUpdate → UX → Settings

右边空白区域 → 右键 → 新建 → DWORD（32位）值 → 重命名为：FlightSettingsMaxPauseDays → 双击打开 → 选择十进制 → 在数值数据框内输入天数（据说最好是2的次方，可以避免卡顿，比如4096）