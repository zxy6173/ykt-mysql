# 连接并实现mysql数据库的操作

## 配置数据库连接地址

    在package.json文件中配置数据库的连接地址和数据库名。配置方法如下：

    package.json文件：

    {
        ...
        "db": {
            "url": "localhost",
            "port": "3306",
            "user": "root",
            "password": "ykt",
            "database": "demo"
        },
        ...
    }