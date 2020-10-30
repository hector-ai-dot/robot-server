全局安裝typescript: npm install -g typescript

vscode終端預設是powershell
（1）以管理員身份執行vscode或者powershell
（2）查詢Powershell詳細策略，在終端執行：get-ExecutionPolicy，顯示Restricted（禁止狀態）
（3）更新Powershell策略，在終端執行：set-ExecutionPolicy RemoteSigned
（4）再次查詢策略狀態，在終端執行：get-ExecutionPolicy，顯示RemoteSigned
更新執行策略，使其允許使用指令碼，即可解決“因為在此係統上禁止執行指令碼”問題！
