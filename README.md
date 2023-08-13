Version 20230813

# [install]
1. 第一次使用要先安裝 msodbcsql.msi
    - sqlodbc.exe需要這個dependency 
2. run generate_crendentials.exe
    - 按照指示輸入職編
    - 會在目錄下產生crendentials.txt
    使用時會檢查credentials.txt看使用者是否有註冊或是到期

# [usage]
- 主程式為autoload-gui-auth.exe
    - **F12**: 認證報告 並自動叫下一片
    - **scrolllock** : 叫出設定 選擇按F12是否要叫舊片 讀失敗時是否使用日期來叫片等
    - **alt + printscreen**: load 舊片 
    - **ctrl + printscreen**: load 舊片+報告

# [note]
- crendentials.txt要跟autoload-gui-auth.exe放在一起
- 目前只能跑在64bit系統
