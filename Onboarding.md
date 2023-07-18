## NetID Onboarding

* NetID基本流程：
  1. 激活NetID，具体操作包括：
     1.  从最初预留的邮箱找到学校发的邮件&#x20;

         <figure><img src="https://s1.ax1x.com/2023/07/18/pCTAWrD.jpg" alt=""><figcaption><p>Email</p></figcaption></figure>
     2. 从邮件中第一个链接（accounts.oit.duke.edu开头的）进入，按照页面要求操作，注意链接只有一次有效，安全问题答案用英文

  2. 设置MFA

     1. 关闭所有浏览器页面，打开邮件内的第二个链接（https://idms-mfa.oit.duke.edu）

     2. 准备好以下内容：

        * 你自己的手机号码，例：`18912345678`，则记录为`+8618912345678` 
        * 手机应用 `Duo Mobile` [安卓/鸿蒙系统下载地址](https://people.dukekunshan.edu.cn/~bz106/DuoMobile-4.44.0.apk) [iOS下载地址](https://apps.apple.com/us/app/duo-mobile/id422663827?l=zh-Hans-CN) 
        * 在第一次页面设置中设置的密码

     3. 打开页面后，你应当处于Duke Login页面<img src="https://f.pz.al/pzal/2023/07/18/413fa8b34b16d.jpg" alt="Secret_2023-07-18 23.09.05" style="zoom:25%;" /> 

        选择`Log in with NetID`

        <img src="https://f.pz.al/pzal/2023/07/18/1cae853618a88.jpg" alt="Secret_2023-07-18 23.10.35" style="zoom:50%;" /> 

        手动输入`NetID` `Password`

        确认无误后点击`Log In` 登录

        <img src="https://f.pz.al/pzal/2023/07/18/c7a6073c5c182.jpg" alt="Secret_2023-07-18 23.17.25" style="zoom: 33%;" />

        点击`Register Device with Duo` 

        <img src="https://f.pz.al/pzal/2023/07/18/9c22c261794da.jpg" alt="Secret_2023-07-18 23.19.18" style="zoom:33%;" />

        此处为避免反复操作，请一律选择`Mobile phone` 

        <img src="https://f.pz.al/pzal/2023/07/18/7e0bcbafa6433.jpg" alt="Secret_2023-07-18 23.20.22" style="zoom:33%;" />

        苹果设备选iPhone，反之一律选择Android

        `10-digit phone number`下方的框内填入准备的手机号码（实例为+8618912345678

        最后一栏的设备备注名用于标识设备，选填

        点击`Continue` 

        <img src="https://f.pz.al/pzal/2023/07/18/789072dac106c.jpg" alt="Secret_2023-07-18 23.32.42" style="zoom:25%;" />

        滑动到页面最底部（Step 4）

        <img src="https://f.pz.al/pzal/2023/07/18/eb106717ca505.jpg" alt="Secret_2023-07-18 23.34.48" style="zoom:25%;" />

        扫描二维码（图示二维码为实例，无法用于扫描且二维码与用户绑定，无法与他人共享）

        完成后点击`Continue`

        <img src="https://f.pz.al/pzal/2023/07/18/5c2ea9c3b0595.jpg" alt="Secret_2023-07-18 23.36.55" style="zoom:20%;" />

        出现`Registration Successful`说明MFA设置部分完成

     4. 设置完成MFA后的登录（绝大部分Duke网站使用完整服务都需要MFA）

        <img src="https://f.pz.al/pzal/2023/07/18/4f9d3aae99e0b.jpg" alt="Secret_2023-07-18 23.14.53" style="zoom: 25%;" />

        按照要求输入NetID和Password后稍等，底部会出现`Multi-factor Authentication` （图示中对个人信息进行了隐藏处理）

        一般情况下有四种可选项（推荐使用前两种）

        * Duo Push
          * 选择该选项后，手机可能会收到一条来自`Duo Mobile` 的通知（iOS一般会收到通知），打开应用后选择`Approve`
        * Call phone
          * 选择该选项后，手机会收到来自`(021) 8036 5482`的电话，接起后使用拨号盘输入任何内容即可，电话会在几秒后自动挂断
        * Send SMS codes （不推荐使用）
        * 最底部的输入框（不推荐使用）
          完成后可以选择`Remember device for 72 hours` 减少需要反复进行MFA认证的次数
          * 注意：72小时限制指的是上述MFA选项的有效时长，与MFA途径本身的有效期无关，72小时后无需重新设置

* 至此，所有NetID设置部分全部完成，如果希望设置无密码登录请查看[Duke Unlock](Unlock.md)