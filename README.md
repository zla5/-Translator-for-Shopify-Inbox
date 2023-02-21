它可以在Shopify Inbox聊天窗口添加一些翻译按钮，当你在消息框中输入你的本国语言，点击语言按钮，它将翻译为目标语言。方便你与客户沟通，不需要在谷歌翻译页面来回复制粘贴翻译后的内容。<br>
<br>
使用方法：<br>
1. 请在浏览器上安装tampermonkey中使用这个js代码。<br>
2. 默认源语言为中文，如果你要修改源语言请在这段代码中的"zh-CN"修改为你需要的语言代码如："en"<br>
 translate("zh-CN", languageCode, messageContent.value.trim(), function(result) {<br>
3. 在代码中你可以自行添加或删除需要的语言。<br>
            addButton("en", "EN");<br>
            addButton("es", "ES");<br>
            addButton("ar", "AR");<br>
            addButton("fr", "FR");<br>
            addButton("ru", "RU");<br>
            <br>
            <br>
            欢迎大家一起来来更新功能<br>
