git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/xielifei/a.git
git push -u origin master


�������$ git remote add origin git@github.com:djqiang��github�ʺ�����/gitdemo����Ŀ����.git 

    ��ʾ������Ϣ��fatal: remote origin already exists.

    ����취���£�

    1��������$ git remote rm origin

    2��������$ git remote add origin git@github.com:djqiang/gitdemo.git �Ͳ��ᱨ���ˣ�

    3���������$ git remote rm origin ���Ǳ���Ļ���error: Could not remove config section 'remote.origin'. ������Ҫ�޸�gitconfig�ļ�������

    4���ҵ����github�İ�װ·�����ҵ���C:\Users\ASUS\AppData\Local\GitHub\PortableGit_ca477551eeb4aea0e4ae9fcd3358bd96720bb5c8\etc

    5���ҵ�һ����Ϊgitconfig���ļ��������������[remote "origin"]��һ��ɾ���ͺ��ˣ