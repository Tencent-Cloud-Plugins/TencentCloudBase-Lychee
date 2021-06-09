<p align="center">
  <img height="100px" src="./lychee.jpeg" />
</p>

# [Lychee.jpeg](https://github.com/electerious/Lychee)

Lychee是一个开源的照片管理系统，能方便管理和共享照片。

## 部署

本项目基于开源应用中心 [oac](https://app.cloud.tencent.com/) 开发部署，支持一键云端部署


[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2Fjjasonzhang0215%2FTencentCloudBase-Lychee&branch=master)

### 配置

- `PUID`：PUID
- `PGID`：PGID
- `DB_CONNECTION`：数据库连接方式


### 依赖

- CFS：使用 CFS 持久化存储数据
> lychee-cfs-conf:lychee数据库文件
> lychee-cfs-sym:lychee系统文件
> lychee-cfs-upload:lychee上传目录文件

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
