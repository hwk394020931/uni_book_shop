## 当前目录初始化成为git仓库
```
	git init
```

## 查看状态
``` 
	git status （文件颜色为黄色）
```

## 把所有的文件提交到索引去
```
	添加
	git add .  (文件颜色为绿色，需要过滤哪些文件可以在.gitignore中设置) 
	
	撤回
	git reset （还没commit 时，后面带文件名撤回一个，不带撤回全部）
```
## 提交清单
``` 
	git commit -m "add: 初始化项目"
	git status （commit后查看状态就会发现没有文件了）
```
## 推送到远程仓库
```
	创建关联
	git remote add origin url（git 仓库上的链接）
	查看是否与远程仓库建立关系
	git remote -v
	把代码推送到远程仓库
	git push -u origin master
	-u：是第一次推送要加。
	master： 远程仓库绑定的分支名称
```

