# WMViewRelease
WMView程序发布

#### change log
- 2017-09-25 发布1.0.0版本
- 2017-09-25 发布1.0.1版本
  - 修复 未连接到数据库时查询历史数据异常未捕获，造成程序崩溃
  - 改进 删除了"注册机"，"程序注册" 菜单
- 2017-09-27 发布1.0.2版本
  - 修复 从github更新时，混用asyn，sync（await, result)造成程序死锁 [参考](http://blog.stephencleary.com/2012/07/dont-block-on-async-code.html)
  - 修复  使用UpdateManager.GitHubUpdateManager 调用mgr.dispose(),而未调用result.dispose()，抛出异常
- 2017-10-10 发布1.0.3版本
  -  新增 添加程序到自动启动
  -  新增 复制实例项目到"D:\gwt\VMView"文件夹