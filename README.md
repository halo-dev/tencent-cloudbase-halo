<p align="center">
  <img height="100px" src="./logo.png" center />
</p>

# [Halo](https://github.com/halo-dev/halo)

Halo 是一款现代化的个人独立博客系统，给习惯写博客的同学多一个选择。

## 部署

本项目基于腾讯开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署。

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2Fhalo-dev%2Ftencent-cloudbase-halo&branch=master)

## 注意事项

1. 系统使用内置的 H2 Database，暂不支持使用 MySQL。
2. 工作目录保存在腾讯云提供的 CFS 上，在使用此方式创建应用的时候会要求创建 CFS。
3. 目前使用该方式部署，不支持修改[配置文件](https://docs.halo.run/zh/install/config)。
4. 费用相关请参考 [https://cloud.tencent.com/document/product/876/18864](https://cloud.tencent.com/document/product/876/18864)

## 文档

- [Halo 官方文档](http://docs.halo.run)
- [腾讯云开发文档](https://docs.cloudbase.net)
