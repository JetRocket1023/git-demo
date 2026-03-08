### 查版本
- git version	

### 建立基本資訊 全域資訊
- git config --global user.name Rock
- git config --global user.email rockman761023@gmail.com

### 初始化倉庫
- git init
- .git/(vs code出現的目錄)

### 控管狀態
- U ->Untrack (未追蹤)
- A ->Added (已加入)
- D ->Deleted (已刪除)
- M ->Modified(已修改的檔案)

### 加入控管
- git add 1.txt
- git add . (批量)
 

### 檢視狀態
- git status

### 恢復刪除
- git restore 1.txt

### 加入不控管的目錄
- 新增.gitignore

### 檢視暫存區狀態
- git ls-files -s

### 恢復上一動
- git checkout filename
- git checkout .

###加入倉庫
- git commit -m "專案初始化完成"

###檢視倉庫
- git log
- git log --online

	

### 分支的概念
- master(主分支)
- git branch

### 切換commit
- git checkout (commit-sha前5碼)
	- 觀察該版本的程式碼
- git checkout master


### 新增分支
- git branch (分支名)

### 切換分支
-git checkout (分支名)


### 合併分支
- git checkout master
- git merge test

### 刪除分支
- git branch -D test

### 申請github

###綁定到雲端
- git remote add origin https://github.com/JetRocket1023/git-demo.git

### 檢視雲端網址
- git remote -v

###推送到雲端
- git push
- git push -u origin master (第一次)

###從雲端拉取
- git pull

### VDCODE
- ctrl+shift+p
- 更改終端機
	-default terminal =>cmd.exe