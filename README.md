# CpdailyAutoSign-for-NAU
南京审计大学今日校园自动签到。
此项目完完全全依靠子墨大佬的项目，在此只是为了方便记录，减少新来的同学一些配置的时间。详情请参阅https://github.com/ZimoLoveShuang/auto-submit ，为原作者点一下star，如有意捐赠请直接捐赠子墨大佬，在此不甚感谢。

禁止任何人使用此项目提供付费的代挂服务

项目说明

config_nau.yml 南京审计大学的配置文件，在此需要填入自己的学号，密码，接收通知的邮箱等信息。
index.py 完成自动提交的py脚本，一般来说不用更改。


clone 或者 下载 此仓库到本地
git clone https://github.com/ZimoLoveShuang/auto-submit.git
打开本地仓库文件夹，配置config.yml中对应的学号（username）和密码（password）还有地址（address）等等信息，详情请看config.yml中的注释说明，注意这里的学号和密码都是今日校园的学号和密码

打开百度搜索腾讯云函数，注册认证后，进入控制台，点击左边的层，然后点新建，名称随意，然后点击上传zip，选择release中的dependency.zip上传，然后选择运行环境python3.6，然后点击确定，耐心等待一下，上传依赖包需要花费的时间比较长。

