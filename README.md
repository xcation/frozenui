### sass

写css代码用sass，win系统下需安装ruby

### grunt

[参考](https://github.com/QQVIPTeam/team/issues/5)

使用`grunt test`会编辑代码以及开启nico测试，访问[127.0.0.1:8000](127.0.0.1:8000)调试页面

使用`grunt --log=logtest` 命令会打包当前版本所需的包,生成如1.0.0的文件夹,生成站点以及svn提交，ftp同步，git提交

css ，css-debug和img目录是需要发布到线上，_css-debug_是未压缩的版本，为调试使用

i.gtimg.cn.zip需要发布到离线包

### nico 

用[nico](lab.lepture.com/nico/zh/)生成文档以及调试，`nico build `命令生成文档，`nico server `命令调试

### git

生成好的文档会在_site目录，提交当前目录到[https://github.com/frozenui/baseui.git](https://github.com/frozenui/baseui.git)

_site目录下的内容提交到gh-pages分支，参考[文档](https://help.github.com/articles/user-organization-and-project-pages)

页面会显示在frozen的css组件菜单项中[http://frozenui.github.io/baseui/](http://frozenui.github.io/baseui/)
