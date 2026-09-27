---
layout: report-home
title: "V2EX 每日热点回顾"
permalink: /latest/
status: success
target_date: 2026-09-26
generated_at: "2026-09-27 08:27:41"
summary: "昨日主题 138 个，过滤 43 个，DeepSeek 分析 94 个，保留高价值内容 16 个。"
count_all: 138
count_excluded: 43
count_included: 95
count_high_signal: 0
count_valuable: 16
report_url: "/2026/09/26/"
data_url: "/data/2026-09-26.json"
---

# V2EX 2026-09-26 昨日新帖报告

<details class="topic-card" data-topic-id="1244814" markdown="1">
<summary>
<span class="topic-rank">1</span>
<span class="topic-title">独立开发无收入，该不该上 Claude Max？</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
发帖者用 20 美元 Codex 加 20 美元 Claude，感觉 Codex 额度不够、Claude 尚可，纠结是否升级 Claude Max 以加速产品上线；但产品无收入、多个项目从预期 2 个月拖到半年未上线，也担心“最贵会员做出没人买单的产品”。

### 关键要点
- **多数回复倾向不买**：没收入时先投推广而非升级会员；有收入、能覆盖每月 200 美元支出后再考虑。
- **额度不是瓶颈**：有独立开发者称每月 10 美元也够用，甚至用不完；同时做多方向时，真正制约的是精力与决策力，而非 token。
- **产品节奏问题**：半年出不来产品被视为拖延，MVP 要快，先调研需求、快速出原型，有人付费再迭代，无人付费就弃坑。
- **成功比例**：有回复认为产品本身只占两成，八成靠宣传；先解决“有没有人愿意用”，再谈“有没有人付钱”。
- **风险提示**：Claude 封号较频繁，长期依赖需考虑稳定性；也可先试用国内竞品或只买一个月体验。

### 评论补充
发帖者自认怕做 marketing、靠加功能拖延上线。也有反向观点：把月费当压力逼自己提速；或先买一个月尝鲜即可。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244814" target="_blank" rel="noopener noreferrer">独立开发产品无收入，有必要买 Claude Max 吗</a></span><span class="topic-stats">回复 44 · 收藏 7</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244853" markdown="1">
<summary>
<span class="topic-rank">2</span>
<span class="topic-title">从 Windows 11 换到 CachyOS 的实际体验与取舍</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者把 Windows 11 换成 CachyOS 后，从速度、输入法逻辑、软件 Bug 和系统设置四方面对比了两者，结论是响应速度与交互一致性提升明显，但生态与开箱即用仍是短板。

### 关键要点
- **速度**：网页打开与视频起播延迟比 Windows 快约一秒，作者认为此前卡顿源于系统而非网站优化。
- **输入法**：改用 Rime 后，Enter 直接输出已输入内容、Space 选首候选，避免了微软输入法 Web 联想反复自动开启和中文态下打英文需连按两次 Shift 的问题。
- **Bug 消失**：Chrome 中 AI Studio 长上下文输入卡顿、思源笔记首次点 Emoji 卡一秒、Clash Verge Rev 的 TUN 模式延迟生效，换 Linux 后均不再出现。
- **设置结构**：Windows 11 设置层层跳转，Linux 设置呈树状，逐级查找即可。
- **代价**：部分软件无 Linux 包，仍需自行折腾。

### 评论补充
有回复认为前三个月是适应门槛，之后会形成稳定工作流；LLM 可显著降低 Linux 配置成本。反对意见指出 QQ/微信适配、截图贴图、音乐软件缺失、新平台驱动（如 Ultra 笔记本）仍是问题，Windows 功能更全面。另有建议尝试 Debian、NixOS、deepin 或 Windows LTSC，并提醒工业软件（CAD、SolidWorks）用户需谨慎。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244853" target="_blank" rel="noopener noreferrer">脱离了 Windows 的保护，发现外边根本没有雨</a></span><span class="topic-stats">回复 41 · 收藏 11</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244848" markdown="1">
<summary>
<span class="topic-rank">3</span>
<span class="topic-title">geoip=cn 分流为何不够：DNS 污染与 geosite 方案</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容

