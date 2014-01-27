laravel-local-website
====================

本地化 laravel 官方网站 文档 API（方便网络异常时进行文档查阅）

- 延伸自官方开源项目 [laravel/website](https://github.com/laravel/website)
- 由于原项目在 windows 下安装存在诸多不便，因此略作修改。
- 由于官方项目有自己的部署需求，当前项目的改动不便并入分支，因此本项目作为新的项目独立发布。
- 有条件有能力的朋友建议直接使用原官方项目。

---

## 项目安装方法

> Git 克隆本项目  
> 在本地项目目录执行安装命令

    composer install

## 文档更新方法

> 直接在项目中更新子模块即可

![选择菜单](/public/assets/img/readme/tg-01.jpg "Optional title")

![全选更新](/public/assets/img/readme/tg-02.jpg "Optional title")

![更新结束](/public/assets/img/readme/tg-03.jpg "Optional title")

## API 文档更新方法

> 直接运行 `/api-update-win.sh` 文件即可
> 程序将自动完成 API 文档的更新
