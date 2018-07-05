Git is a distributed version control system.
Git is free software.

git init
git add [filename]
git commit -m "content"

git status
git diff [filename]	//查看修改

git log		//查看版本库中版本

git reset --hard HEAD^   (HEAD^^ HEAD~100)	//回退版本
git reflog                       //查看所有提交版本历史

git checkout -- [filename]       //撤销工作区的修改
git reset HEAD [filename]        //撤销暂存区的修改