主帖问：为什么代理软件需要大量规则并频繁更新，`geoip=cn` 直连、其余走代理是否够用？讨论的核心结论是：**单靠 `geoip=cn` 在多数场景可用，但存在 DNS 解析与污染的结构性缺陷**，因此需要 geosite 等域名规则补充。

### 关键要点

- **CDN 与分区解析**：同一域名用直连 DNS 和远程 DNS 解析，得到的 IP 可能完全不同，仅按 IP 判断会误判。
- **DNS 污染风险**：用 IP 规则必须先解析域名；若把被墙域名交给国内 DNS 解析，等于暴露访问意图，且可能拿到污染结果。
- **geosite + fakeip 更快**：有回复称域名规则配合 fakeip 可避免本地解析，比纯 IP 规则快约 30%。
- **兜底策略**：有用户采用默认 direct、对 gfw/proxy 手动添加规则，很少改动。
- **规则示例**：有配置列出 PROCESS-NAME、RULE-SET 去广告、GEOSITE 分类（AI、Netflix、cn 等）与 GEOIP 兜底。

### 评论补充

有观点认为，若所有 DNS 都走国内服务商，`geoip=cn` 确实够用，但需接受 DNS 请求交给国内服务商；也有用户建议维护 top100 中国站点白名单，其余走国外 DNS 与线路。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244848" target="_blank" rel="noopener noreferrer">geoip=cn 无法识别所有中国网站吗</a></span><span class="topic-stats">回复 35 · 收藏 10</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244818" markdown="1">
<summary>
<span class="topic-rank">4</span>
<span class="topic-title">开源 Edge TTS 服务：兼容 OpenAI 音频接口</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者开源了基于 Edge TTS 免费接口封装的语音合成服务 edgeTTS，项目地址为 https://github.com/DejavuMoe/edgeTTS 。其核心卖点是协议兼容 OpenAI 标准 `/v1/audio/speech`，现有客户端只需改 Base URL 即可接入。

### 关键要点
- **协议兼容**：支持 OpenAI 音频接口格式，迁移成本低。
- **长文本处理**：内置分段切片与音频流拼接，缓解长文本请求易失败的问题。
- **可调参数**：支持声音映射与参数微调。
- **部署方式**：提供 Docker 镜像一键部署。

### 评论补充
有用户反馈已用 Docker 部署成功，也有人用它做 txt 转 mp4 用于收听较难内容。作者明确该服务**不支持离线**，TTS 由微软处理，离线生产环境需另寻方案。多人对话合成功能作者暂不打算做，建议自行按角色流式调用不同音色。另有用户认为 Edge TTS 音质较差，改用 pocket-tts、kokoro、supertonic 等约 100M 级别的方案。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244818" target="_blank" rel="noopener noreferrer">[开源] 基于 Edge TTS 的语音合成服务，兼容 OpenAI 音频接口</a></span><span class="topic-stats">回复 7 · 收藏 14</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244846" markdown="1">
<summary>
<span class="topic-rank">5</span>
<span class="topic-title">Piko：KMP 写的多平台 PikPak 第三方客户端</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者用 KMP（Kotlin Multiplatform）开发了第三方 PikPak 客户端 Piko，安卓端为原生应用，Windows 端性能表现不错，代码开源于 GitHub：https://github.com/NihilDigit/piko 。

### 关键要点
- 并发八连接下载，改善弱网传输速度；作者称其 SDK 默认八并发取流，播放与下载都较快。
- 离线下载自动排除广告文件，解析合集文件便于挑选内容。
- 离线下载支持部分转存（下完自动删除）与完整预览。
- 可截取视频片段，查看账号传输配额信息，内置播放器。
- Windows on ARM 原生构建；UI 采用谷歌 M3 Expressive 设计语言，框架为 Compose 多平台版本。

