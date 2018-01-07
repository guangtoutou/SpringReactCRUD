# SpringReactCRUD

Backend (Spring Data REST):

spring-boot-devtools: 引入这个dependency，可以提高开发效率
    Automatic Restart: 修改java代码，重新编译后，Server自动重启
    LiveReload Server: 修改前端代码后，网页自动刷新(需配合Browser Extension)
    Remote application: 程序部署到remote server上，仍然可以本地进行debug
    
h2-console: spring boot集成了h2的支持，访问地址localhost:8080/h2-console
Lombok：Entity类不用再写getter和setter啦



Frontend (React):
frontend-maven-plugin: 运行maven build时，自动执行webpack将前端资源打包
Chrome LiveReload extension: 与Spring boot自带的LiveReload Server配合，实现修改前端代码后，网页自动刷新
webpack:前端开发人员修改代码后，只需要运行webpack命令，就会重新将前端资源打包，例如编译生成bundle.js
