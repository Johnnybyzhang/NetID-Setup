# DKU新生 NetID\_MFA\_邮箱登录 常见问题 Q\&A

作者：Zheng Zeng & Boyan Zhang

## NetID Onboarding

* NetID基本流程：
  1. 激活NetID，具体操作包括：
     1. 从最初预留的邮箱找到学校发的邮件
        [![pCTAWrD.jpg](https://s1.ax1x.com/2023/07/18/pCTAWrD.jpg)](https://imgse.com/i/pCTAWrD)
     3. 从邮件中第一个链接（accounts.oit.duke.edu开头的）进入，按照页面要求操作，注意链接只有一次有效，安全问题答案用英文
  2. 设置MFA，具体操作见下方
  3. 推荐设置[Duke Unlock](https://unlock.duke.edu/)，设置前提为已经完成了MFA的设置，优势是登录不需要用到Duo/手机号
     1. 设备硬件需求：
        * Windows设备使用Windows Hello人脸/指纹/PIN，浏览器Edge，Chrome和Firefox都可以，基于Chromium套壳的国内浏览器兼容性较差
        * macOS可以用Safari, Chrome和Firefox，Safari下设置一次可以在所有支持“通行密钥”的设备上使用
        * iOS/iPad OS可以使用Safari，有Face ID/Touch ID即可设置
        * Android/鸿蒙使用Chrome/Firefox/Edge，有指纹识别/人脸识别即可设置
     2. 打开页面后选Yes，随后出现绿字即为可以注册Duke Unlock，红字则为平台不支持，可以试着更换浏览器/检查设备设置
        [![pCTAfqe.jpg](https://s1.ax1x.com/2023/07/18/pCTAfqe.jpg)](https://imgse.com/i/pCTAfqe)
     4. 点击Register this Device，设置一个便于记忆的设备名
       [![pCTAc26.jpg](https://s1.ax1x.com/2023/07/18/pCTAc26.jpg)](https://imgse.com/i/pCTAc26)
     6. 点击Register device with Duke Unlock，对照屏幕上跳出的提示完成设置（macOS，Chrome为例，其余同理）&#x20;
        [![pCTA68x.jpg](https://s1.ax1x.com/2023/07/18/pCTA68x.jpg)](https://imgse.com/i/pCTA68x)
        [![pCTARKO.jpg](https://s1.ax1x.com/2023/07/18/pCTARKO.jpg)](https://imgse.com/i/pCTARKO)
     8. 设置完成，在任意Duke Login页面输入NetID后点击“Continue with Duke Unlock”即可使用（设置完成后点击“Try it now”也可）

## NetID

* NetID 的结构：First Name 首字母+Last Name 首字母 + 随机分配的数字
  * 因此没有大写字母I，只有小写字母l
* 手机号码输入格式：+8618812345678
* Security Question 要求用英文，不出现姓名等敏感信息，强烈建议另外保存答案文本
* Password 显示 valid 后再进下一步
* 双 Unsuccessful，Error reason: Authentication failed for xx\*\*\*
  * 一般为已经有过一次 Password Update: Successful，重进链接后 current password 写 successful 这次设置的密码
  * 如果确实没有设置成功过，发邮件给[service-desk@dku.edu.cn](https://service-desk@dku.edu.cn)，邮件内包含你的姓名，NetID和联系方式，并说明情况，Service Desk会为你重新生成一个一次性链接

## MFA相关常见问题

* Duo Mobile 安卓/鸿蒙系统安装链接：
* [https://dl.duosecurity.com/DuoMobile-latest.apk](https://dl.duosecurity.com/DuoMobile-latest.apk) MFA的软件可以在电脑上安装吗？不行。
* 显示6位验证码/Successful界面就是设置好了
* 二维码在哪里？MFA的设置过程中会出现，找不到等一等或者往下翻一翻网页。
* 二维码过期？重新进设置界面。
* 使用 NetID 登录时 MFA 认证区域显示下图：点 Forgot your device?，按指引重设设备&#x20;
[![MFA-Error](https://s1.ax1x.com/2023/07/18/pCTAgxK.jpg)](https://imgse.com/i/pCTAgxK)
## 邮箱

* 登录地址：mail.duke.edu，或者 Outlook/Apple 邮件等邮件客户端（网易邮箱大师不适用）
  * mail.duke.edu可能抽风打不开，多刷新试试
* 登录使用的邮箱地址：你的netid@duke.edu
* 邮箱地址自带别名：firstname.lastname(number)@dukekunshan.edu.cn
  * 不能用来登录
  * 邮件客户端可以选用哪个发邮件
* Outlook 登录时服务商选 Office 365
* Apple 邮件客户端登录时服务商选 Microsoft Exchange 不要选Outlook

## 杂项

* 推荐访问
  * it.dukekunshan.edu.cn
    * 了解学校提供的信息资源
  * software.duke.edu
    * 了解学校可以使用的正版软件，注意选择DKU Student
    * 部分软件在开学前无法使用，需要等Duke Software刷新License