### 评论补充
- 有用户反馈 Windows 端界面不清晰，修改高 DPI 缩放替代行为后仍无效，作者表示会研究。
- 作者已放出实验性 macOS 构建，但手头无 Mac 设备、完全未测试，需用户反馈；有用户试用后称比官方 Mac 版好用。
- 鸿蒙（hap）支持暂不可行，KMP 对鸿蒙支持不佳，作者欢迎社区贡献移植。
- 作者预告将加入信息流功能，可把文件夹当短视频刷。

### 限制
macOS 与 Windows 端存在未验证或已知显示问题，鸿蒙暂无计划，功能仍在开发中。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244846" target="_blank" rel="noopener noreferrer">Piko：高性能、多平台的 PikPak 客户端</a></span><span class="topic-stats">回复 18 · 收藏 4</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244915" markdown="1">
<summary>
<span class="topic-rank">6</span>
<span class="topic-title">电梯内吸烟如何应对：避让、取证与投诉路径</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
楼主在电梯口要求吸烟男子灭烟或等下一班，对方拒绝，物业调解无效，僵持约 10 分钟后楼主自行换乘另一部电梯。核心问题是：个人劝阻电梯吸烟往往无效，报警也多为和稀泥。

### 关键要点
- **多数回复主张避让**：直接换乘下一部电梯，避免与陌生人僵持，减少时间与人身风险。
- **取证是少数可操作手段**：有回复建议拍视频后报警，警察到场仍继续拍摄并明确告知正在拍摄。
- **地区执法差异明显**：有回复称上海对公共场所吸烟有罚款依据，南京等地则缺少公权力支持。
- **可走行政投诉路径**：有回复引用《江苏省爱国卫生条例》第三十三条第（九）款，建议向电梯管辖单位投诉、举报、信访乃至行政诉讼，要求其履行法定责任，链接为 https://www.jsrd.gov.cn/qwfb/sjfg/201311/t20131114_1221095.shtml 。
- **风险提示**：有体格较强的回复者表示自己曾因动手被强制传唤，认为冲突不划算，极端情况下可能让自己身处险境。

### 评论补充
评论普遍认为此类矛盾源于公权力执法缺位，个人硬刚成本高；也有观点反对“幸福者退让”，认为一味退让会纵容该行为。综合看，现实可行方案是避让优先，愿意投入时间者走取证加投诉、诉讼路径。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244915" target="_blank" rel="noopener noreferrer">应该如何对付电梯里吸烟的人？</a></span><span class="topic-stats">回复 23 · 收藏 0</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244832" markdown="1">
<summary>
<span class="topic-rank">7</span>
<span class="topic-title">Noiseless：用 LLM 给 X 推文降噪的 Chrome 插件</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者发布 Chrome 扩展 **Noiseless**，用于给 X（Twitter）网页内容“脱水”：柔性折叠广告/推广内容、支持自定义关键词屏蔽，并调用 LLM 从**事实可验证度、观点可信度、观点可行性**三个维度评估信息质量。作者称其为“加强版 Grok”，需自备 API，推荐可免费注册的 Google Gemini。

### 关键要点
- 作者无编程基础，靠 Gemini 约 5 天完成开发、测试并上架 Chrome 应用商店，代码已在 GitHub 开源（https://github.com/Jackroro/noiseless-extension）。
- 隐私设计：不常驻后台扫描，仅主动触发时处理；只提取文本上下文交给大模型，不留存个人历史，不做跨站追踪。
- 适用人群：在电脑上刷 X、希望快速验证信息真伪的用户；对固定话题不感兴趣者可加关键词屏蔽。
- 作者自述局限：Prompt 对长文本边界情况、不同平台排版兼容仍粗糙，交互与 Prompt 持续打磨中。

