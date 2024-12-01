# AliPayQrcode
*这是一个供中国用户使用的项目。如果你不知道这是什么，请关闭此页面。

# 预览展示效果
  [点击预览](https://studentconstellation.github.io/alipayqrcode.html)

# 如何使用本项目？

### 1.下载本项目
  点击本页面的绿色“<>Code”按钮，选择“Download Zip”下载项目随后解压。

### 2.在网页端登录支付宝
  进入[支付宝网页版](https://www.alipay.com/x/personal)，扫码登陆账号

### 3.使用 DevTools 查找支付宝 ID
  登录后，按下键盘上的 F12 按键，打开 DevTools 。
  选择到“元素”这一栏，按下Ctrl+F调用搜索
  ![搜索ID](/img/0.png)
  
  在搜索框内输入“2088”，将会出现一串 2088 开头的 16 位数字，这就是支付宝 ID。
  此时，替换 index.html 的第 87 行的“你的支付宝ID”即可。

### 4.测试
  打开index.html文件，查看页面能否加载。
  你可以输入金额，备注查看是否正常工作。
  
### 5.正式使用
  删除多余的 /img 文件夹、readme.md 文件，便可以直接使用了
  你也可以对项目做一些修改，前提是需要 Fork 本项目。
