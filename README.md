## Welcome to GitHub Pages

一、苹果的小火箭单独去油管广告（也同样适用于Quantumult，Quantumult X，Loon等app
1、打开Shadowrocket--点击配置--点击.conf的配置文件，点击编辑纯文本。
2、复制下方代码，然后将拷贝的代码粘贴到
[URL Rewrite]
ctier=L ctier=A 302
^https:\/\/[\s\S]*\.googlevideo\.com/.*&(oad|ctier) _ REJECT
3、拷贝好之后点击右上角保存
4、再次点击.conf的配置文件--点击编辑配置--找到HTTPS解密
添加域名：*.googlevideo.com ，多个域名用英文的逗号隔开
生成证书-安装证书-手机设置描述文件允许-设置-通用-关于本机-证书信任设置-下面对应的证书开关打开-证书安装成功
5、和第4步重复的，只是另一种方法：或者是直接在文本的hostname后添加（默认的配置文件的文本里是没有的，只有添加过主机名之后会自动创建）

最重要还是需要用到HITM的功能，也就是http解密。
