青龙面板 薅羊毛 微信阅读 多用户高收益<br>
~单微信号每日收益2块左右 3000金币=0.3元即可提现到微信钱包<br>
~6秒一篇文章得120金币 每小时30篇 每天6轮 180篇文章共21600金币=2.16元<br>
--
用微信扫一扫 
<img src="https://github.com/jiasai007/wxyd/blob/e9dfdf7afdc486f0bb7b9021926e010c588056fb/1.png" alt="Clash" width="200">
<img src="https://github.com/jiasai007/wxyd/blob/e9dfdf7afdc486f0bb7b9021926e010c588056fb/2.png" alt="Clash" width="200">
<img src="https://github.com/jiasai007/wxyd/blob/e9dfdf7afdc486f0bb7b9021926e010c588056fb/3.png" alt="Clash" width="200">
任意一个均可
<br>
--
打开后自动转跳阅读文章 空白页关闭后 重新打开 <br>
转跳到文章页面停6秒 返回上一页 重复操作30次即可 <br>
可以在安卓或苹果手机中的微信里操作 也可以用PC版微信的自带浏览器等等<br>
单个微信号 可以自己写个简单的模拟按键延迟点击脚本 并且不会有验证文章卡住的问题 
--
青龙面板可以在windows系统 安卓手机 软路由 linux docker 等安装均可 <br>
安装教程自行搜索 这次从可以打开青龙面板 5700端口开始<br>
青龙面板-定时任务-新建任务<br>
名称:拉库 命令/脚本:复制下面内容
```Shell
ql repo https://ghproxy.com/https://github.com/jiasai007/wxyd.git
```
定时规则 
```Shell
0 0 0 * * 1
```
点击 确定 后在操作栏中 点击 运行 该脚本
运行成功后 设置 微信阅读 脚本 定时规则为 0 */30 * * * ? <br>

青龙需要抓包m.*.shop域名下cookie <br>
青龙面板-环境变量-新建变量<br>
名称:wxyd 值:(你抓取的cookie) 点确定 多账户用回车换行隔开<br>

安卓可以用 小黄鸟 HttpCanary  https://www.bilibili.com/video/av292860564/<br> 
PC可以用 smartsniff Wireshark 等 抓取cookie

~返回定时任务 运行 微信阅读 查看日记 运行是否正常~
