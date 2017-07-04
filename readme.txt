目录结构:
	api
	controllers(控制器相关，业务逻辑)
	models(模块开发)
	policies(用于路由过滤)
	responses(定制所需的响应:如404 res.notFound())
	services(定制一些常用的工具类–全局的)
	assets(静态资源文件)
	images
	js
	styles
	templates
	favicon.ico
	config(整个项目的配置文件系统)
	env(配置不同环境的变量)
	*.js
	tasks
	views

安装

1、npm -g install sails
2、sails new sailsProject
3、cd sailsProject

运行：node app.js
访问：http://localhost:1337

sails中文文档：http://sailsdoc.swift.ren/
sails英文文档：http://sailsjs.com/
