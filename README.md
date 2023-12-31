# DKU新生 NetID\_MFA\_邮箱登录 常见问题 FAQ

作者：Zheng Zeng & Boyan Zhang

# 打开该文档请从这里开始 [Onboarding](Onboarding.md)

## 如果存在声称自己是DKU IT的人员，请立刻通过邮件联系IT Service Desk。不向他人透露敏感信息。

## 以下为常见问题和对应解决方案

### NetID

* NetID 的结构：First Name 首字母+Last Name 首字母 + 随机分配的数字
  * 因此没有大写字母I，只有小写字母l
* 手机号码输入格式：+8618812345678，即11位中国内地手机号前加+86。港澳台地区手机号同理
* Security Question 要求用英文，不出现姓名等敏感信息，强烈建议另外保存答案文本以备不时之需
* Password 显示 valid 后再进下一步
* 双 Unsuccessful，Error reason: Authentication failed for xx\*\*\*
  * 一般为已经有过一次 Password Update: Successful，重进链接后 current password 写 successful 这次设置的密码
  * 如果确实没有设置成功过，发邮件给[service-desk@dku.edu.cn](mailto:service-desk@dku.edu.cn)，邮件内包含你的姓名，NetID和联系方式，并说明情况，Service Desk会为你重新生成一个一次性链接。强烈建议使用英文。
* 如多次尝试密码均错误，建议重置密码。DUID (Duke Unique ID) 请通过 [directory.duke.edu](https://directory.duke.edu/) 使用自己的名字查询。
  * 请核对 NetID，以确认检索到的为自己的信息。  

### MFA相关常见问题

* MFA的软件可以在电脑上安装吗？不行。
* 显示6位验证码/Successful界面就是设置好了
* 二维码在哪里？MFA的设置过程中会出现，找不到等一等或者往下翻一翻网页。
* 二维码过期？重新进设置界面。
* Duo Mobile上的账户名称需要改吗？随便，没影响。
*   使用 NetID 登录时 MFA 认证区域显示下图：点 Forgot your device?，按指引重设设备&#x20;

    <figure><img src="https://s1.ax1x.com/2023/07/18/pCTAgxK.jpg" alt=""><figcaption><p>MFA-Error</p></figcaption></figure>

### 邮箱

* 登录地址：[mail.duke.edu](https://mail.duke.edu) ，或者 Outlook/Apple 邮件等邮件客户端（网易邮箱大师不适用）
  * [mail.duke.edu](https://mail.duke.edu) 可能抽风打不开，多刷新试试
* 登录使用的邮箱地址：你的netid@duke.edu
  * 不用新建账户！
* 邮箱地址自带别名：firstname.lastname(number)@dukekunshan.edu.cn
  * 不能用来登录
  * 邮件客户端可以选用二者之一发邮件
* Outlook 登录时服务商选 Office 365
* Apple 邮件客户端登录时服务商选 Microsoft Exchange 不要选 Outlook.com
