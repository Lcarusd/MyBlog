# Tale 博客系统

> Tale 的英文含义为**故事**，我相信每个坚持写 Blog 的人都是有故事的；中文你叫它 ***塌了*** 也无所谓 🤣。
`Tale` 使用了轻量级 mvc 框架Blade开发，默认主题使用了漂亮的 [pinghsu](https://github.com/chakhsu/pinghsu)。

## 特性

+ 设计简洁，界面美观
+ Markdown 文章发布
+ 自定义文章链接
+ 支持多主题
+ 支持插件扩展
+ 支持 Emoji 表情
+ 支持网易云音乐播放
+ 支持附件和数据库备份
+ 部署简单，不依赖 Tomcat
+ 无需数据库，内嵌 Sqlite

## ./tale-cli工具使用

```sh
» ./tale-cli

Tale 博客程序帮助工具

Github: https://github.com/otale/tale

Usage:
	tale-cli command [arguments]

Available commands:
backup   备份 Tale 博客
log      查看 Tale 博客日志
restart  重启 Tale 博客
start    启动 Tale 博客
status   查看 Tale 博客运行状态
stop     停止 Tale 博客
upgrade  升级 Tale 博客
``` 
