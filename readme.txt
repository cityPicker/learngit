Git is a distrubuted version control system.
Git is free software.

I am learning...

$ git init		//创建仓库
$ git add <file>	//添加到仓库
$ git commit -m "注释" 		//提交

$ git status		//查看仓库状态
$ git diff			//提交前查看difference

$ git log						//查看历史提交记录
$ git log --pretty=oneline		//查看历史提交记录精简版
$ git reset --hard HEAD			//还原到最新版本，HEAD表示最新版本
$ git reset --hard HEAD^		//回到最新版本的上一版本
$ git reset --hard HEAD^^		//回到最新版本的上一版本的上一个版本
$ git reset --hard HEAD~100		//回到倒数第100个版本
$ git reset --hard ecea			//会到版本号是ecea的版本
$ git reflog					//查看历史命令

creating a new branch quickly

在dev的工作，不保存没有提交

在101的工作会有dev的工作区内容，101要提交

$ git stash dev的文件保存了，修改没有提交也没有出现
