# wechatbot
个人微信接入chatgpt3.5版本，模型：gpt-3.5-turbo

项目基于[openwechat](https://github.com/eatmoreapple/openwechat)/[wechatbot](https://github.com/djun/wechatbot)
开发
###目前实现了以下功能
 + 群聊@回复
 + 私聊回复
 + 自动通过回复
 
# 注册openai
chatGPT注册可以参考[这里](https://juejin.cn/post/7173447848292253704)

# 安装使用
````
# 获取项目
git clone git@github.com:superheze/wechatbot.git

# 进入项目目录
cd wechatbot

# 复制配置文件
cp config.dev.json config.json

# 启动项目
go run main.go

启动前需替换config中的api_key
