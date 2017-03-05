# PDF辅助翻译
可编辑的PDF文档复制到 Google 翻译时，会由于行尾的换行符导致翻译不准，本程序去掉了上下两行断句中间的换行符并将其连接为一个句子。然后调用Google翻译，生成翻译后的文档。
###用到的库：
clipboard 获得剪贴板内容：https://pypi.python.org/pypi/clipboard/<br/>textblob Python的Google翻译第三方库：https://pypi.python.org/pypi/textblob
### 使用说明：
* 程序开始运行后，选中文字按Ctrl+C复制，程序会自动捕捉剪贴板内容。
* 选中段落时请务必选中段落末尾的标点符号。
* 复制结束后，在控制台按回车开始翻译。
<br>

### 注意：
本程序需要VPN或全局代理！！！
