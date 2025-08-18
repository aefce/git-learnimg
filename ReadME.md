git--version'檢查git版本'
git config --global user.name "your name" '設定使用者姓名'
git config --global user.email "your email"'設定使用者信箱'
git init'建立git歷史資料儲存庫'
git status'檢查目前檔案狀況'
### 檔案狀態
#### Untracked-->尚未進入於git中
####    使用 "git add +檔名"將檔案放入Staged  
####    使用 "git add ."將所有變更檔案放入Staged  
#### Staged-->暫存區
####    使用 'git commit -m"說明文字"'將檔案放入  Staged    
#### Commited-->提交
#### Tracked-->進入於git
git log "提交歷史(作者+日期+說明文字)"
q 退出 log
git log --oneline "便於瀏覽"
git diff gitid -- 檔名 "先是現今版本與當時版本差異"
git checkout gitid -- 檔名 "回復當時版本(記得要再commit)"
git reset --hard gitid"回復當時版本並清除此版本之後所有資料(不可逆)"
#### 如果有將整個檔案刪除，仍需進行add+commit記錄檔案狀態變化
#### 如有不需儲存的資料時，可新增".gitignore"的檔案，並將要忽略儲存的檔名紀錄其中

