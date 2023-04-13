
# [HighKer]

📦 基于 laravel 开发的一个社区社交的小程序

## 环境需求

- PHP >= 8.1
- [Composer](https://getcomposer.org/) >= 2.0

## 目录结构

highker-core highker 代码

highker-www laravel 项目主目录

highker-mini 小程序源码(代码 3 个人写的 后面写的有点垃圾)

## 注意事项

我用的服务器是新浪云 代码里的 websocket 什么的都是用的新浪云的服务 需要的话自己折腾吧

# highker-core

## 安装

```php

██╗  ██╗██╗ ██████╗ ██╗  ██╗██╗  ██╗███████╗██████╗ 
██║  ██║██║██╔════╝ ██║  ██║██║ ██╔╝██╔════╝██╔══██╗
███████║██║██║  ███╗███████║█████╔╝ █████╗  ██████╔╝
██╔══██║██║██║   ██║██╔══██║██╔═██╗ ██╔══╝  ██╔══██╗
██║  ██║██║╚██████╔╝██║  ██║██║  ██╗███████╗██║  ██║
╚═╝  ╚═╝╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
                                                    
highker-core version 1.0.0

Available commands:
highker:install     Install the highker package(安装 HighKer 扩展包)
highker:uninstall   Uninstall the highker package
highker:publish     发布 HigKer 路由，配置，迁移文件等。 如果要覆盖现有文件，可以添加--force选项
highker:seed        Seed the highker test data
```

## License

MIT