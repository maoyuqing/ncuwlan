### 缘起
在学校里很多人都是用的校园网，有的是自己学校的,比如我们学校有ncuwlan，有的是cmcc或者联通的校园网，这些校园网大多需要在连接wifi后登陆特定的网页才能登陆，而且还经常容易下线，所以就写了这个脚本。   
### 需知
1. 这个脚本需要requests，你可以`pip install requests`来安装这个库。其他的都是一些python自带库，不需要额外安装。
2. 经过测试这个脚本在南昌大学校园网ncuwlan可以一用，相信其他的校园网形式大多相似，可以方便改编。
### 使用
下载ncuwlan.py   ,编辑器打开它，在脚本的一开始，需要更改用户名和密码 ,以及可以自己设定每隔几秒进行一次连接，防止下线。python2，python3，linux和Windows都可以用  
当这个脚本运行时，会按照设定的时间间隔检测网络连通，如果掉线就会自动重连


