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
- 2017-10-16 发布1.0.4版本
  -  改进 去除计算机器码时前后空格符
  -  改进 安装时复制实例项目到"D:\gwt\WMView"文件夹（原"VMView"为拼写错误)
  -  改进 按照"数据库字段规范文档_WXP_20170929" 规范历史数据查询字段显示
 - 2017-10-18 发布1.0.5版本
   -  修复 计算机器码时用ManagementClass类获取CPUID时，ghost系统CPUID不变，计算机器码时增加硬盘序列号
   -  新增 项目文件夹下增加"UI\View\HistoryData.xaml" 文件，可通过编辑此文件相应项，增减程序历史查询时所显示列
- 2017-10-18 发布1.0.6版本
   -  修复 计算机器码时用 ManagementObjectSearcher类获取硬盘序列号为空，计算机器码时增加mac地址（任文杰组重庆水站远程测试正常）
   -  修复 项目文件夹下"UI\View\HistoryData.xaml" 文件，打包错误，更正为正确的文件
- 2018-01-04 发布1.0.7版本
   -  新增 Cascade协议支持，用于与第三方软件通讯
   