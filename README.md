# FreeOpennSourceSoftware
School study records.\n

## resources
課本: git-learn-git\n

Git 練習場: https://gitbook.tw/playground\n


### date: 09262023
Git 之 SHA-1 與四大物件:\n
    \tBlob, Tree, Commit, Tag: 講義 (git-learn-git.pdf) 頁數: 99-129

#### 作業_1:
HW02A git (II): git 分支:\n
    \t練習 6.1 ~ 6.4 指令\n

HEAD: 目前所在分支。\n
SHA-1 編碼: 生成不同的 commit 身份證號，區分commit。\n

指令:\n
git commit\n
    \t新增一個commit（圓圈）。將暫存區裡的檔案，儲存到Repository。灰色圆圈為已完成commit內容的記錄;緣色圆圈為最新的commit記錄。
    ![commit](./picture/commit.png)

git branch branch_name\n
    \t新增一個分支（方塊）。\n

git checkout branch_name\n
    \t將 HEAD 跳轉至指定分支。\n
    ![branch](./picture/branch.png)

git merge branch_name\n
    \t將 指定分支 合併至 HEAD 分支。\n
    ![merge_合併前](./picture/merge_1.png)
    ![merge_合併後](./picture/merge_2.png)

git tag tag_name\n
    \t將 HEAD 所在 commit 加上 tag。\n
    ![tag](./picture/tag.png)

git reset HEAD^\n
    \t跳轉回 HEAD 上級之 commit，一個 '^' 跳一級。\n
    ![reset前](./picture/reset_1.png)
    ![reset後](./picture/reset_2.png)

git rebase branch_name\n
    \t將 HEAD 所在分支，串接至指定分支後方。\n
    ![rebase前](./picture/rebase_1.png)
    ![rebase後](./picture/rebase_2.png)

git revert commit_name\n
    \t將指定 commit(黃) 刪除，並生成該操作的新紀錄 commit（綠）。\n
    ![revert前](./picture/revert_1.png)
    ![revert後](./picture/revert_2.png)

解答: https://moodle.thu.edu.tw/pluginfile.php/1604525/mod_label/intro/open-git2-example.png \n

#### 作業_2:
HW02B git (II): git 分支練習場\n
    \t以branch, checkout, commit, reset指令，在練習場產生以下樹狀圖\n
    ![範例](./picture/exampleTree.png)
    ![結果](./picture/resultTree.png)

