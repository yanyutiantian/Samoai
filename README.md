# Samoai
一款开源的，使用Java编写的AI程序，可以使用Openai(或兼容Openai)的Api网关，可以导入或使用Silly Tavern(酒馆)角色卡(v2格式)，此应用完全由AI Agent开发
web文件夹为服务端 api.js使用node /admin是api后端
搭建步骤
一、服务端
1. api.js 
1.1在 api.js 修改你允许的模型或者修改api反代(当前使用硅基流动)
1.2去你的硅基流动或者其他api平台添加Key
1.3运行起 api.js 会自己创建数据
2. /admin/imdex.html
2.1使用nginx对准你当前 api.js 的文件夹
2.2访问 http/https://你的域名/IP/admin
2.3添加你在API平台添加的Key 并充值余额
二、客户端
1. 手机编译客户端
1.1项目使用Java7开发，手机使用Aide Pro打包
1.2修改 ApiConfig.java 的 BASE_URL 为你的反代
1.3打包运行测试
2. 电脑编译客户端
2.1打开Android student
2.2导入项目
2.3请看上面的 1.2 修改
2.4 打包运行测试
