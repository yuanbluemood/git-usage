# git-usage
git 日常使用方法

###git - 简明指南
http://rogerdudler.github.io/git-guide/index.zh.html

###使用github托管静态网站
http://jekyllcn.com/

###markdown的语法
https://github.com/guoyunsky/Markdown-Chinese-Demo

#
#

#####在远程仓库添加本机的pub文件到sshkey，然后在本机添加源
git init
git remote add origin git@github.com:yuanbluemood/django-fig.git
#####更新最新到本地
git fetch origin
git reset --hard origin/master
#####提交更新
git add .&&git commit -m 'test markdown'&&git push origin master
