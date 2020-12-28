# 2020-12-21
# 🌟 v0.1.70-beta.15

新增
1. [Luuhai48 Oauth-Google](https://discuss.flarum.org/d/25577) 谷歌登陆。
1. [Luuhai48 Oauth-LinkedIn](https://discuss.flarum.org/d/25575) 领英登录。
2. [Sycho GitHub-Milestone](https://discuss.flarum.org/d/25521) GitHub 里程碑。

更新
1. [Askvortsov Moderator-Warnings](https://discuss.flarum.org/d/23228) 站务警告：邮件通知翻译支持。
2. [FoF Best-Answer](https://discuss.flarum.org/d/21894) 最佳回复：邮件内容翻译支持、新增「问题是否已自行解决」询问、设置项分类展示。
3. [FoF Byōbu](https://discuss.flarum.org/d/4762) 私密主题（原私人讨论）：发起按钮名变更、新增侧边栏入口、新增合并索引功能、发帖事件设置、邮件内容翻译支持。
4. [FoF Custom-Footer](https://discuss.flarum.org/d/17774) 自定义页脚：Beta 14/15 兼容。
5. [FoF Follow-Tags](https://discuss.flarum.org/d/20525) 关注标签：邮件内容翻译支持。
6. [FoF GitHub-Sponsors](https://discuss.flarum.org/d/22260) 应用申请链接更新。
7. [FoF Ignore-Users](https://discuss.flarum.org/d/20681) 屏蔽用户：新增屏蔽用户头像徽章、被屏蔽用户发帖会有提示。
8. [FoF Nightmode](https://discuss.flarum.org/d/21492) 夜间模式：可以对未自定义的用户应用默认颜色模式。
9. [FoF Subscribed](https://discuss.flarum.org/d/20917) 高级通知订阅：邮件内容翻译支持。
10. [FoF Upload](https://discuss.flarum.org/d/4154) 文件上传器：新增 S3 兼容模式。
11. [Flarum Tags](https://github.com/flarum/tags)：主次标签分家，使用独立新增按钮。
12. [Flarum Core](https://github.com/flarum/core)：后台管理面板侧边栏标题复用及描述翻译键变更；扩展程序开启关闭提醒；新增扩展程序讨论帖、文档、捐助、源码、支持超链接；新增扩展权限/设置有误提醒；新增打开设置按钮；新增求助按钮；新增扩展程序分类筛选；新增别名驱动设置。
13. [Flarum Nicknames](https://github.com/flarum/nicknames) 昵称：新增外显名称设置，管理员可以选择将用户名、昵称设为外显名称。
14. [Kilowhat Formulaire](https://discuss.flarum.org/d/23063) 表单生成器💰：新增数据导出、新增创建/更新/删除日期显示。

核心调整
1. Dayjs 日期库支持（Moment.js 自 beta.15 弃用）
2. 后台导航栏：「求助」更改为「帮助」
3. 后台：常规选项名变更「显示选择语言菜单」→「显示语言选择器」
4. 后台：测试邮件发送描述。
5. 昵称：更改个人昵称权限名。
6. 默认排序字段「热门回复」改为「热门主题」

其他调整
1. [FoF Frontpage](https://discuss.flarum.org/d/19256) 头版头条变更为精华。
2. [FoF Spamblock](https://discuss.flarum.org/d/17772) 标记破坏者 → 标记垃圾用户。
3. 使用 iflarum 短链接替换新浪短链接

错字更正
1. 后台「外观」打成了「常规」
2. 表情选择器「Flarum」打成了「FLarum」

# 2020-11-23
# 🌟 v0.1.70-beta.14.1.2
新增支持
1. [v17development Blog](https://discuss.flarum.org/d/25392) Flarum 博客。

# 2020-11-18
# 🌟 v0.1.70-beta.14.1.1

迁移并更新
1. Kilowhat-mailing 至 [Clarkwinkelmann Mailing](https://discuss.flarum.org/d/20443) 邮件发送：原文变更，翻译不更。

更新
1. [FoF Pretty-Mail](https://discuss.flarum.org/d/11178) 邮件美化：$baseUrl 变更为 $url。
2. [FoF Sitemap](https://discuss.flarum.org/d/14941) 站点地图：新增个别模式无法运行的条件提示。
3. [FoF User-Directory](https://discuss.flarum.org/d/5682) 会员名录：新增帖子数排序字段。
4. [Nearata Minecraft-Avatars](https://discuss.flarum.org/d/24468) 我的世界头像：取消留空表示禁用的机制，变为值无效提醒。

新增支持
1. [Clarkwinkelmann Bookmarks](https://discuss.flarum.org/d/25357-bookmarks) 书签。
2. [Clarkwinkelmann Group-List](https://discuss.flarum.org/d/25386) 用户组列表。

# 2020-11-11
# 🌟 v0.1.70-beta.14.1

Beta.14.1
1. [Flarum Core](https://github.com/flarum/core)：添加遗漏的编辑提示、修改灌水权限。

更新
1. [Clarkwinkelmann Carving-Contest](https://discuss.flarum.org/d/21828) 雕刻大赛：万圣节新增作品限制功能。
2. [Clarkwinkelmann Passwordless](https://discuss.flarum.org/d/22606) 邮箱链接登录。
3. [Clarkwinkelmann Scratchpad](https://discuss.flarum.org/d/22016) 开发便笺：新增保存前验证。
4. [FoF Linguist](https://discuss.flarum.org/d/7026) 语言学家：新增查找缺失翻译筛选项。
5. [FoF Links](https://discuss.flarum.org/d/18335) 导航栏链接：新增图标。
6. [FoF Mason](https://discuss.flarum.org/d/7028) 梅森表单：
7. [FoF Share-Social](https://discuss.flarum.org/d/20401) 分享：增加电报、Whatsapp。
8. [FoF upload](https://discuss.flarum.org/d/4154) 文件上传器：新增标题介绍。
9. [Kilowhat Formulaire](https://discuss.flarum.org/d/23063) 表单生成器💰：变量添加了空格，新增类型。
10. [Kyrne Websocket](https://discuss.flarum.org/d/23473) 新增开放范围。
11. [Maicol07 SSO](https://discuss.flarum.org/d/21666) 新增颁发域设置。
12. [SychO Profile-Cover](https://discuss.flarum.org/d/23437-profile-cover) 个人资料背景：新增权限。
13. [Tank Perspective](https://discuss.flarum.org/d/21784) Perspective API 内容安全：增加某些标题的释义、提供检测基分切换。

修复
1. [FoF Frontpage](https://discuss.flarum.org/d/19256) 修正徽章提示条。

优化
1. [Flarum Tags](https://github.com/flarum/tags) 清晰描述标签数量限制的描述。

<!--  -->

# 2020-10-21
# 🌟 v0.1.70-beta.14

兼容 Beta.14
1. [Flarum Core](https://github.com/flarum/core) 核心：新增插件依赖检查。
2. 兼容 Day.js 与 Moment.js

新增支持
1. [Clarkwinkelmann First-Post-Approval](https://discuss.flarum.org/d/25055) 前置审核。
2. [FoF OAuth](https://discuss.flarum.org/d/25182) 第三方登录。
3. [Funkeye Custom-Welcome-Hero](https://discuss.flarum.org/d/24664) HTML 欢迎横幅。
4. [Kyrne Evergreen](https://discuss.flarum.org/d/24695) 树型评论区。
5. [Nearata Signup-Confirm-Password](https://discuss.flarum.org/d/24689) 注册确认密码。
6. [Nearta Copy-Code-To-Clipboard](https://discuss.flarum.org/d/24852) 复制代码。

更新
1. [Flarum Mentions](https://github.com/flarum/mentions)：新增通知邮件。
2. [Flarum Subscriptions](https://github.com/flarum/subscriptions)：新增通知邮件。
3. [FoF Auth-GitLab](https://discuss.flarum.org/d/20371)：GitLab 登录。
4. [FoF Formatting](https://discuss.flarum.org/d/17770)：格式化。
5. [FoF Terms](https://discuss.flarum.org/d/11714)
6. [Kilowhat Audit-Log-Free](https://discuss.flarum.org/d/24432) 审计日志免费版。
7. [Kilowhat Audit-Log-Pro](https://discuss.flarum.org/d/24206) 审计日志专业版💰。
8. [Kilowhat Formulaire](https://discuss.flarum.org/d/23063) 表单生成器💰。
9. [Therealsujitk Show-Password](https://discuss.flarum.org/d/22727) 新增眼睛模式。
10. [Tituspijean Auth-LDAP](https://discuss.flarum.org/d/9515) 

优化
1. [Clarkwinkelmann Author-Change](https://discuss.flarum.org/d/21731) 作者变更。
2. [Flarum Lock](https://github.com/flarum/lock)
3. [Flarum Pusher](https://github.com/flarum/pusher)：修改刷新提示用词。
4. [Flarum Suspend](https://github.com/flarum/suspend)
5. [FoF Ban-IPs](https://discuss.flarum.org/d/20949)：IP 黑名单。
6. [FoF Best-Answer](https://discuss.flarum.org/d/21894)
7. [FoF Moderator-Notes](https://discuss.flarum.org/d/22925)。
8. [FoF Reactions](https://discuss.flarum.org/d/20655)
9. [Kyrne Shout](https://discuss.flarum.org/d/24073)
10. [Studosi Mail-Filter](https://discuss.flarum.org/d/23132)
11. [The-Turk Quiet-Edits ](https://discuss.flarum.org/d/22916)

<!--  -->

# 2020-8-9
# 🌟 v0.1.68 - 重大更新

迁移
1. [FoF Mason](https://discuss.flarum.org/d/7028)（原 Flagrow Mason）梅森表单：修改表单用语。

兼容 Beta13
1. [Michaelbelgium Discussion-Views](https://discuss.flarum.org/d/7339) 主题浏览量：适配 Beta13。
2. [Michaelbelgium Profile-Views](https://discuss.flarum.org/d/7596) 个人主页访客：适配 Beta13。

修复
1. [Flarum Core](https://github.com/flarum/core) 核心：校验检查语句的部分翻译。
2. [FoF Terms](https://discuss.flarum.org/d/11714) 服务条款：错别字。
3. [Reflar Webhooks](https://discuss.flarum.org/d/17812) 调整错误翻译。

优化
1. [Clarkwinkelmann Email-As-Display-name](https://discuss.flarum.org/d/22603) 邮件昵称：权限相关翻译。
2. [Clarkwinkelmann Passwordless](https://discuss.flarum.org/d/22606) 无密码登录。
3. [Flarum Core](https://github.com/flarum/core) 核心：邮件相关翻译。
4. [Flarum Pusher](https://github.com/flarum/pusher)：修改刷新提示用词。
5. [Flagrow Fonts](https://discuss.flarum.org/d/6207) 字体：修改中文版pangram。
6. [FoF Best-Answer](https://discuss.flarum.org/d/21894) 最佳回复：修正一个选项的描述。
7. [FoF Ignore-Users](https://discuss.flarum.org/d/20681) 屏蔽用户：修改屏蔽用词。
8. [FoF Subscribed](https://discuss.flarum.org/d/20917) 高级通知订阅：修改用语。
9. [FoF Terms](https://discuss.flarum.org/d/11714) 服务条款：修改用语用词。
10. [FoF User-Directory](https://discuss.flarum.org/d/5682) 会员名录：修改排序名。
11. [Matteocontrini Imgur-Upload](https://discuss.flarum.org/d/18491) Imgur上传：修改用词。
12. [Simonxeko Follow-Users](https://discuss.flarum.org/d/22628) 关注用户：修改用词。
13. [Tpokorra Post-Notification](https://discuss.flarum.org/d/20750) 贴子邮件通知：修正用词。

更新
1. [Askvortsov Categories](https://discuss.flarum.org/d/23184) 传统板块插件。
2. [Askvortsov Moderator-Warnings](https://discuss.flarum.org/d/23228) 站务警告。
3. [Askvortsov PWA](https://discuss.flarum.org/d/23219) 渐进式网页应用。
4. [Askvortsov SAML](https://discuss.flarum.org/d/22757)
5. [Clarkwinkelmann Author-Change](https://discuss.flarum.org/d/21731) 作者变更。
6. [Clarkwinkelmann Scratchpad](https://discuss.flarum.org/d/23016) 开发者便笺。
7. [Flarum Core](https://github.com/flarum/core) 核心：新增邮件测试功能。
8. [Flarumite Decontaminator](https://discuss.flarum.org/d/23735) 净化器：补充了一些说明。
9. [FoF Analytics](https://discuss.flarum.org/d/1983) 流量分析：新增了一些可选项。
10. [FoF Best-Answer](https://discuss.flarum.org/d/21894) 最佳回复：新增两个提示语句。
11. [FoF Byōbu](https://discuss.flarum.org/d/4762) 私人讨论：新增转公开通知和入口按钮、优化指定标签功能。
12. [FoF Drafts](https://discuss.flarum.org/d/20957) 草稿箱：新增定时发布功能。
13. [FoF Follow-Tags](https://discuss.flarum.org/d/20525) 关注标签：新增筛选功能。
14. [FoF Formatting](https://discuss.flarum.org/d/17770) 格式化：新增待办清单。
15. [FoF Forum-Statistics-Widget](https://discuss.flarum.org/d/22380) 统计小部件：新增不统计私人讨论的功能。
16. [FoF Gamification](https://discuss.flarum.org/d/20671) 游戏化：新增仿 Reddit 点赞布局。
17. [FoF Impersonate](https://discuss.flarum.org/d/9868) 身份扮演：新增登录理由。
18. [FoF Moderator-Notes](https://discuss.flarum.org/d/22925) 留言板：新增身份扮演联动功能、优化界面设计。
19. [FoF Nightmode](https://discuss.flarum.org/d/21492) 夜间模式：新增设备继承/独立选择功能。
20. [FoF Pwned-Passwords](https://discuss.flarum.org/d/18348) 密码泄漏检测：新增登录时检测功能。
21. [FoF Reactions](https://discuss.flarum.org/d/20655) 表情反应：新增反应人列表。
22. [FoF Upload](https://discuss.flarum.org/d/4154) 文件上传器：新增自添加扩展名功能、新增错误提示等。
23. [FoF User-Bio](https://discuss.flarum.org/d/17775) 个性签名：新增访问权限。
24. [Reflar Doorman](https://discuss.flarum.org/d/17845) 看门人邀请码：新增用户组邀请和邮件邀请函。
25. [The-Turk MathRen](https://discuss.flarum.org/d/22439) 数学公式：优化定界符设定，新增复制公式功能。
26. [The-Turk Password-Strength-Indicator](https://discuss.flarum.org/d/22624) 密码强度指示器：新增中等强度指示，新增显示密码功能，新增边框色跟随。
27. [TitusPiJean LDAP](https://discuss.flarum.org/d/9515) LDAP 登录。

新增支持
1. [Askvortsov Copy-Links](https://discuss.flarum.org/d/23885) 复制链接。
2. [Askvortsov Discussion-Templates](https://discuss.flarum.org/d/23950) 主题模板。
3. [Clarkwinkelmann Group-Invitation](https://discuss.flarum.org/d/24627) 用户组邀请链接。
4. [Clarkwinkelmann Likes-Received](https://discuss.flarum.org/d/24489) 点赞数统计。
5. [Clarkwinkelmann Popular-Discussion-Badge](https://discuss.flarum.org/d/24490) 热门主题标记。
6. [Datitisev Backup](https://discuss.flarum.org/d/23933) 备份论坛💰。
7. [Datitisev Maintenance](https://discuss.flarum.org/d/23930) 维护模式💰。
8. [Dem13n Auth-Mailru](https://github.com/Dem13n/auth-mailru)
9. [Dem13n Auth-Odnoklassniki](https://github.com/Dem13n/auth-odnoklassniki)
10. [Dem13n Auth-Vkontakte](https://github.com/Dem13n/auth-vkontakte)
11. [Dem13n Auth-Yandex](https://github.com/Dem13n/auth-yandex)
12. [Dem13n Nickname-Changer](https://discuss.flarum.org/d/21238) 昵称变更器。
13. [Dem13n Quad-Theme](https://discuss.flarum.org/d/22618) Quad 主题。
14. [Dexif Telegram](https://github.com/dexif/telegram) Telegram 登录。
15. [Dotronglong Hide-Me](https://github.com/dotronglong/flarum-hide-me) 匿名发帖。
16. [Estevao-Simoes Microsoft-Auth](https://github.com/estevao-simoes/flarum-microsoft-auth) 微软账号登陆。
17. [Artuu Imager](https://discuss.flarum.org/d/24202) 成像仪。
18. [FoF GitHub-Sponsors](https://discuss.flarum.org/d/22260) GitHub 赞助者。
19. [FoF Sitemap](https://discuss.flarum.org/d/14941) 站点地图：全新改版，增加多种生成模式。
20. [Irony Bing-Wallpaper](https://github.com/892768447/flarum-ext-bing-wallpaper) 必应壁纸。
21. [Irony Code-Insert](https://github.com/892768447/flarum-ext-code-insert) 代码插入与高亮。
22. [Irony Google-Search](https://github.com/892768447/flarum-ext-google-search) 谷歌搜索。
23. [Irony Webhook](https://github.com/892768447/flarum-ext-webhook)
24. [Jslirola Login2see-Plus](https://discuss.flarum.org/d/24193) 登录可见 Plus。
25. [Kilowhat Audit-Log-Free](https://discuss.flarum.org/d/24432) 审计日志免费版。
26. [Kilowhat Audit-Log-Pro](https://discuss.flarum.org/d/24206) 审计日志专业版💰。
27. [Kilowhat Custom-Paths](https://discuss.flarum.org/d/23872) 自定义路径💰。
28. [Kilowhat Formulaire](https://discuss.flarum.org/d/23063) 表单生成器💰。
29. [Kilowhat WordPress](https://discuss.flarum.org/d/22229) WordPress 集成💰。
30. [Kvothe keyboard-Shortcut](https://discuss.flarum.org/d/19301) 论坛快捷键。
31. [Kvothe Spoiler-BBCode](https://discuss.flarum.org/d/19044) 扰流板。
32. [Kyrne Shout](https://discuss.flarum.org/d/24073) 即时通讯。
33. [Kryne WebSockets](https://discuss.flarum.org/d/23473)💰
34. [Michaelbelgium MyBB-To-Flarum](https://discuss.flarum.org/d/5506) MyBB 论坛迁移工具。
35. [MigrateToFlarum Fake-Data](https://discuss.flarum.org/d/21160) 假数据。
36. [MigrateToFlarum Itemlist-Order](https://discuss.flarum.org/d/20477) 组件顺序调整。
37. [Nearata Embed-Video](https://discuss.flarum.org/d/24527) 视频嵌入。
38. [Nearata Is-Online](https://discuss.flarum.org/d/24654) 网络链接状态。
39. [Nearata Minecraft-Avatars](https://discuss.flarum.org/d/24468) 我的世界头像。
40. [Nearata Tags-Color-Generator](https://discuss.flarum.org/d/24644) 标签颜色生成器。
41. [NikoVonLas Auth-VK](https://discuss.flarum.org/d/20756) VK 登录。
42. [Reflar Recache](https://discuss.flarum.org/d/20791)💰
43. [Reflar Webhooks-Pro](https://extiverse.com/extension/reflar/webhooks-pro)💰
44. [The-Turk FancyBox](https://discuss.flarum.org/d/19535/64) 新版图片灯箱。
45. [The-Turk RegRole](https://discuss.flarum.org/d/24500) 注册角色。
46. [The-Turk Welcome-Widgets](https://discuss.flarum.org/d/24496) 欢迎部件。
47. [TituSpiJean Auth-SSOwat](https://github.com/tituspijean/flarum-ext-auth-ssowat)
48. [v17development Support](https://discuss.flarum.org/d/23741) 帮助中心💰。
49. [ZhiShiQ Pusher](https://discuss.flarum.org/d/18697)
50. [ZhiShiQ Queue](https://discuss.flarum.org/d/18697)
51. [ZhiShiQ Redis](https://discuss.flarum.org/d/18697)
52. [JuJia18 Chevereto](https://discuss.flarum.org/d/23585) Chevereto 图床。

Version Changes：[v0.1.67...v0.1.68](https://github.com/Littlegolden/flarum-lang-simplified-chinese/compare/v0.1.67...v0.1.68)