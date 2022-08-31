# storm-sniffer-rules

本仓库收录的 storm-sniffer-rules 基本要求
不限制设备数量
未加密规则

今日热榜（haiku） 口令: SSC#7QtSc32inU# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
xmind（haiku） 口令: SSC#GPM5fW7HAS# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
symbolab 计算器（haiku） 口令: SSC#DQ463pnbie# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
奶油壁纸（haiku） 口令: SSC#8eY7Pn6xgt# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
已加密规则

彩云天气+解锁VIP 口令: SSC#6hzMgkwHVc# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
泼辣修图+解锁VIP 口令: SSC#6aLjeqoWjK# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
Lr Adobe Lightroom+解锁VIP 口令: SSC#JpA2rJeWiu# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
美图秀秀+解锁粉钻VIP 口令: SSC#bwfTSqfcfC# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
B612咔叽+解锁VIP 口令: SSC#DdEwDbmRUp# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)
提交未收录规则

https://github.com/coolhaiku/storm-sniffer-rules/issues/new

Notice

导出的规则无需任何更改，格式示例如下：
今日热榜（haiku） 口令: SSC#7QtSc32inU# 复制本段文本并打开Storm Sniffer(https://t.cn/A6Xjh5bu)

导出时需要将 App 的 AppStore 的商店链接放到重写描述栏中，方便导入的用户找到该 App，具体步骤如下：
AppStore 搜索需要分享的 APP -> 点击分享 -> 拷贝链接 -> 粘贴至 storm-sniffer 的重写规则描述栏中 -> 分享规则

进阶技巧

官方使用教程

此处引用 影子 的正则表达式简单教程

([\s\S]*?) 万能匹配表达式，匹配一切；包括空格，换行符；

\s 匹配一切空格，包括空格，换行，Tab缩进

\S 匹配一切非空字符

\d 匹配数字；如修改 0 为 1

. 通配符，但不匹配换行，所有出现换行的字符，都需要使用 [\s\S]*

\w 用于匹配字母，数字或下划线字符；如修改 false 为 true

\W 用于匹配所有与\w不匹配的字符；

+ 匹配1次或多次

* 匹配0次或多次

? 匹配0次或1次

所以 ([\w\W]*)同([\s\S]*)

正常情况下
.* 会匹配所有字符(换行除外)

.*? 表示非贪婪模式

如 123123123

.*3 会匹配:123123123，.*?3 会匹配:123

如果你想加强自己的动手能力，可以参考其他的仓库学习相关网络调试功能。另外，如 Thor , Http catcher , iHTTP Tracker , surge , Quantumult X ...... 的规则可以在参考将其改为 storm-sniffer-rules ，不同的软件操作上略有不同，但是原理大体是相同的。
推荐仓库
https://github.com/harry-sunhao/QuanX
https://github.com/search?p=4&q=http+catcher&ref=opensearch&type=Repositories
特别声明

本仓库发布的一切 storm-sniffer-rules 仅限用于学习和研究目的；不得将上述内容用于商业或者非法用途，否则，一切后果请用户自负。本仓库信息来自网络，版权争议与本仓库无关。您必须在下载后的24个小时之内，从您的设备中彻底删除上述内容。如果您喜欢该程序，请支持正版软件，购买注册，得到更好的正版服务。如有侵权请提交 Issues 与我们联系处理。
