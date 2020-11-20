# resource
微信读书app资源文件

准备：
1.mysql新建localhost(login:root,password:root)-book数据库，导入book.sql数据；
2.配置nginx-1.19.2下的conf-nginx.conf文件；
3.resource文件夹放在桌面上；

开发环境启动：
1.进入nginx输入命令start nginx；
2.打开node-ebookshop输入命令npm install安装依赖包，node app.js；
3.打开Ebookshop输入命令npm install安装依赖包，npm run dev；

生产环境打包：
1.打开Ebookshop输入命令npm run build；
2.打开dist文件夹下的index.html；
