## git学习笔记
------
### 分支管理
1. 创建分支

	```
	git branch dev
	```

2. 切换分支

	```
	git checkout dev
	```

3. 创建&切换分支

	```
	git checkout -b dev
	```

4. 删除分支

	```
	git branch -d sub
	```
	
5. 合并分支

	1. 切到待合并分支上
	2. git pull 最新线上代码
	3. 合并代码```git merge dev```
	4. ```git push```

### 标签管理
1. 创建标签

```
git tag v1.0
```

2. 操作标签

```	
git show v1.0	
```

3. 对已提交的打标签

```git tag v1.1 1234567```


