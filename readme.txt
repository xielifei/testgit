git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/xielifei/a.git
git push -u origin master


git diff 文件名   //查看文件的更改
git log          //查看修改记录
git reset  --hard HEAD^   //回到上一个版本


退回最新版本
git reflog     //找到版本号
git reset  --hard 版本号 


如果输入$ git remote add origin git@github.com:djqiang（github帐号名）/gitdemo（项目名）.git 

    提示出错信息：fatal: remote origin already exists.

    解决办法如下：

    1、先输入$ git remote rm origin

    2、再输入$ git remote add origin git@github.com:djqiang/gitdemo.git 就不会报错了！

    3、如果输入$ git remote rm origin 还是报错的话，error: Could not remove config section 'remote.origin'. 我们需要修改gitconfig文件的内容

    4、找到你的github的安装路径，我的是C:\Users\ASUS\AppData\Local\GitHub\PortableGit_ca477551eeb4aea0e4ae9fcd3358bd96720bb5c8\etc

    5、找到一个名为gitconfig的文件，打开它把里面的[remote "origin"]那一行删掉就好了！