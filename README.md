# OurWorld Docker-Compose 部署

OurWorld 是一个轻量级的在线编程、分享平台

本仓库包含以下内容：
OurWorld 的docker-compose 部署文件,环境变量文件

## 示例

想了解社区效果，请参考 [OurWorld](https://ourworld.wuyuan.dev)。

## 安装

这个项目使用[docker](https://docker.com)，请确保你本地已经安装了它们。


### 配置环境变量

修改`.env`或手动配置环境变量
<br/>请务必不要同时使用环境变量与.env，请注意不要让项目与其他项目冲突
<br/>目前所有环境变量都必须配置

### 运行
```sh
$ docker-compose up -d
```


## 相关仓库

- [OurWorld](https://github.com/OurWorldOrg/OurWorld) — 项目主仓库
- [StaticFile](https://github.com/OurWorldOrg/StaticFile) — 静态文件仓库

## 开发者

[@SunWuyuan](https://github.com/sunwuyuan)
