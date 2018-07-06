$初始化git仓库
	git init；

$查看目录信息
	git ls -a



$Git中文件的4种状态
	1.untracked  : 未被追踪
	2.Modified 	 : 表示工作区修改了某个文件但是还没有添加到暂存区
	3.Staged     : 表示吧工作区修改的文件添加到暂存区但还没有提交到版本库
	4.Committed  : 表示数据被安全的存储在本地仓库中。

$显示日志
	git log
	git log --pretty=oneline

$回退之前的版本(commit)
	第一种：git reset --hard HEAD^
	第二种：(使用回退多次提交之前的版本,n 代表回退几次之前) git reset --hard HEAD~n
	第三种：（如果当前窗口关闭重新打开了新窗口，使用如下命令回到指定版本）
			第一步：git reflog (查看版本号)
			第二步：git reset --hard 版本号

$撤销本次对文件中内容的修改(文件没有add之前)
	git checkout -- 文件名

$撤销本次对文件得修改(文件没有add之前)
	git checkout -- 文件名；

$删除文件(文件而不是文件夹)
	rm 文件名

$创建分支 
	git branch 分支名

$切换分支
	git checkout 分支名

$创建并且换分支
	git checkout -b 分支名

$$$$$$$$$$$$$