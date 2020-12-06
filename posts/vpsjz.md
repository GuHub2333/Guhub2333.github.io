#购买VPS
----------
推荐几个商家,大家任选一个就行
1.Akko
[2.雨云][1]
[3.liluohost][2] 黑五优惠码:`black50off`
4.艾云
这里我以雨云为例子,下翻还有它家的
点击购买云服务器,注意要购买海外的服务器哦,如果你备案了,当我没说
![购买界面][3]
记录信息
----------
来到服务器管理界面,等待创建完毕,等待ing...
![等待创建完毕][4]
创建完毕后进入控制面板
![创建完成][5]
进入控制面板后往下滑,IPv4地址(公网),远程用户名,远程密码都复制上,粘贴到txt记事本里
![控制面板][6]
安装面板
----------
用SSH工具连接你的服务器,这里推荐[FinalShell][7]
打开SSH工具后,点击小文件夹按钮,让后点击左边的白色文件夹,让后点击添加linux服务器
![添加服务器信息界面][8]
把刚刚的服务器信息粘贴进来,让后点击确定
![添加服务器填写信息界面][9]
连接后输入代码并回车,在输入Y（小写
代码是:`curl -sSO http://download.bt.cn/install/install_panel.sh && bash install_panel.sh`
![宝塔安装][10]
等待一会,服务器好的4分以内,慢的30分钟也有可能、
![请输入图片描述][11]
配置环境
----------
提示安装完成后打开提示的链接,输入账号和密码登录
![请输入图片描述][12]
![请输入图片描述][13]
这里建议使用我这样的配置进行安装
![请输入图片描述][14]
# 创建网站
----------
安装完成环境后点击左边的网站建,让后点击新建网站
域名输入你自己的,或者也可以使用服务器的ip进行建站
数据库可以创建,也可以不创建,因为typecho支持SQLite3所以我们可以使用文件进行使用更加轻量级的数据库
毕竟SQLite3不占用内存,不像MySql那样高占用内存
![请输入图片描述][15]

# 上传网站程序
----------
网站程序有很多种,这里我们就以更加轻量级的Typecho博客为例子
下载博客系统到电脑  [官网下载地址][16]
下载完再上传到服务器上


  [1]: http://redirect.rainyun.cn/?ref=13915
  [2]: https://my.liluohost.com/aff.php?aff=340
  [3]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/002.png
  [4]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/001.png
  [5]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/003.png
  [6]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/004.png
  [7]: http://www.hostbuf.com/t/988.html
  [8]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/005.png
  [9]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/006.png
  [10]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/007.png
  [11]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/11/29/vpsjz/008.png
  [12]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/12/1/vpsjz/001.png
  [13]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/12/1/vpsjz/002.png
  [14]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/12/1/vpsjz/003.png
  [15]: https://img-1302845516.cos.ap-nanjing.myqcloud.com/blog/2020/12/1/vpsjz/004.png
  [16]: http://typecho.org/build.tar.gz
