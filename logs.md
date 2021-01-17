1. 
git status    检查git状态
位于分支 master

尚无提交

无文件要提交（创建/拷贝文件并使用 "git add" 建立跟踪）

2.
touch learn.txt


未跟踪的文件:
  （使用 "git add <文件>..." 以包含要提交的内容）

3. 
 git add .

提交的变更：
  （使用 "git rm --cached <文件>..." 以取消暂存）
	新文件：   learn.txt

4. 
git commit -m "create learn.txt"
[master（根提交） b18cda9] create learn.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 learn.txt

5.
git status
位于分支 master
无文件要提交，干净的工作区


已修改 --- git add ---> 已暂存 --- git commit ---> 已提交
工作区                  暂存区                     Git仓库

git log 显示历史所有提交记录