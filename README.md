![屏幕截图 2024-02-25 205903](https://github.com/CJJ-amateur-programmer/Detect_BIT_OJ_getchar/assets/161215070/ef34bc8a-7226-4392-9c84-7964a4d30628)针对北京理工大学乐学平台的C语言测试题，通过提交C语言程序，逐字符确定测试用例。

为符合编程人员的习惯，字符默认从第0个开始。

文本框中输入Enter键可以直接开始探测。

在结束文本框输入非数字时，会持续探测。

探测到所有的测试用例都EOF时探测会结束。

支持的测试用例字符：ASCII -1, 8-13, 32-126。

注意：

  1.这个程序会频繁向服务器发送固定模式的C语言代码，并通过每秒2次的请求确定是否编译完毕。因此，您不应该频繁或长时间使用此程序，否则可能给服务器造成巨大的压力。

  2.这个程序仅在最新版Micorsoft Edge中、采用篡改猴测试版和其篡改猴测试版试验过，不保证在IE、Firefox等浏览器或其他脚本管理器中正确运行。

  3.请在规定范围内使用程序。任何因使用不当而产生的后果责任自负，本人不承担任何相关责任。

  4.源代码开放，欢迎修改、提交issues，但禁止倒卖。

  5.全凭兴致不定期维护和更新。

使用方法：

  您应当事先安装好脚本管理器扩展，例如 TamperMonkey ，安装此脚本，并赋予适当的权限。

  以下教程以Microsoft Edge中的篡改猴测试版版为例说明。

  1.打开某一道尚未关闭提交入口的编程题，打开“查看”“提交”“结果”“提交历史”“报表”“相似度”的任意一项（此时网址形如：[https://lexue.bit.edu.cn/mod/programming/\*.php?id=\*]）。

  2.单击扩展，找到脚本管理器，点击，您应该找到“篡改猴测试版”。
  
  ![TamperMonkey](https://github.com/CJJ-amateur-programmer/Detect_BIT_OJ_getchar/assets/161215070/e14dae17-fb5e-40e5-b2d8-b55c83fd903a)
  
  单击“Detect_BIT_OJ_getchar”下方的“获取保密测试用例”。
  
  ![ContextMenu](https://github.com/CJJ-amateur-programmer/Detect_BIT_OJ_getchar/assets/161215070/0611dcea-9943-4aa0-8dd0-5efb52c2c5cd)
  
  3.出现弹窗。按照弹窗提示输入参数并提交即可。如果希望全部探测，请保持第一个输入框为0或非数字，在第二个输入框输入非数字。

  4.探测结束，结果会自动下载为txt文件，同时以弹窗的形式显示。

感谢 @YDX-2147483647 提供的最初版本python程序及其思路。

感谢 JWJ 提供的通过运行时长来确定字符的python程序及其思路。
