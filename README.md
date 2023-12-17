
# [download]
 最新版本 v20231005
 [下載](https://github.com/falcon0125/KMU-phrase-public/archive/refs/heads/main.zip)

# [第一次使用前]
1. 第一次使用要先安裝 msodbcsql.msi
    - sqlodbc.exe需要這個dependency 
2. 到 (https://kmu-phrase.puipui.rocks/) 抓自己的crendentials.txt放到autoload-gui-auth.exe同樣的目錄裡
   使用時會檢查credentials.txt看使用者是否有註冊或是到期
   要是有顯示過期或是錯誤就再來網站抓新的crendentials.txt
   
# [普通使用]
- 主程式為autoload-gui-auth.exe
    - **F12**: 認證報告 並自動叫下一片
    - **scrolllock** : 叫出設定 選擇按F12是否要叫舊片 讀失敗時是否使用日期來叫片等
        - load image using date: 用accession叫片失敗時用日期叫
        - health exam: 報告種類改成中文
        - get old film: 是否帶入舊影像
        - get old report: 是否帶入舊報告
    - **alt + printscreen**: load 舊片 
    - **ctrl + printscreen**: load 舊片+報告
    - **ctrl + D**: 上傳選定的series的lebal, annotation (本來ctrl+x的動作自動化), 會把window level回復到預設
# [note]
- crendentials.txt要跟autoload-gui-auth.exe放在一起
- 目前只能跑在64bit系統

# [changelog]
### version 20231217
 - crendentials.txt改至(https://kmu-phrase.puipui.rocks/)抓取

### version 20231030
 - [to fix] can not generate credential file

### version 20231005
 - fix calling sqlodbc.exe problem

### version 20231004
 - fix auth importing issue
 - add icon tooltip showing current version
 - 新增ctrl +D 上傳label
### Version 20230813
 - first version
