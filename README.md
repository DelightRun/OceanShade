#OceanShade

OceanShade是我基于[greyshade](https://github.com/shashankmehta/greyshade)修改的自用Octopress主题

预览效果详见我自己的博客[Changxu's Blog](http://changxu.wang)

##新特性

+ 左边栏颜色改成漂亮的渐变色，宽度略加宽，并重新布局
+ 去掉twitter相关的部分以解决在国内加载慢的问题
+ 添加新浪微博，使用时请在`_config.yml`文件加入`weibo_user: 你的微博名或ID`

##安装说明

在Ubuntu下键入以下命令（假设你以搭建好自己的Octopress）

    $ cd /path/to/your/blog/
    $ git clone https://github.com/DelightRun/OceanShade.git .themes/OceanShade
    $ rake "install[OceanShade]"
    $ rake generate
    $ rake preview # 预览
    $ rake deploy # 部署

其他设置可自行修改`_config.yml`文件
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
