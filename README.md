# 萌新写的UWP B站视频下载工具
这是一个可以下载B站视频的工具，支持使用BV,AV,SS,EP号搜索视频，自动转换为ass格式下载弹幕，以及MC号搜索漫画。暂不支持4K视频。有些太老的视频（没有dash的视频）暂不支持。

# 重构项目地址
https://github.com/EveElseIf/BilibiliDownloadToolUWP

# 使用说明
此工具支持断点续传，重启程序后也可以续传。为了尊重版权，需要使用大会员下载高清晰度视频（其实播放视频本质上就是在下载视频，所以能播放就能下载）。

下载视频的步骤为，打开程序，设置下载路径，点击搜索页，输入BV,AV,SS,EP,MC号或带有这些号码的网址（URL），点击搜索按钮，即可选择需要的视频进行下载。

如果不出意外，等进度条满了就下载好了，程序会自动调用ffmpeg进行合并处理，如果过程中出现闪退，那就是卡bug了，请提交issue。。。

为了简化漫画下载，不提供断点续传、下载记录等功能，请在程序单次使用时下载完毕。

# 安装说明
发布到了商店，https://www.microsoft.com/store/apps/9NRCX4MWLW8T

# 问题
程序在后台时（最小化之类），无法执行ffmpeg，无法更新界面

# 废话
作者是C#萌新，没有经验

然后高三了，有时间就久不久更新一下。。。

什么时候有第一颗星呢？⭐

# 引用
Newtonsoft.Json

QRCoder

Base64Url

XC.RSAUtil

https://github.com/EveElseIf/DanmakuToAss

参考了 https://github.com/SocialSisterYi/bilibili-API-collect 的文档

ffmpeg是从jjdown那里复制来的（只有3m，完整版可是60m以上。。）
