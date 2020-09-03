# telegram_translate
## time 9:44 am
## Thursday, 3 September 2020 (GMT+8)
## author:xcc
## url:https://core.telegram.org/bots


# 机器人：一个给开发者的入门指南

bot是运行在Telegram内部的第三方应用程序。用户可以通过发送消息、命令和内联请求与机器人进行交互。你可以通过HTTPS请求我们的机器人API来控制你的机器人。


# 1. 我能用机器人做什么
举几个例子，你可以使用bots做以下事情:

A.获得自定义的的通知和新闻。机器人可以像{智能报纸}(也就是可以点击播放的报纸，以达到交互的目的)样，在相关内容一出版就会发送给你

B.集成了其他服务。机器人可以用来自外部服务的内容丰富电报聊天。Gmail机器人，GIF机器人，IMDB机器人，Wiki机器人，音乐机器人，Youtube机器人，GitHub机器人

C.支持Telegram付款。机器人可以提供付费服务或充当虚拟店面。阅读更多

D.创建自定义工具。机器人可以为您提供警报、天气预报、翻译、格式化或其他服务。MarkDown机器人，贴纸机器人，投票机器人，点赞机器人。

E.开发单人和多人游戏。机器人可以提供丰富的HTML5体验，从简单的街机游戏和谜题到3d射击游戏和实时战略游戏。GameBot, Gamee

F.构建社交服务。机器人可以根据共同的兴趣或距离将寻找对话伙伴的人们联系起来。

E.几乎可以做其他任何事情。 除了洗碗，因为机器人洗碗可能碗都没了，哈哈哈

# 1. 机器人是如何运转的
总的来说，telegram机器人是特殊的帐户，因为不需电话号码就可以注册，用户可以通过两种方式与机器人交互：
1.通过与机器人聊天或将他们加入群组，向他们发送信息和命令。
2.通过输入bot的@username和一个查询直接从输入字段发送请求。这允许从内联机器人直接发送内容到任何聊天、组或频道。

用户发送的消息、命令和请求被传递到运行在您的服务器上的软件。我们的中间服务器为您处理所有加密和与电报API的通信。您可以通过一个简单的http接口与此服务器通信，该接口提供了一个简化版的Telegram API。我们把这个接口称为我们的机器人API。

此页面提供了Bot API的详细描述
