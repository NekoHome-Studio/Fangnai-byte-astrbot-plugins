# Fangnai-byte 的 AstrBot 插件仓库合集

Fangnai-byte 名下 AstrBot / DeepSeek Harness 相关插件与开发资料的索引。每个插件都独立成库，本仓只做目录，不存放源码。

## 功能插件

| 插件 | 说明 | 语言 |
| --- | --- | --- |
| [astrbot_plugin_group_log_archive](https://github.com/Fangnai-byte/astrbot_plugin_group_log_archive) | 群聊日志归档：分群按天导出聊天记录，支持图片保存、AI 命名、脱敏 | Python |
| [astrbot_plugin_stardust_diary](https://github.com/Fangnai-byte/astrbot_plugin_stardust_diary) | 智能记忆：重要记忆长期保存，日常消息保留一天，按群隔离，按需注入上下文 | Python |
| [astrbot_plugin_smart_reply](https://github.com/Fangnai-byte/astrbot_plugin_smart_reply) | 智能自动回复：指定群生效、群/用户黑白名单、频次粗筛 + 灰区语境判断、被无视自动降频 | Python |
| [astrbot_plugin_full_prompt](https://github.com/Fangnai-byte/astrbot_plugin_full_prompt) | 修复唤醒词 / At 被剥离导致提交给 LLM 的提示词残缺的问题 | HTML |
| [astrbot_plugin_speak_rank](https://github.com/Fangnai-byte/astrbot_plugin_speak_rank) | 群内发关键词即可查看本群发言排行：今日 / 本周（周一起）/ 累计 | Python |
| [astrbot_plugin_peak_whitelist0d00](https://github.com/Fangnai-byte/astrbot_plugin_peak_whitelist0d00) | 峰值时段白名单（0d00 版） | Python |
| [astrbot_plugin_qzone_publish](https://github.com/Fangnai-byte/astrbot_plugin_qzone_publish) | 用 `/说说 内容` 直接在 QQ 空间发一条说说 | Python |
| [astrbot_plugin_ds_status](https://github.com/Fangnai-byte/astrbot_plugin_ds_status) | 订阅状态页 RSS，有新动态推送到 QQ | Python |
| [astrbot_plugin_self_msg_guard](https://github.com/Fangnai-byte/astrbot_plugin_self_msg_guard) | 自消息守卫：拦截机器人自身消息，防止自转循环 | Python |
| [astrbot_plugin_plugin_cache](https://github.com/Fangnai-byte/astrbot_plugin_plugin_cache) | 插件二级缓存：按需唤醒休眠插件，用完即关 | Python |
| [astrbot_plugin_comfyui_local](https://github.com/Fangnai-byte/astrbot_plugin_comfyui_local) | 把本地 ComfyUI 接进 AstrBot：聊天里一句话出图，支持指定 / 展示工作流，含内容兜底与出图日志 | Python |
| [dsh-deepspace-theme](https://github.com/Fangnai-byte/dsh-deepspace-theme) | DeepSeek Harness Web GUI 的 deepspace 玻璃拟态主题 | JavaScript |

## 开发资料

| 资料 | 说明 |
| --- | --- |
| [astrbot-plugin-dev](https://github.com/Fangnai-byte/astrbot-plugin-dev) | AstrBot 4.28.0 插件开发参考：命令与事件过滤、事件钩子、LLM 工具、`_conf_schema.json`、metadata 打包、Star KV 存储、会话等待、Web API 与图片渲染 |
| [dsh-plugin-dev](https://github.com/Fangnai-byte/dsh-plugin-dev) | DeepSeek Harness 插件开发参考：宿主半边与客户端半边、`cordis.patch.yml` 行插入、profile bundle 接线、安装后验证 |

## 备注

以上插件均以 MIT 许可发布，各自仓库内保留完整提交历史与 Issues。

合集仓库本身位于 NekoHome-Studio 组织下，仅提供索引，便于统一查阅与发现；源码仓库归属 Fangnai-byte。
