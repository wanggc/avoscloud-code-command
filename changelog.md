## v0.5.3
* 修正新版本查询 Bug。

## v0.5.2
* 修复 webHosting user 在并发请求时信息串号的问题。
* webHosting req 参数增加 user 对象（req.AV.user）。
* 使用 nodemon 监视文件变更自动热加载

## v0.5.1
* 修复新建项目在 windows 系统上的权限问题，导致部署失败。
* 增加新版本检测功能
* 新增`-P`选项，指定本地测试端口。

## v0.5.0

* 添加 `app`,`add`,`rm`等命令，用于多应用管理。
* 消除对 curl 命令的依赖。
* 重构部分代码，更稳定和健壮。