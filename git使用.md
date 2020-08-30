## git使用

```
首先配置用户信息
	git config --global user.email "weiyandong2012@163.com"
	git config --global user.name "wydcarlos"

拷贝远程代码到本地
	git clone 代码地址  本地文件夹
	git clone https://github.com/wydcarlos/mycode.git notebook

增加到本地版本管理
	git add myfirst.txt  把某个文件添加到本地仓库
	git add .  把当前文件夹下的所有文件添加到本地仓库

提交
	git commit  提交到本地

提交到远程
	git push   提交到远程服务器

更新本地
	git pull 获取远程服务器上的代码到本地

查看状态
	git status 查看当前目录的状态

查看历史记录
	git log 查看详细历史记录
	git log --pretty=oneline 简要显示历史信息

回滚
	git reset --hard HEAD^
	git reset --hard HEAD^^
	
	git reset --hard 124324324  回滚到版本id为124324324开头的版本
	
	git reflog 记录每一次命令
```

```
暂存区 work directory
	git add .  就是把代码先放在暂存区
	git commit 就是把暂存区的代码提交到服务器上
	
撤销暂存区
	git restore --statge filename 从暂存区撤销

删除文件
	git status 可以查看
	git rm filename
	git commit -m 'message'
```

