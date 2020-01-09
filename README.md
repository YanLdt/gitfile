####Git-Tutorial

- git分为三个区域,四种状态
	- 三个区域：
		1. Woring directory

		-----git add👇

		2. Staging Area

		-----git commit👇

		3. Repository
	- 四个状态
		1. Untracked
		2. Staged
		3. Unmodified
		4. Modified

- 获取git仓库的方法
	
	- 本地新建：
		进入目录并输入	git init  即可

	- 克隆仓库
		git clone {url}  选择ssh方式不需要输入密码

- 提交：
	git add .
	git commit -m "commit"
	git push

- git命令

	1. git log 查看git日志
		git log --oneline
		git log --oneline --graph
	2. git status 查看git状态
	3. git diff 对比当前工作区和上一次commit版本库的区别
	4. git diff HEAD 对比当前暂存区和工作区的区别
	5. git checkout [版本号] 回到过去的commit
	6. git reset --hard HEAD/{版本号} 完全回到过去的commit
	
