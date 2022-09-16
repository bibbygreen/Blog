# Git 相關指令

## Git初始化與提交


```
git init  //初始化數據庫
git status  //查看 git 狀態
git add .  //將當前資料夾內檔案加入索引
git diff  //查看工作目錄與索引內檔案的不同
git commit -m “修改內容”  //提交更新
```


## Git 切換、還原與查看紀錄
```
git checkout  //HEAD 切換
git log  //查看 commit 歷史紀錄
git reflog  // 查看 commit 詳細歷史紀錄
git log — oneline -graph  //觀看線圖

```


## Git 分支與合併
```
git branch  //查看分支
git branch <分支名稱>  //git branch <分支名稱>
git branch -d <分支名稱>  //git branch -d <分支名稱>
git checkout <分支名稱>  //切換到指定分支最新版本
git merge <分支名稱>  //git merge <分支名稱>


```
