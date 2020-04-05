# git

在git bash中，可以使用touch+文件名，新建一个文件。
使用`git add`将工作区的文件添加到暂存区。
再将暂存区的文件提交到仓库中，`git commit -m`

修改后，仍然需要add和commit来重新提交上去。

使用git命令`git rm`删除仓库文件。

注意这里的都是本地仓库，而不是远程仓库。

最后提交到网上的仓库是远程仓库

## git push

如何将本地仓库同步到git远程仓库中？  

三步走：  

第一步使用`git add`将工作区的文件发送到暂存区；
然后使用`git commit`将暂存区的文件提交到本地仓库中；
最后使用`git push`将本地仓库的文件提交到远程仓库。

## git clone

git clone：将远程仓库（github对应的项目）复制到本地