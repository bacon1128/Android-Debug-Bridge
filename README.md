# PC端
  - download 'platform-tools'
  - 把資料夾放在C槽
  - 設定 → 關於 → 進階系統設定 → 環境變數 → Path → 編輯 → 新增 → C:\platform-tools
# 手機端
  - 安裝'Application Inspector'(用於查看 <package_name>)
  - 開發人員選項 → USB偵錯
# 執行步驟
  - 用電腦開啟CMD
  - 輸入 adb devices
# 相關指令
  - 刪除指令：adb shell pm uninstall -k --user 0 <package_name>
  - 停用指令：adb shell pm disable-user <package_name>
  - 啟用指令：adb shell pm enable <package_name>
