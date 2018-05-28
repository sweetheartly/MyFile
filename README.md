欢迎来到虫虫的小窝 ~   以下是虫虫学习剑指Offer的笔记呢~

### Follow me ！
```js
添加远程库：
git remote add origin git@github.com:sweetheartly/xx.git

生成ssk：
ssh-keygen -t rsa -C "youremail@example.com"

在~/下生成.ssh文件夹，进去，打开 id_rsa.pub，复制里面的 key。  回到 github 上，进入 Account => Settings（账户配置）。

验证是否成功：
ssh -T git@github.com

初始化：
git init

添加文件(单文件)：
git add README.md

提交并备注信息:
git commit -m "添加README.md信息"

提交到Github:
git push -u origin master
```

```js
查看当前的远程库:
git remote
git remote -v

提取远程仓库：
从远程仓库下载新分支与数据:
git fetch

从远端仓库提取数据并合并到当前分支：
git merge

推送到远程仓库：
git push origin master

删除远程仓库：
git remote rm -v
git remote add origin2 git@github.com:sweetheartly/xx.git
git remote -v origin2
git remote -v

删除仓库 origin2：
git remote rm origin2 git remote -v
```
