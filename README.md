# copyExpress
A copypage test with Express 4.0 + jade + stylus

###任务描述：###
使用 express 4.x 的jade+stylus复制页面 *https://campaigns.jimubox.com/mobile-guide/redbag/* 

###准备工作：###
已安装Node.js  
**npm install -g express** (全局安装)  
**express copyExpress -c stylus** （创建express项目，express默认支持jade，-c用来指定stylesheet <engine> 为 stylus）  

此repository为实现功能后的项目文档

###查看方式：###
**set DEBUG=myapp & npm start** （windows系统，在根目录下）  
**DEBUG=myapp npm start** （类Unix系统，在根目录下）  
之后在浏览器输入*http://localhost:3000/* 查看结果  
