基本指令
 留言
git init：創建一個 git 資料夾（初始化），裡面有預先配置好的東西
rm -r .git：刪除 git
rm -rf .git：刪除 git 包含裡面的檔案
git status：顯示目前 git 狀態
決定是否加入版本控制
有兩種狀態：
untracked：沒有加入版本控制的檔案、staged：要加入版本控制的檔案
test
git add code.js：將 code.js 加入版本控制
git add .：將目前資料夾底下所有的檔案都加入版本控制
git rm –cached code.js：將 code.js 移回 untracked 狀態
新建版本
git commit：進入 vim 編輯器，輸入對該版本的敘述（:q 退出；:wq 存檔退出）
git commit -m "first commit"：新建一個版本名稱叫 first commit
git commit -am "first commit"：新建一個版本名稱叫 first commit 且將當前資料夾底下所有檔案都加入版本控制