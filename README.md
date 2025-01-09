# burp的汉化---个人翻译文本
burp的汉化个人翻译文本

## 免责声明
本工具仅面向合法授权的企业安全建设行为与个人学习行为，如您需要测试本工具的可用性，请自行搭建靶机环境。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如果发现上述禁止行为，我们将保留追究您法律责任的权利。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。

在安装并使用本工具前，请您务必审慎阅读、充分理解各条款内容。

除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。

## 更新日志

2021年9月16日

新增部分汉化 Repeater模块汉化 以及 proxy模块

[![4nEjT1.png](https://z3.ax1x.com/2021/09/16/4nEjT1.png)](https://imgtu.com/i/4nEjT1)

[![4nGVKI.png](https://z3.ax1x.com/2021/09/16/4nGVKI.png)](https://imgtu.com/i/4nGVKI)

## 使用说明
需要配合burp的汉化插件使用

汉化插件的git地址[BurpSuiteCn](https://github.com/hackxx/BurpSuiteCn "BurpSuiteCn")

插件自己下载哈

将cn.txt文件放在BurpSuiteCn汉化补丁的同级目录即可，汉化补丁会自动读取相关信息

图片预览--大多数都是双语汉化

精力和能力有限、可能有部分汉化错误

且只汉化部分，能满足大多数需求了

**如果burp2020.6或者以上的有字体显示错误或者光标错位的请在设置调整为宋体等中文字体、字号也根据自己的实际情况调节，我的是16，无BUG，选择什么的都正常**

**我自己的使用方法是增加-Dsun.java2d.uiScale=1参数**

**附上我使用的vbs**

CreateObject("WScript.Shell").Run "./jre\bin\java.exe  -Dsun.java2d.uiScale=1 -Dfile.encoding=utf-8 -javaagent:BurpSuiteCn.jar -noverify -javaagent:BurpSuiteLoader.jar   -jar burpsuite_pro.jar",0

![UdaLWt.png](https://s1.ax1x.com/2020/07/15/UdaLWt.png)
![UdaXSP.png](https://s1.ax1x.com/2020/07/15/UdaXSP.png)
![UdaqJI.png](https://s1.ax1x.com/2020/07/15/UdaqJI.png)
