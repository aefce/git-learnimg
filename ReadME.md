#### git--version'檢查git版本'
#### git config --global user.name "your name" '設定使用者姓名'
#### git config --global user.email "your email"'設定使用者信箱'
#### git init'建立git歷史資料儲存庫'
#### git status'檢查目前檔案狀況'
### - - -
### 檔案狀態
#### Untracked-->尚未進入於git中
####    使用 "git add +檔名"將檔案放入Staged  
####    使用 "git add ."將所有變更檔案放入Staged  
#### Staged-->暫存區
####    使用 'git commit -m"說明文字"'將檔案放入  Staged    
#### Commited-->提交
#### Tracked-->進入於git
### - - -
#### git log "提交歷史(作者+日期+說明文字)"
#### q 退出 log
#### git log --oneline "便於瀏覽"
#### git diff gitid -- 檔名 "先是現今版本與當時版本差異"
#### git checkout gitid -- 檔名 "回復當時版本(記得要再commit)"
#### git revert gitid 撤銷提交
#### git reset --hard gitid"回復當時版本並清除此版本之後所有資料(不可逆)"
#### 如果有將整個檔案刪除，仍需進行add+commit記錄檔案狀態變化
#### 如有不需儲存的資料時，可新增".gitignore"的檔案，並將要忽略儲存的檔名紀錄其中
#### 將github提供的三段程式碼貼上終端機
#### git remote add origin +你的網址
#### git branch -M main
#### git push -u origin main
#### git push "更新新內容至githud"
### - - -
### 說明共編事宜
#### git clone +網址
#### cd 至要更改檔案 
#### git pull 將更新內容載入本地端
#### git pull origin main 動手前，先同步
#### git branch 知道自己所在分支
#### git checkout -b +新分支名稱
#### git push +遠端名稱 +本地名稱(新分支名稱) 分支要上傳github
### - - -
##### 此資料參考 https://www.youtube.com/watch?v=FKXRiAiQFiY

