#github 三要素#
##Reposity仓库##
*仓库是github项目管理储存的基本单位*
*一个仓库中储存一个项目，一个用户可以拥有多个仓库，一般仓库分为public，private*













#设备认证#
##1.如何让网站的账户与设备绑定，后续完成代码的管理，上传下载##
*git init                                    //创建本地仓库*
*git config --list                           //查看git的配置文件*
*git config --global user.email"邮箱"*
*git config --global user.name"用户名"*
*ssh-keygen -t rsa -C "注册邮箱"            //创建本地密文*
<br>
*rsa.pub 复制密文，粘贴 setting->SSH key and CPG -> new ssh key ->粘贴*
*ssh -T git@github.com                       //测试关联是否成功*

##2.为目标仓库起别名，定位目标仓库，后续上传##
*git remote add orgin "ssh地址"             //为ssh仓库地址创建别名orgin*
*git remote remove orgin                    //删除orgin别名*
*git remote add orgin "ssh地址"             //为ssh仓库地址创建别名为orgin*           
