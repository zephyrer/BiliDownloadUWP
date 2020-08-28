# 萌新写的UWP B站视频下载工具
这是一个可以下载B站视频的工具，支持使用BV,AV,SS,EP号搜索视频。不支持4K视频。

# 使用说明
此工具支持断点续传，重启程序后也可以续传。为了尊重版权，需要使用大会员下载高清晰度视频（其实播放视频本质上就是在下载视频，所以能播放就能下载）。

下载视频的步骤为，打开程序，设置下载路径，点击搜索页，输入BV,AV,SS,EP号或带有这些号码的网址（URL），点击搜索按钮，即可选择需要的视频进行下载。

如果不出意外，等进度条满了就下载好了，程序会自动调用ffmpeg进行合并处理，如果过程中出现闪退，那就是卡bug了，请提交issue。。。

# 安装说明
UWP程序需要使用证书签名才能安装，此工具使用了自签证书，所以安装有两种方法。

## 使用xxx.appxbundle文件安装
直接打开会提示不受信任，所以请右键安装包，点击属性，数字签名，在签名列表选定证书，点击详细信息，点击查看证书，点击安装证书，下一步，将所有证书都放入下列储存，浏览，选择受信任的根证书颁发机构，然后一直下一步。
证书安装好了以后，就可以双击安装包进行安装了。

## 使用powershell脚本安装
下载整个压缩包，右键install.ps1，点击使用powershell运行，根据提示允许安装。

# 废话
作者是真C#萌新，没有经验，也只自学过《C# in Depth》,《More Effective C#》(看不是很懂)，《深入浅出WPF》，这几本书，所以写出来的代码可能非常难看。。。
然后高三了，肯定没时间继续搞。。。

# 引用
Newtonsoft.Json

QRCoder

参考了 https://github.com/SocialSisterYi/bilibili-API-collect 的文档

ffmpeg是从jjdown那里复制来的（只有3m，完整版可是60m以上。。）
