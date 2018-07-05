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
