<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-ithome-rss

_✨ 一个用于订阅 IT 之家 RSS 的插件 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/Stewawa/nonebot-plugin-ithome-rss.svg" alt="license">
</a>
<img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="python">

</div>

# 安装
只提供手动安装。把 `nonebot_plugin_ithome_rss` 丢进 `src/plugins` 吧！

# 配置
> 以下配置项可在 `.env.*` 文件中设置，具体参考 [NoneBot 配置方式](https://nonebot.dev/docs/appendices/config)

#### `ithome_rss_interval`
- 类型：`int`
- 默认：`60`
- 说明：获取 IT 之家订阅的时间间隔。

#### `ithome_rss_groups`
- 类型：`List[str]`
- 默认：`[]`
- 说明：要推送订阅的群。

#### `ithome_rss_friends`
- 类型：`List[str]`
- 默认：`[]`
- 说明：要推送订阅的好友。