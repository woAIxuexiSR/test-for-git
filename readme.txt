Git is a distributed version control system.
Git is free software.

git init
git add [filename]
git commit -m "content"

git status
git diff [filename]	//查看修改

git log		//查看版本库中版本
git log --pretty=oneline

git reset --hard HEAD^   (HEAD^^ HEAD~100)	//回退版本
git reflog                       //查看所有提交版本历史

git checkout -- [filename]       //撤销工作区的修改
git reset HEAD [filename]        //撤销暂存区的修改

git rm [filename]

git remote add origin git@github.com:[username]/[repository]
git push -u origin master	//第一次推送到远程库
git push origin master		//之后

git clone git@github.com:[username]/[repository]

git checkout -b dev		//创建分支并切换
git branch dev
git checkout dev		//切换分支
git branch			//查看当前分支
git merge dev			//合并分支
git branch -d dev		//删除分支
git branch -D dev		//强制删除未合并的分支

git stash			//关于隐藏当前工作（未尝试）
git stash list
git stash pop
