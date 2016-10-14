---
title: Hexo
---

## Hexo安装
1. 全局安装Hexo--- npm install -g hexo
2. 初始化创建Hexo项目--- hexo init [hexo-name]
3. 切换到Hexo项目目录,运行 npm install 安装依赖
4. 启动Hexo服务器--- hexo server / hexo s

## Hexo配置文件
1. scaffolds:模块文件夹，Hexo三种默认布局：post、page和draft
2. source ：资源文件夹是存放用户资源的地方
3. source/_post ：文件箱
4. themes ：主题 文件夹
5. themes/landscape ：默认的皮肤文件夹
6. _config.yml ：全局的配置文件，每次更改要重启服务

## Hexo基本使用（常用命令）
1. 新建文章--- hexo new [layout] <title> /hexo n
2. 部署（将所有文章静态化处理）--- hexo generate / hexo g
3. 发布（需配置）--- hexo deploy / hexo d
	如果要发布到github，还需要配置 deploy 指令，
	安装 hexo-deployer-git ：npm install hexo-deployer-git -S