# vue-notes-example

## 准备vue范例项目
1. 添加 gitgub远程仓库
	- 在GitHub上创建新的 project
	- 选择node类型和mit规范
	- clone到本地
2. 初始化项目
	- yarn init
	- 创建index.html
3. 创建环境
	- 引入第三方工具
		- samantic-ui css样式
		- vue 
		- lokijs 数据库
	- 引入自定义
		- style.css 自定义样式
		- app.js 页面脚本
		- db.js 数据库配置
4. 创建服务器
	- yarn init -y
	- yarn add browser-sync --dev
	- package.js配置scripts属性
		- `start: "./node_modules/.bin/browser-sync start --server --no-notify --file='index.html, *.css, *.js'"`
	- yarn start
3. 上传push到github仓库
	- git status //查看仓库状态
	- git add . // 添加所有修改
	- git commit '准备vue范例' // 提交
	- git push origin master // 提交到远程


	
