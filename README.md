# AI智能对话-Chat智能对话+AI绘图
源码下载:https://pan.ciyundata.com/f/mxSA/%E5%AE%8C%E6%95%B4%E5%8C%85.zip
#### Description
AI演示站（要后台演示的帐号密码可以加wx获取）:
wx:Y85136926
前台
https://ai.ciyundata.com

AI程序采用NUXT3+LARAVEL9开发（目前版本V1.1.7）

授权方式：三个顶级域名+两次更换

1.AI智能对话-对接官方和官方反代（markdown输出）PS:采用百度与自用库检测文字

2.AI绘图-根据关键词绘图-增加dreamStudio绘画-增加midjourney绘画

3.AI小应用-用户认证自主创建AI场景小应用-小应用分类

3.VIP功能-限制VIP每天免费对话和绘画次数

4.邀请码-用户可以通过分享邀请注册，达到注册次数奖励VIP

5.VIP卡密兑换-额度-会员

6.场景功能-实现场景指定场景内容

7.生成图片-截图当前对话记录生成图片下载

8.key池管理-轮询KEY监听Event请求

9.违禁词库-禁止发送某些词汇

10.风控中心-检测用户操作

11.优惠卷-购买折扣减价

12.签到-每日签到奖励-连续签到奖励

13.免登录问答-限制免登录问答次数

14.模型指定用户组或会员组选择

强烈建议开启百度审核文本，不得将程序用作任何违法违纪内容，不要让亲人两行泪

界面部分图解构：

前台show：
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/lasYnoVb6qe0ZSk0q9d8SUw4FC6UZAA44C9BH7YR.png)

![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/WTh0V1deXgo9qtgGj2WkIoMoH5WgUmAYNBKLcAmN.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/FByMeNWMW71iwBUeildwLfP2rOkaEVK3WnPcT3d0.png)
后台Show：
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/SpzHTDhj2ldm0GgFiw5h1EUHPIcu8dDoKDdtjpDL.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/eJyNxV55ahYcHTrUIggyn5478ItJ6TAw8fzJHM1m.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/9rx38iaflbswkalh1U1BMvYVlqIF4H6jWsiJrBRR.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/0ZBRCeddfJ3dpYMEXGKipHbqjTt7I3a2ijpuNBHU.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/LmB8HQGFCmyiiLh4KFyY4kk9xPicyjiIpt6iuoZq.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/8wBIHOqJD0hmhubQzBG6Iq29bN0oq4CXt4BYT9PW.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/FNejqpdaiuLlAX7YMJ0V4urstmQcrNgpU03ymJWp.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/9T73k9abnpEFa1AjJi1ry3Chwl2S0RQqHy1DT5Gz.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/4Dp77DXjRa7usONhDbQuLR8SsijBwuZKD1DwnLk8.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/4Cv4QnuqBctjgYA6XopwpTF3gUrYPVjqZ0QxNWZx.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/PL6nDXL3hzTKX8AvsAsyok18j4wUNCyYMo4Ygq9k.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/8UydIyKRhX2MVRImEcveROEm2OC1Vl2OVe4FKixM.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/PMVW9OFOOLEzZeC65zbJwevqGx33NngxpmRsmdyz.png)

 **AI问答绘图后端部署** 
运行环境（宝塔必看！）

Nginx

php8.1

redis

PM2管理工具

Mysql5.7以上

后台地址：后端域名/admin admin admin

后端部署：

先部署后端
创建网站-创建数据库


点击设置
运行目录选择
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/R5zlhB38JSuZ3tMaVkXp69Pyo518upTrbHG8fyDz.png)


配置伪静态
选择laravel5-保存
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/IPDrxGUog5tPALcKrQTsX8HQrwzgl7VjcpDchdmA.png)


进入目录
解压
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/lzlwtMm2H20twgxMsZCw8jAQCjUAxe9ugNElOzH4.png)


打开.env文件
修改数据库配置
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/5Pd95NyVsgyWsz1NPHLfT2odVMrkcQ9Qw7idGdaw.png)


打开后端网址
当看到以下提示便是搭建成功



安装PHP的扩展-redis以及fileinfo
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/ZSztQ3VRrCfTLQZ1Xpi9VOOWXR7zhYM3cRN4HY3x.png)
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/BKFhxNSPNh4bgDehHeEMLmudpPMrzA6w9HLgkW0y.png)

 **前端部署** 
前端部署：

安装pm2管理器


点击设置
选择v16.19.1版本-切换版本
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/4zo0jxtVsoJ8bIh6ShE0S0bbkdQJZZSUUZb8xSpy.png)


再新建一个网站
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/chQ0CLupfmmtdHfPtPhYd7L4HLDWOYmi2aaAEwGK.png)

点击设置
添加反向代理-代理名称随便填-目标url(http://127.0.0.1:3000)-提交
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/f4t1nPvhIDItuIHN6tga3m0k8VSWScVgfuk1OiLS.png)


进入网站目录
解压client.zip压缩包# AI智能对话-Chat智能对话+AI绘图
源码下载:https://pan.ciyundata.com/f/mxSA/%E5%AE%8C%E6%95%B4%E5%8C%85.zip
#### Description
AI演示站（要后台演示的帐号密码可以加wx获取）:
wx:Y85136926
前台
https://ai.ciyundata.com

AI程序采用NUXT3+LARAVEL9开发（目前版本V1.1.7）

授权方式：三个顶级域名+两次更换

1.AI智能对话-对接官方和官方反代（markdown输出）PS:采用百度与自用库检测文字

2.AI绘图-根据关键词绘图-增加dreamStudio绘画-增加midjourney绘画

3.AI小应用-用户认证自主创建AI场景小应用-小应用分类

3.VIP功能-限制VIP每天免费对话和绘画次数

4.邀请码-用户可以通过分享邀请注册，达到注册次数奖励VIP

5.VIP卡密兑换-额度-会员

6.场景功能-实现场景指定场景内容

7.生成图片-截图当前对话记录生成图片下载

8.key池管理-轮询KEY监听Event请求

9.违禁词库-禁止发送某些词汇

10.风控中心-检测用户操作

11.优惠卷-购买折扣减价

12.签到-每日签到奖励-连续签到奖励

13.免登录问答-限制免登录问答次数

14.模型指定用户组或会员组选择

强烈建议开启百度审核文本，不得将程序用作任何违法违纪内容，不要让亲人两行泪

界面部分图解构：

前台show：
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/lasYnoVb6qe0ZSk0q9d8SUw4FC6UZAA44C9BH7YR.png)

![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/WTh0V1deXgo9qtgGj2WkIoMoH5WgUmAYNBKLcAmN.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/29/FByMeNWMW71iwBUeildwLfP2rOkaEVK3WnPcT3d0.png)
后台Show：
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/SpzHTDhj2ldm0GgFiw5h1EUHPIcu8dDoKDdtjpDL.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/eJyNxV55ahYcHTrUIggyn5478ItJ6TAw8fzJHM1m.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/9rx38iaflbswkalh1U1BMvYVlqIF4H6jWsiJrBRR.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/0ZBRCeddfJ3dpYMEXGKipHbqjTt7I3a2ijpuNBHU.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/LmB8HQGFCmyiiLh4KFyY4kk9xPicyjiIpt6iuoZq.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/8wBIHOqJD0hmhubQzBG6Iq29bN0oq4CXt4BYT9PW.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/FNejqpdaiuLlAX7YMJ0V4urstmQcrNgpU03ymJWp.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/9T73k9abnpEFa1AjJi1ry3Chwl2S0RQqHy1DT5Gz.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/4Dp77DXjRa7usONhDbQuLR8SsijBwuZKD1DwnLk8.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/4Cv4QnuqBctjgYA6XopwpTF3gUrYPVjqZ0QxNWZx.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/PL6nDXL3hzTKX8AvsAsyok18j4wUNCyYMo4Ygq9k.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/8UydIyKRhX2MVRImEcveROEm2OC1Vl2OVe4FKixM.png)
![输入图片说明](https://nsmao.oss-cn-shanghai.aliyuncs.com/202304/25/PMVW9OFOOLEzZeC65zbJwevqGx33NngxpmRsmdyz.png)

 **AI问答绘图后端部署** 
运行环境（宝塔必看！）

Nginx

php8.1

redis

PM2管理工具

Mysql5.7以上

后台地址：后端域名/admin admin admin

后端部署：

先部署后端
创建网站-创建数据库


点击设置
运行目录选择
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/R5zlhB38JSuZ3tMaVkXp69Pyo518upTrbHG8fyDz.png)


配置伪静态
选择laravel5-保存
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/IPDrxGUog5tPALcKrQTsX8HQrwzgl7VjcpDchdmA.png)


进入目录
解压
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/lzlwtMm2H20twgxMsZCw8jAQCjUAxe9ugNElOzH4.png)


打开.env文件
修改数据库配置
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/5Pd95NyVsgyWsz1NPHLfT2odVMrkcQ9Qw7idGdaw.png)


打开后端网址
当看到以下提示便是搭建成功



安装PHP的扩展-redis以及fileinfo
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/ZSztQ3VRrCfTLQZ1Xpi9VOOWXR7zhYM3cRN4HY3x.png)
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/BKFhxNSPNh4bgDehHeEMLmudpPMrzA6w9HLgkW0y.png)

 **前端部署** 
前端部署：

安装pm2管理器


点击设置
选择v16.19.1版本-切换版本
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/4zo0jxtVsoJ8bIh6ShE0S0bbkdQJZZSUUZb8xSpy.png)


再新建一个网站
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/chQ0CLupfmmtdHfPtPhYd7L4HLDWOYmi2aaAEwGK.png)

点击设置
添加反向代理-代理名称随便填-目标url(http://127.0.0.1:3000)-提交
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/f4t1nPvhIDItuIHN6tga3m0k8VSWScVgfuk1OiLS.png)


进入网站目录
解压client.zip压缩包
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/lqwmRXW7zpPOojDYD7jfQjofknVPuiOiSMarspnn.png)


进入env文件打开.env文件
修改VITE_SERVER_NAME为自己的后端域名
![输入图片说明](https://epmao.oss-cn-beijing.aliyuncs.com/202304/05/rBjNpdJnYoSbrhzhidoQr69CPCLKrX3g521CXXQP.png)


接着返回到上级目录
打开终端

执行npm install -g pnpm

运行pnpm install

运行pnpm run build后

运行pm2 start ecosystem.config.js

如果运行pm2 start ecosystem.config.js报错 先运行pm2 update

搭建结束 ps：数据库自己别忘记上传

 **Ai问答绘画常见问题** 
常见问题

1.前端开启ssl为什么请求不了后端了

答：前后端要同时开启https否则会有跨域问题

 

2.我前端改了样式为什么没生效

答：前端不管修改什么都要执行以下步骤。

执行pnpm install后pnpm run build后执行pm2 delete NuxtAppName后执行pm2 start ecosystem.config.js

 

3.后台登录界面没出现验证码？

答：检查.env文件的数据库配置信息是否正确，表是否完全导入，建议进入phpmyadmin导入 否则不知道报错什么

 

4.前端报错弹窗为空白？

答：数据库错误 缺少表

 

5.阿里手机验证码发出报错？

答：需要进入默认php的禁用函数，删除shell_exec

 

6.支付宝支付没报错：生成失败？

答：商家协议有问题 ，查看是否上线应用，是否开通了当面付

 

7.支付没回调？

答：查看后台系统设置-》api地址填写是否后端地址，并且尾部不加/

 

8.小应用图片上传不了？后端图片上传不了？图片显示不了？

答：图片设置，如果是本地上传，查看后台系统设置-》api地址填写是否后端地址，并且尾部不加/

如果是阿里oss查看key那些是否正确，并且阿里oss开启了公共读

 

9.前端页面502？

答：需要重新执行pnpm install后pnpm run build后执行pm2 delete NuxtAppName后执行pm2 start ecosystem.config.js

 

10.后端改了密钥或者其他设置突然进不去？

答：检查你的.env文件是否有空格符号

 

11.后台地址api地址填啥？

答：后端地址http://xxx.com（最后面不加斜杆）
7.支付没回调？

答：查看后台系统设置-》api地址填写是否后端地址，并且尾部不加/

 

8.小应用图片上传不了？后端图片上传不了？图片显示不了？

答：图片设置，如果是本地上传，查看后台系统设置-》api地址填写是否后端地址，并且尾部不加/

如果是阿里oss查看key那些是否正确，并且阿里oss开启了公共读

 

9.前端页面502？

答：需要重新执行pnpm install后pnpm run build后执行pm2 delete NuxtAppName后执行pm2 start ecosystem.config.js

 

10.后端改了密钥或者其他设置突然进不去？

答：检查你的.env文件是否有空格符号

 

11.后台地址api地址填啥？

答：后端地址http://xxx.com（最后面不加斜杆）
