# github 三要素<br>
## Reposity仓库<br>
* 仓库是github项目管理储存的基本单位<br>
* 一个仓库中储存一个项目，一个用户可以拥有多个仓库，一般仓库分为public，private<br>





# 设备认证<br>
## 1.如何让网站的账户与设备绑定，后续完成代码的管理，上传下载<br>
* git init                                    //创建本地仓库<br>
* git config --list                           //查看git的配置文件<br>
* git config --global user.email"邮箱"<br>
* git config --global user.name"用户名"<br>
* ssh-keygen -t rsa -C "注册邮箱"            //创建本地密文<br>
---
* rsa.pub 复制密文，粘贴 setting->SSH key and CPG -> new ssh key ->粘贴*<br>
* ssh -T git@github.com                       //测试关联是否成功*<br>

## 2.为目标仓库起别名，定位目标仓库，后续上传##<br>
* git remote add orgin "ssh地址"             //为ssh仓库地址创建别名orgin<br>
* git remote remove orgin                    //删除orgin别名<br>
* git remote add orgin "ssh地址"             //为ssh仓库地址创建别名为orgin<br> 

---
> 一级引用
>> 二级引用
>>>三级引用
>>>>四级引用

## 列表修饰符
### 无序列表 \*
* 二次元游戏
  * 原神
   * 神力凌华
* 大逃杀类
  * PUBG
  * APEX
### 有序列表
1. 物理学
   1. 粒子物理
   2. 原子核物理
   3. 凝聚态物理
2. 计算机科学
   1. 分布式架构
   2.云计算
## 混合列表
1. 测试一级
   * 测试二级
   2. 测试三级
---
## 代码片段
```c
      #include<stdio.h>
```

```cpp
      #include<iostream>
```

``` python
          import <os>
```

```bash
       echo "测试"
       pwd
```


