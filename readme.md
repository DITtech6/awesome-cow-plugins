这个仓库主要是收集[CoW(chatgpt-on-wechat)](https://github.com/zhayujie/chatgpt-on-wechat)的[插件](https://github.com/zhayujie/chatgpt-on-wechat/tree/master/plugins)，欢迎补充加入看到、用过或新开发的插件。

喜欢的朋友记得帮忙点亮免费的 Star 支持下，让更多的人看到。

## 内置插件

- banwords: 敏感词
- bdunit: 基于百度 UNIT 的智能对话，如天气、日期时间、数学运算等
- dungeon: 地牢游戏
- finish
- [godcmd](https://github.com/zhayujie/chatgpt-on-wechat/tree/master/plugins/godcmd): 管理员认证
- hello
- keyword: 关键字匹配回复固定内容
- linkai
- role: 角色扮演
- tool

## 效率工具

- [haikerapples/timetask](https://github.com/haikerapples/timetask): 自定义定时任务，功能强大。
- [ayasa520/TaskScheduler](https://github.com/ayasa520/TaskScheduler)：基于 APScheduler 库，提供了灵活的任务管理和调度功能。
- [Isaac20231231/send_msg](https://github.com/Isaac20231231/send_msg): 实现手动执行 api(基于 flask 的本地 http api)或微信命令发送消息通知到微信功能。

## 群管理

- [lanvent/plugin_summary](https://github.com/lanvent/plugin_summary): 群聊天记录总结
- [sineom-1/plugin_summary](https://github.com/sineom-1/plugin_summary)：群聊天记录总结
- [dfldylan/GroupInvitation](https://github.com/dfldylan/GroupInvitation)：特定关键字拉群
- [Tishon1532/bridge_room](https://github.com/Tishon1532/bridge_room): 多微信群桥接互通
- [sineom-1/revocation](https://github.com/sineom-1/revocation): 私聊和群聊消息的防撤回
- [xiaoqidaov2/MemberMonitor](https://github.com/xiaoqidaov2/MemberMonitor)：群成员监控插件，支持退群提醒
- [dividduang/blackroom](https://github.com/dividduang/blackroom): 小黑屋
- [Sakura7301/DarkRoom](https://github.com/Sakura7301/DarkRoom): 小黑屋

## 资讯工具

- [fatwang2/sum4all](https://github.com/fatwang2/sum4all): 网页、文件、视频、播客、图片大模型总结，支持联网搜索及多轮追问。
- [hanfangyuan4396/jina_sum](https://github.com/hanfangyuan4396/jina_sum): 基于 jina reader 和 gpt 总结网页内容，支持公众号、小红书、知乎等分享卡片链接。
- [6vision/Apilot](https://github.com/6vision/Apilot)：基于[ALAPI](https://admin.alapi.cn/account/center)及[韩小韩 API](https://api.vvhan.com/)接口，包含早报、摸鱼（视频）日历、明星八卦、查快递、星座运势及多平台热榜。
- [Lingyuzhou111/AIReport](https://github.com/Lingyuzhou111/AIReport): AI 日报，基于[天聚数行](https://www.tianapi.com)的 API 接口，包括图片版和文字版。
- [fatwang2/seek1assit](https://github.com/fatwang2/seek1assit): 基于[medisearch](https://search2ai.online/medisearch)(医疗大模型)的医疗咨询。
- [AnCool-OvO/HighSpeedTicket](https://github.com/AnCool-OvO/HighSpeedTicket): 高铁（火车）票查询插件,可查询直达跟中转两种方式,查询后可发送+问题进行进一步的筛选。
- [fred2045/plugin_rss](https://github.com/fred2045/plugin_rss)：通过 RSS(RSSHub)订阅各平台大 V 的最新消息，推送到微信群或微信号。

## AIGC

- [Lingyuzhou111/FluxUltra](https://github.com/Lingyuzhou111/FluxUltra): 基于[glif.app](https://glif.app/glifs)的 API 实现[FLUX1.1 [pro] Ultra](https://blackforestlabs.ai/flux-1-1-ultra/)模型的文生图，支持中英文提示词、多种图片比例和生成模式。
- [Lingyuzhou111/GLM_vision](https://github.com/Lingyuzhou111/GLM_vision)：基于智谱 GLM-4V 视觉模型，支持通过 URL 链接分析图片和视频内容。
- [Lingyuzhou111/Hunyuan_video](https://github.com/Lingyuzhou111/Hunyuan_video)：基于 SiliconFlow 平台的混元视频生成功能，支持通过文本描述生成视频。
- [lemodragon/Siliconflow2cow](https://github.com/lemodragon/Siliconflow2cow)：基于 SiliconFlow 的文生图、图生图，支持多模型、自定义尺寸和比例。
- [lanvent/plugin_replicate](https://github.com/lanvent/plugin_replicate): 基于[Replicate](https://replicate.com/)的 API 画图。
- [lanvent/plugin_sdwebui](https://github.com/lanvent/plugin_sdwebui): 基于 stable diffusion webui 的 api 画图。
- [mouxangithub/midjourney-proxy-on-wechat](https://github.com/mouxangithub/midjourney-proxy-on-wechat): 基于 MJ 画图。
- [LargeCupPanda/Cow-GPTs](https://github.com/LargeCupPanda/Cow-GPTs): 调用 GPTs。
- [cheungchazz/cow_plugin_kimichat](https://github.com/cheungchazz/cow_plugin_kimichat)：基于 kimi 及 Azure 识图 api 的对话、文件、图片、视频解析（基于 whisper 做音频转录）。
  - [single228758/cow-](https://github.com/single228758/cow-)：大规模重构，kimi 协议更新，基于 kimi 识图 API 做图片和视频总结，基于硅基流动 API 做音频转录。
  - [akun-y/plugin_iKnowKimichat](https://github.com/akun-y/plugin_iKnowKimichat)：新增 kimi 的付费 api key 支持，paddle ocr 做识图，对话管理及文件 cache。
- [KimYx0207/CogView2Cow](https://github.com/KimYx0207/CogView2Cow)：基于智谱 API 的文生图、文生视频。
- suno

## 娱乐

- [BenedictKing/chinesepua](https://github.com/BenedictKing/chinesepua): 中文词语提供幽默而富有创意的新解释,并生成一张方便分享的文字卡片。此外，它还可以生成精美的社交名片。
- [KimYx0207/RaiseCard](https://github.com/KimYx0207/RaiseCard): 举牌图片生成。
- [Lingyuzhou111/SearchMusic](https://github.com/Lingyuzhou111/SearchMusic): 多平台音乐搜索播放，支持酷狗音乐、网易音乐和神秘音乐三大平台。
- [Lingyuzhou111/DouyinDuanju](https://github.com/Lingyuzhou111/DouyinDuanju): 搜索抖音短剧并获取播放链接。
- [Lingyuzhou111/Img2Url](https://github.com/Lingyuzhou111/Img2Url)：上传图片到[图床](https://imgbb.com/)，以便后续通过 url 引用。
- [5201213/media_parser](https://github.com/5201213/media_parser): 多平台视频及图集解析。
- [AnCool-OvO/KFCwenan](https://github.com/AnCool-OvO/KFCwenan): 随机发送一句 KFC 文案，可以配合 timetask 插件实现每个星期四自动发送疯狂星期四文案。
- [qiupo/apitools](https://github.com/qiupo/apitools)：点歌及歌曲推荐。
- [WoodGoose/meme](https://github.com/WoodGoose/meme): 可玩性很高的单人、双人动态 meme 表情包生成。

## 常见问题

- 暂无

## 其他

- 任何想法、建议、需求、咨询等，欢迎加微信 fred2025 交流
- "CoW 插件交流群": 新插件及内测 demo 的第一手信息，与插件开发者交流，插件试玩，欢迎备注"cow 插件"入群。

![微信二维码](images/qr.jpg)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=fred2045/awesome-cow-plugins&type=Date)](https://star-history.com/#fred2045/awesome-cow-plugins&Date)
