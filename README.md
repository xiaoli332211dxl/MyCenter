# MyCenter
spring知识点学习
上图已经写清楚了Github上传项目的方法，有两种方法：一种通过https，一种通过ssh。
我刚开始是使用ssh的方法，不过一直报错，就直接换了https方法，这次一次就成功了。
第四步：因为GitHub是基于git实现的代码托管，所以git是少不了的。我们要确认电脑上安装了git，没有安装的，就去安装git。至于安装方法，就自行百度吧。
第五步：新建Test文件夹，里面添加几个文件。右击Test文件夹根目录，点击“Git Bash Here”，打开git命令行。
第五步：按照github新建仓库上的文档提示，提交项目：
1.在命令行中，输入“git init”，使Test文件夹加入git管理；
2.输入“git add .”（不要漏了“.”），将Test文件夹全部内容添加到git。
3.输入“git commit -m "first commit"”（“git commit -m "提交信息"”
）
4.输入“git remote add origin https://github.com/shench5612390/Test.git”（git remote add origin 你自己的https地址），连接你的guthub仓库。
5.输入“git push -u origin master”，上传项目到Github。这里会要求输入Github的账号密码，按要求输入就可以。
