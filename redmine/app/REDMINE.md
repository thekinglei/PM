redminePM是一款ios/android通用的redmine移动端软件

redminePM下载地址：  https://redminepm.cn.uptodown.com/android

使用前置条件
服务器端：administrator  -> settings - > authentication ,取消 "要求认证" 按钮打勾，并保存

app端：
服务器：http://redmine-server-ip:port/redmine （注意有的服务器服务地址结尾默认有rednine有的没有）

用户：用户

密码：用户密码

基本身份验证：再输入一次账号密码

如上操作，可以使用android移动端redmine。

问题：
1、redmine服务器必须设置： 取消认证要求，那么在用户非登录状态下，可以看到所有public项目，这个注意，尤其服务器放到公网上时。
2、issues 变更：对于修改issues字段，只有redmine系统默认的值，才可以设置（这个简直不可接受）
3、app登录后，在首页“项目”页，非公开的项目不展示（即使已经将用户授权给此项目）
4、我的任务 页面不展示assgine to me的issues不展示。
