QQ交流群340195342，点击加入：http://jq.qq.com/?_wv=1027&k=2ADNTk3
======

快速上手
======
1. 下载bftrader发布包
下载地址: https://github.com/sunwangme/bftrader/releases
下载地址: http://pan.baidu.com/s/1nvgrNst
运行ctpgateway，点击ctp/ctpConfig配置好ctp账号

2. 安装golang编译器和IDE
   2.1 安装 golang1.7.0 RC1 windows x86 (http://golangtc.com/download)
   2.2 安装 liteide x30.1 windows x86 (http://golangtc.com/download/liteide)
   2.3 安装 git for windows (https://git-scm.com/)
   2.4 更新 liteide的gotools和gocode，拷贝gotools.exe gocode.exe到liteide/bin
       go get -u github.com/visualfc/gotools
       go get -u github.com/nsf/gocode
       (https://github.com/visualfc/liteide/issues/633)

3. 下载bygo源代码
   3.1 go get github.com/sunwangme/bfgo

4. 写策略，调试策略  
   4.1 运行ctpgateway.exe,datafeed.exe
   4.2 点击ctpgateway的net/netStart,点击datafeed的net/netStart
   4.3 运行datarecorder/main.go，以连接ctpgateway datafeed
   4.4 点击ctpgateway的ctp/ctpStart
   4.5 可以看到datarecorder跑起来啦

网友策略列表
======
datarecorder/：tick收集器，演示BfTraderClient+BfRun的用法
sunwangme/：grpc例子
oneywang/: 1分钟方向策略 多周期多品种收集器

（完）
