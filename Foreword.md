> 针对Mac环境

## gitbook的安装与使用

  * 安装node.js

    在node.js官网下载，直接安装。下载地址：https://nodejs.org/en/。

  * 安装gitbook

    1）sudo npm install gitbook-cli -g

    2）gitbook -V（查看gitbook版本，注意v大写）

  * 初始化gitbook

    1）新建一个文件夹

    2）gitbook init //初始化目录文件

    3) gitbook build //生成静态网页

    4) gitbook serve // 生成静态网页并运行服务器

  * gitbook常用命令

    gitbook help //列出gitbook所有的命令

    gitbook --help //输出gitbook-cli的帮助信息
    
    gitbook build --gitbook=2.0.1 //生成时指定gitbook的版本, 本地没有会先下载

    gitbook ls //列出本地所有的gitbook版本

    gitbook ls-remote //列出远程可用的gitbook版本

    gitbook fetch 标签/版本号 //安装对应的gitbook版本

    gitbook update //更新到gitbook的最新版本

    gitbook uninstall 2.0.1 //卸载对应的gitbook版本

    gitbook build --log=debug //指定log的级别

    gitbook builid --debug //输出错误信息