### 评论补充
- 有用户建议适配微博，作者回应若使用量增长再考虑，目前先专注 X。
- 讨论中有人指出 X 上不少内容搬运自知乎、小红书，简中区域国外消息才更接近源头；也有人推荐 HackerNews 与 Threads 作为信息密度更高的替代来源。
- 作者后续计划：推文提到项目或产品时自动分析优缺点，降低判断门槛。

风险提示：插件需将页面文本发送给第三方 LLM，实际隐私表现与评估准确度需自行验证；作者自述无编程基础，代码质量与长期维护存在不确定性。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244832" target="_blank" rel="noopener noreferrer">写了个给 X“脱水”的浏览器插件： Noiseless，尝试用 LLM 过滤信息噪声</a></span><span class="topic-stats">回复 17 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244939" markdown="1">
<summary>
<span class="topic-rank">8</span>
<span class="topic-title">集成 Tailscale 的 Android SSH/SFTP 终端 NovaScale 开源发布</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者发布 Android 版 NovaScale：一款把 Tailscale 内核直接集成进 App 的 SSH/SFTP 终端，无需安装 Tailscale 官方客户端，因此可与其他 VPN 同时运行。应用完全免费、代码开源（GPL，因借用 Termux 的 terminal rendering 代码），已上架 Google Play。

### 关键要点
- 基于 `libghostty-vt` + Termux 渲染方案，支持鼠标操作（tmux / herdr 等 TUI 场景可用）、剪贴板与 OSC52。
- 支持自定义控制服务器，即 headscale 或其他自建 tailscale coordinator。
- 内置 SFTP 文件浏览器（可直接编辑文件）、内置浏览器（访问 tailnet 内 Web 服务）。
- 支持后台代理，让第三方应用（如 Termius）借用 tailnet 连接。
- 技术架构：tailscale 源码包装为 lib，russh 通过 FFI 通信实现 SSH；tailscale lib 提供 socks5 代理供浏览器与其他进程使用。
- 开发方式：当前版本完全由 Codex 开发，作者只负责架构文档与验收；商店截图、描述、授权流程也交由 Codex 完成，提交隔天通过。

### 评论补充
有用户反馈 iOS 版 SSH 连接 Mac 后检测不到 tmux：其 tmux 由 zinit 管理而非 brew 安装，询问自动检测逻辑，并建议支持读取 `.zshrc` 或手动指定 tmux 路径。另有用户表示公司场景确实需要此类工具，但个人已改用 wireguard 方案。

相关链接：开源仓库 https://github.com/GalaxNet-Ltd/novascale-android ，Play 下载 https://play.google.com/store/apps/details?id=cc.galaxnet.novascale 。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244939" target="_blank" rel="noopener noreferrer">集成 tailscale 的 android SSH/SFTP 终端</a></span><span class="topic-stats">回复 2 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244886" markdown="1">
<summary>
<span class="topic-rank">9</span>
<span class="topic-title">GPT-Load 新增可逆脱敏与 Jev 智能护栏</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
自托管 AI 网关 GPT-Load 新增两项安全功能：**请求脱敏**与 **Jev 智能护栏**，分别针对上游信任问题和拼车场景的请求约束。项目地址见 [GitHub](https://github.com/tbphp/gpt-load)，官网 gpt-load.com。

### 关键要点
- **可逆脱敏**：在「全局设置 → 请求脱敏」添加正则规则，处理方式选「可逆加密」。匹配内容先加密再发上游，模型原样返回密文时由后端自动还原，聊天回复与客户端工具调用参数均适用。加密解密全在自部署后端完成，不请求模型、不依赖 Jev。
- **典型场景**：Vibe Coding 时代码、配置、日志中的邮箱、内部地址、密钥不必原样交给上游；例如让 AI 调用工具发信，模型传回密文，还原后工具拿到真实邮箱。
- **Jev 智能护栏**：在「全局设置 → 实验性功能 → 智能护栏」配置 Jev 渠道分组、密钥与模型，添加预设或自定义规则，设置命中动作（告警仅标记日志，拦截直接返回错误）与阈值，可按 AccessKey 生效。
- **组合使用**：请求先脱敏，再把处理后文本交给 Jev 审核。

### 限制与风险
脱敏后模型看不到原值，依赖原文的分析、检索可能受影响，上游内置工具拿到的仍是密文，且仅处理文本，图片与附件不在范围内。智能护栏为实验性功能，会增加判断耗时与调用费用，可能误判或漏判，需自行调教提示词规则。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244886" target="_blank" rel="noopener noreferrer">GPT-Load 新增安全功能：可逆脱敏和 Jev 智能护栏</a></span><span class="topic-stats">回复 0 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244809" markdown="1">
<summary>
<span class="topic-rank">10</span>
<span class="topic-title">computer use 窗口置顶干扰操作的隔离方案</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
使用 computer use 操作和测试时，被操作的窗口会置顶并抢占当前操作，作者询问是否有办法避免，或是否该另购一台 Mac mini 专门跑。

### 关键要点
- 主流桌面系统（Windows、Linux、macOS）通常只支持单一指针焦点，因此难以让自动化操作完全不干扰前台用户。
- 部分操作还要求 RDP session 处于前台才能触发，进一步限制了后台运行的可能。
- 常见方案是隔离环境：虚拟机、独立设备，或 Windows 上的 RDP Child Session 本地“远程桌面”。
- 有回复指出 codex mac 支持画中画小窗口不置顶，Windows 不行。

### 评论补充
有用户分享自研小工具 LocalRDP（https://github.com/charles-cty/LocalRDP），用 RDP Child Session 隔离 computer use，但作者自述基本没怎么测试过。作者也提到虚拟机限制较多，部分测试需要真机环境才更准确，且操作 App 时新窗口仍会直接置顶。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244809" target="_blank" rel="noopener noreferrer">computer use 在操作和测试的时候经常会让操作的窗口显示出来打扰我当前的操作</a></span><span class="topic-stats">回复 8 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244817" markdown="1">
<summary>
<span class="topic-rank">11</span>
<span class="topic-title">光猫 TR069 该删还是改 URL？地区差异与风险</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
用户花约 5 个月拿到光猫超密后，纠结是否删除 TR069，担心运营商把配置改回去或升级固件导致超密获取方法失效。评论共识是：运营商主动改配置的概率不大，但不同地区差异明显，处理方式需按地区选择。

### 关键要点
- **保守做法**：不删 TR069，只把连接 URL 改掉使其连不上，出问题还能恢复（回复 18128240）。
- **直接删除**：有用户两条宽带（电信、移动）均无 TR069，稳定运行两三年，无装维上门（回复 18128504）。
- **地区差异**：河南联通不删 TR069，每次重启光猫超密都会变；上海联通仅注册时改一次超密（回复 18129421）。
- **风险提示**：删 TR069 可能因失管被装维要求上门（回复 18128412）；TR069 可能重置超管密码（回复 18128980）；部分光猫插光纤后无法删除（回复 18128180）。
- **替代管理**：TR069 已非运营商唯一远程管理手段，删掉后仍可能被其他途径管理（回复 18129182）。

### 评论补充
有用户认为超密可直接花十几二十元购买服务获取（回复 18128063）。另有观点指出，若不想被远程管理，需不用运营商定制固件，但部分地区仅填 LOID 无法正常上网（回复 18129182）。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244817" target="_blank" rel="noopener noreferrer">关于 tr069 是否要删除</a></span><span class="topic-stats">回复 12 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244824" markdown="1">
<summary>
<span class="topic-rank">12</span>
<span class="topic-title">OpenAI 服务故障致 Codex 报 401，官方确认重置额度</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
OpenAI 出现服务故障，用户使用 Codex 时收到 `unexpected status 401 Unauthorized: Incorrect API key provided`。发帖人一度以为账号被封，查看 [status.openai.com](https://status.openai.com/) 后确认是平台整体故障，并非个人账号问题。

### 关键要点
- 故障表现为 API key 报错 401，容易被误判为账号或密钥失效。
- 多名用户反馈更新客户端后出现该错误，GitHub 上同类 issue 集中爆发。
- 有用户尝试退出重登、重启电脑均无效，说明问题在服务端。
- 官方人员 tibo 发文确认将进行额度重置，但据称是硬重置而非 banked 形式（[推文](https://x.com/thsottiaux/status/2103637477760311522)）。
- 有用户制作了重置监控页面：[rss.bz/zh/codex-reset](https://rss.bz/zh/codex-reset)。

### 评论补充
部分用户提到，此前已使用过重置卡的人这波相对受益；也有人指出当天下午 5 点本就接近自然重置时间，提前发重置卡意义有限。另有用户反馈故障期间正在进行的对话丢失，属于 Codex 常见问题。

**结论**：遇到 401 报错先查官方状态页，不要急于怀疑账号；官方已确认重置额度，可关注监控页面获取进展。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244824" target="_blank" rel="noopener noreferrer">这下得给个重置吧！ unexpected status 401 Unauthorized: Incorrect API key provided</a></span><span class="topic-stats">回复 15 · 收藏 0</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244870" markdown="1">
<summary>
<span class="topic-rank">13</span>
<span class="topic-title">把魔兽世界塞进网页：解包流程与容量内存难题</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者受油管博主移植 WOW 到网页的演示启发，在对方未开源的情况下自行尝试，把魔兽世界的模型、贴图解包后塞进浏览器，验证网页版可行性。目前阶段结论是任务系统、战斗、装备、职业、种族等原版内容基本都能实现。

### 关键要点
- **流程**：解包游戏资源，取出模型、贴图，再放入 Web 环境运行。
- **容量问题**：仅东部王国的城市、地形、建筑，模型+贴图+碰撞就约 1GB，贴图占大头；Gzip 等压缩无法压到可接受体积，一次性下载大包不现实。
- **两种取舍**：读条加载地图，或随玩家移动动态加载。为保留 WOW 无缝地图体验，作者倾向后者：只加载玩家周围一定范围的地图、模型与贴图，同时缓解浏览器内存占用。
- **代价**：持续移动会不断消耗流量；可把占大头的贴图转成 WebP 有损压缩以省流量。
- **演示**：https://jamfer.com/wowdemo 仅展示可行性，采用一次性加载整图方式，服务器带宽有限，只加载了压缩后的艾尔文森林（不含暴风城）。

### 评论补充
有回复确认演示运行流畅，并询问是否有服务端、怪物战斗逻辑是否在本地；作者说明这只是单机 demo，没有服务端，也远未达到可玩程度。另有回复提到已把 War3 流畅跑在网页里，可作为同类 Web 化案例参考。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244870" target="_blank" rel="noopener noreferrer">研究把魔兽世界塞进网页里的阶段成果</a></span><span class="topic-stats">回复 13 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244898" markdown="1">
<summary>
<span class="topic-rank">14</span>
<span class="topic-title">用 Claude Code 做的 Touch Bar Dock：DockTouchBar 开源</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者把闲置多年的 Touch Bar 改造成 Dock：用 Claude Code 开发了 DockTouchBar，只做一件事——把系统 Dock 常驻显示在 Touch Bar 上。首个可用版本一上午完成，后续主要精力用于打磨稳定性。

### 关键要点
- **功能**：按系统 Dock 顺序常驻显示 App，运行中有小圆点；单击切换，窗口在其他桌面时自动切过去；双击隐藏、长按退出（右边缘有“正在关闭…”倒计时）；睡眠唤醒、锁屏解锁后自动恢复。
- **兜底设计**：最右端小眼睛可临时把 Touch Bar 还给系统（亮度、音量），过一会儿自动回来，应对屏幕亮度被调到全黑。
- **实测数据**：M1 MacBook Pro（macOS 27）空闲时 CPU 0.0%、内存约 34 MB，约 1650 行 Swift，无第三方依赖。
- **限制**：Intel 机器未实测，仅在 Rosetta 下确认能启动；因使用系统私有接口无法上架 App Store，改用 Developer ID 签名并做 Apple 公证，DMG 放在 GitHub Releases。
- **踩坑经验**：连续快速点击不乱最耗时——切桌面动画期间系统会丢弃新的切换请求，接口却仍返回成功；最终放弃固定等待，改为校验前台 App 与当前桌面是否正确，不对就重试。

### 评论补充
评论仅有一条“看着还不错，试试看”及作者回应，无实质技术补充。

源码公开，个人使用免费，商用需另行授权（PolyForm Noncommercial）。GitHub：https://github.com/hooosberg/DockTouchBar ；产品页与开发日记：https://hooosberg.com/apps/docktouchbar/

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244898" target="_blank" rel="noopener noreferrer">我的 Touch Bar 吃灰多年，用 Claude Code 做了个只干一件事的 Dock</a></span><span class="topic-stats">回复 2 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244834" markdown="1">
<summary>
<span class="topic-rank">15</span>
<span class="topic-title">Antigravity 提示不支持地区：节点被送中的排查与规避</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
用户使用 Antigravity（agy）时遇到 `FAILED_PRECONDITION (code 400): User location is not supported for the API use`，同时 Google 搜索返回 301 跳转。评论区一致判断为代理节点被 Google 识别为受限地区（俗称“送中”），而非账号或工具本身故障。

### 关键要点
- **换节点**：多位回复者建议直接更换代理节点或更换服务商，换到非受限国家节点后即可恢复。
- **快速自检**：新开浏览器隐身窗口访问 google.com，若跳转到 `.com` 说明节点正常，若跳转到 `.hk` 则说明节点已被送中。
- **账号侧规避**：有回复提出可关闭 Google 账号的各项定位权限，并设置固定 home 地址，使定位不依赖 IP，从而减少被判定为受限地区的情况。

### 评论补充
多数回复将原因归结为节点问题，属于经验性共识，但缺少官方说明或可复现的验证数据；账号定位设置方案仅单一回复提及，效果待自行验证。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244834" target="_blank" rel="noopener noreferrer">我 antigravity 突然用不了了？提示不支持地区</a></span><span class="topic-stats">回复 9 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244921" markdown="1">
<summary>
<span class="topic-rank">16</span>
<span class="topic-title">MatrixMedia v0.11.6：视频号自动挂载小程序短剧与原生剧集</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
开源多平台视频矩阵发布工具 MatrixMedia（Electron + Puppeteer）发布 v0.11.6，核心功能来自社区贡献者 ababa00 的 PR：视频号发布时自动挂载小程序短剧和视频号原生剧集，GUI、CLI、HTTP、MCP 四条路径均已打通。

### 关键要点
- CLI 通过 `--sph-drama-id` / `--sph-series-id` 传入剧名即可完成挂载。
- 挂载失败不会误报成功：自动转存草稿，并以退出码 4 提示人工确认。
- 近期版本新增发布失败自动截图（点击失败次数可回看现场）与 macOS arm64 打包。
- 实现细节记录在仓库 `docs/sph-links.md`，涉及视频号发布页的 shadow DOM 穿透、antd 固定列隐藏克隆行、弹窗遮罩残留吞掉「保存草稿」按钮等坑。
- 项目采用 GPL-2.0 许可，Star 850+，仓库地址：https://github.com/hanliang97/MatrixMedia

### 评论补充
该主题暂无回复，以上信息均来自主帖正文。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244921" target="_blank" rel="noopener noreferrer">MatrixMedia v0.11.6：社区 PR 实现视频号自动挂载小程序短剧/剧集，发布失败自动截图</a></span><span class="topic-stats">回复 0 · 收藏 1</span></p>

</div>

</details>
