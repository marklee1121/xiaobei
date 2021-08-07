## 本项目主要用于学习研究，请勿用于非法用途，若出事一切后果请自行承担！本人概不负责，谢谢！

----

### 介绍
 > 这是一个小北学生自动打卡脚本，用了此脚本导员再也不用在群里一直@你了，不用为了每天忘记打卡而想各种理由了，这玩意之前就想就想搞一个了，只不过没时间好好看一下，之前使用小米手机抓包一直有问题，最近用iPhone抓 却抓到了
 这个脚本是在我上班摸鱼期间写的，带薪摸鱼🐟  真的很舒服~~
 
### 使用

-----

 **有两种方法使用，一种是使用`Github actions` ，还有一直是直接在本地运行（不推荐）**
 
#### 本地运行

----

安装python3环境，然后执行`pip install requests`或者`python -m pip install requests`,之后下载本仓库代码，如果安装了Git则直接使用命令`git clone https://github.com/lovebai/xiaobei.git`
如果未安装则直接在右上角下载zip，如图
![下载zip](images/160919.png)
还有种情况是未安装python环境和git环境的直接在`release`中下载exe，下载链接：[Release Download](https://github.com/lovebai/xiaobei/releases/tag/1.0)

#### 在Github Actions运行方式（推荐使用这种）

-----

 * 首先点击右上角的Fork
     ![Fork](images/162619.png)
 * fork成功后点击`settings`
     ![setting](images/163023.png)
 * 为了安全，选择和下图一样的,右侧栏`actions`
     ![setting](images/163327.png)
 * 还是右侧栏，选择`secrets`
     ![secrets](images/163720.png)
 * 根据下图 添加配置
     ![secrets](images/164043.png)
 * 为了方便复制也提供一份文本的
    ```XB_USERNAME  # 小北用户名（必填）
    XB_PASSWORD  # 小北密码（必填）
    XB_LOCATION  # 经纬度（必填）
    XB_COORD     # 当前位置（必填）
    XB_IS_EMAIL  # 是否开启邮件通知（必填）如果开启了下面的也必填 不然收不到信息
    XB_EMAIL     # 通知接收邮箱账号（选填）
    XB_E_HOST    # SMTP服务器地址（选填）
    XB_E_ACCOUNT # 通知发送邮箱账号（选填）
    XB_E_PASS    # 通知发送邮箱账号的密码（选填）
   ```

 * 下面是添加账号的示例，其他的也按此方法填写即可
      ![secrets](images/165515.png)
 * 完成之后点`code`回到代码页然后点add file在点击create new file
       ![secrets](images/170240.png)
       ![add file](images/170636.png)
 * 点击后标题和内容随便输入，输好之后直接点击Commit new file
     ![secrets](images/170957.png)
 * 之后在前actions查看任务即可
   ![secrets](images/170509.png)
   ![具体信息可以的点击查看](images/171549.png)

### 说明

-----

 - 以上说明只是起初版本的
 - 有时间会优化的
 - 需要配置的东西有点多，后期会将邮件给优化了 换一种方式通知或者调用接口的方式
 - 持续优化

### 其他

-----

> 如果你自己有服务器的话建议使用dev版本，在本地使用也是可以的，各有各的好处吧，
[点我去看服务器版本](https://github.com/lovebai/xiaobei/tree/dev)
     

### 免责声明

-----

本项目只做为技术研究，本人不对其程序所带来的后果担则。



   


   
   
