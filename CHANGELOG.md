# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.6.0] - 2022-02-14
### 新增
* 配置编辑支持自定义参数(#12)
* 打开配置文件入口
* 项目编辑可生成随机名称
* 复制服务器地址入口
* 添加`connect_server_local_ip`，`http_proxy`，`user`编辑入口

### 优化
* 减少不必要的视图更新
* 优化系统缩放时的界面显示

### 更新
* FRP 版本 0.39.1

## [1.5.0] - 2022-01-05
### 更新
* FRP 版本 0.38.0

## [1.4.2] - 2021-09-08
### 新增
* 可单独设定配置的服务启动方式(手动/自动)(#9)

### 修复
* 修复某些情况下无法查看服务的异常

## [1.4.1] - 2021-09-07
### 新增
* 支持配置xtcp/stcp类型(#8)
* 添加自定义选项支持
* 查看服务属性入口(#9)

### 更新
* FRP 版本 0.37.1

## [1.4.0] - 2021-07-12
### 修复
* 修复日志文件的卸载错误提示

### 更新
* FRP 版本 0.37.0

## [1.3.2] - 2020-12-16
### 新增
* 支持双击编辑

### 优化
* 小幅UI优化

## [1.3.1] - 2020-12-16
### 新增
* 添加文件版本信息

### 修复
* 修复卸载程序时的DLL错误

## [1.3.0] - 2020-12-13
### 新增
* 添加关于页面
* 支持导出配置文件

### 优化
* 日志实时显示
* 小幅UI优化

### 修复
* 修复卸载时日志文件无法删除的问题

## [1.2.5] - 2020-12-03
### 优化
* 小幅 UI 逻辑优化
* 相关日志文件重命名/删除

### 修复
* 修复 Windows 7 下的闪退问题(#2)

## [1.2.4] - 2020-08-17
### 新增
* 添加自定义DNS服务器的支持，对于使用动态DNS的服务器可以减少离线时间

### 修复
* 修复了一些编译错误

## [1.2.3] - 2020-05-24
### 修复
* 解决某些情况下电脑重启后服务没有自动运行问题
* 更新软件后需打开软件，选择左侧配置项后右键编辑，然后直接确定，再启动即可

[Unreleased]: https://github.com/koho/frpmgr/compare/v1.6.0...HEAD
[1.6.0]: https://github.com/koho/frpmgr/compare/v1.5.0...v1.6.0
[1.5.0]: https://github.com/koho/frpmgr/compare/v1.4.2...v1.5.0
[1.4.2]: https://github.com/koho/frpmgr/compare/v1.4.1...v1.4.2
[1.4.1]: https://github.com/koho/frpmgr/compare/v1.4.0...v1.4.1
[1.4.0]: https://github.com/koho/frpmgr/compare/v1.3.2...v1.4.0
[1.3.2]: https://github.com/koho/frpmgr/compare/v1.3.1...v1.3.2
[1.3.1]: https://github.com/koho/frpmgr/compare/v1.3.0...v1.3.1
[1.3.0]: https://github.com/koho/frpmgr/compare/v1.2.5...v1.3.0
[1.2.5]: https://github.com/koho/frpmgr/compare/v1.2.4...v1.2.5
[1.2.4]: https://github.com/koho/frpmgr/compare/v1.2.3...v1.2.4
[1.2.3]: https://github.com/koho/frpmgr/releases/tag/v1.2.3