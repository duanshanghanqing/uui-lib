# 本地开发
    cd uui-lib
        npm link [添加软连接，即注册命令，这里node做了很多事,生成软连接，解析了package.js文件配置，把bin对象的key注册在全局环境变量中]
        npm unlink [删除软连接，即删除命令]

    把 package.js bin对象的key，即使 "uui-cli" 注册到全局环境变量

    之口在命令行工具即可执行 "uui-cli" 命令

# 生产使用

    把包发布到npm仓库

    npm install uui-cli -g

    安装到电脑

    之口在命令行工具即可执行 "uui-cli" 命令

