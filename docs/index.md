---
layout: report-home
title: "V2EX 每日热点回顾"
date: 2026-09-18 08:30:00 +0800
categories: [v2ex, daily-report]
status: success
target_date: 2026-09-18
generated_at: "2026-09-19 08:10:34"
summary: "昨日主题 263 个，过滤 163 个，DeepSeek 分析 100 个，保留高价值内容 32 个。"
count_all: 263
count_excluded: 163
count_included: 100
count_high_signal: 0
count_valuable: 32
report_url: "/2026/09/18/"
data_url: "/data/2026-09-18.json"
---

# V2EX 2026-09-18 昨日新帖报告

<details class="topic-card" data-topic-id="1242854" markdown="1">
<summary>
<span class="topic-rank">1</span>
<span class="topic-title">Claude 防封号半年 100+ 账号实操经验</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者以半年 100+ 账号的实操，总结了一套降低 Claude 封号概率的流程，覆盖邮箱、IP、KYC、支付和日常使用五个环节，适用于个人、小团队和中等团队。

### 关键要点
- **邮箱**：优先谷歌（权重更高，不易触发手机验证），其次微软；被封多次的公司自建邮箱可能已进黑名单。
- **IP 与环境**：用指纹浏览器（如火狐 147 内核）搭配住宅 IP，作者买过加利福尼亚住宅 IP；弹不弹 KYC 主要看 IP 质量。
- **KYC**：可找淘宝/闲鱼代过，秒封多为渠道问题且通常包退款；代过流程是付款弹 KYC 后回设置页完成 KYC 再付款，资料不行会秒封。
- **支付**：作者用 Coinepay 虚拟卡，一卡一号；也可用 N26、空中云汇，或通过美区 Apple ID + Apple Pay 绕过。付款页协议勾选位置反映卡 bin 要求，换 IP 和环境重新注册可改善。
- **使用**：少登录官网，不推荐本地客户端；订阅后通过 CLIProxyAPI、new-api 等自建中转站，把号放到海外服务器用 SSH 授权开发养号，谷歌云一个出口 IP 挂 5-6 个号。

### 评论补充
有回复称用谷歌注册 4 个号、频繁换 IP 且多人登录也未封，用 Apple 订阅；也有人手机订阅后换设备登录次日被封。另有用户表示 Teams/企业版长期未封，怀疑 A 社对企业版手软；客户端 browser use 风控明显高于 CLI。整体共识是封禁策略随机、难以完全预测。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242854" target="_blank" rel="noopener noreferrer">Claude 封号问题，想使用 claude 不被封，这是我近半年 100+账号跌跌撞撞的一些心得</a></span><span class="topic-stats">回复 70 · 收藏 66</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242824" markdown="1">
<summary>
<span class="topic-rank">2</span>
<span class="topic-title">三十岁自述：从原生家庭、买房到相亲拉扯的独立之路</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
一位三十岁程序员回顾成长、家庭、买房、相亲与自我重建的经历，核心结论是：把重心放回自己身上，改变从三十岁开始也不晚。

### 关键要点
- **原生家庭**：父母在外，由祖辈带大，饮食不健康导致营养不良并遭遇霸凌；父母被描述为严重 NPD，把子女当情绪垃圾桶，作者选择与家庭保持距离。
- **工作与买房**：在省会本土公司被 PUA 式加班，进入一线城市子公司后才体会到正常双休与尊严；买房时不懂政策，迁户口、高点接盘，首付亏完，多年年光，靠商转公和提前还款才缓解。
- **相亲经历**：异地拉扯数年，对方在推进关系时反复谈钱（18.8 万彩礼、五金、婚前买车写名、婚后管钱、同居期间具体经济支持），作者最终拒绝并封心锁爱。
- **独立实践**：疯狂购物、看演出音乐剧、旅游、读心理学哲学、与家里保持距离，开始“中年叛逆”，按自己的思想行动。

### 评论补充
有回复认为对方是在向下兼容、把作者当备胎，建议“光撒网、小步验证、光速止损”；也有人指出成年人很难改变，不要幻想几年后对方会变。另有评论认为一段好的感情应引导人向上，三十岁开窍不晚。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242824" target="_blank" rel="noopener noreferrer">我的三十岁，以及从龟到独立人格的改变</a></span><span class="topic-stats">回复 94 · 收藏 47</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242973" markdown="1">
<summary>
<span class="topic-rank">3</span>
<span class="topic-title">zcode 被指静默打包上传整个代码库与 git 历史</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有用户称 AI 编程工具 zcode（智谱）在未告知的情况下，将整个代码库连同 git 开发历史加密打包上传，Windows 与 macOS 均受影响，并附有推文与博客链接作为佐证。发帖人要求官方解释，帖子引发大量讨论。

### 关键要点
- 争议核心不是“AI 需要读代码”，而是**上传范围与告知义务**：正常 Agent 按需检索片段，全量代码库不应进入 prompt。
- 评论指出被上传的不只是当前代码，还包括 **git 完整开发历史**，性质更严重。
- 有说法称打包加密、密钥仅存于服务端，且存在重试上传、增量上传、无路径消除。
- 可执行建议：正在使用 zcode 的用户先关闭或卸载，改用可自行编译、风险可控的方案。
- 同类风险并非孤例，评论提到 grok 也曾有类似问题。

### 评论补充
部分人认为“交给 AI 就别谈隐私”，但被反驳：问题在于私自上传用户未授权的数据。也有观点认为所有 Agent 都可能上报代码，只是量级不同。

### 待核验
目前主要依据为个人验证与外部链接，官方尚未回应，结论需以后续说明为准。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242973" target="_blank" rel="noopener noreferrer">有用 zcode 的，马上关闭 ！它打包上传了你整个代码库！</a></span><span class="topic-stats">回复 109 · 收藏 9</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242843" markdown="1">
<summary>
<span class="topic-rank">4</span>
<span class="topic-title">用 pi 三周替代 Claude Code 与 Codex 的实践与插件改造</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者集中使用 pi 三周后，从 Claude Code（cc）和 Codex 迁移到 pi，并自行改造插件与工具。迁移契机包括：cc 曾发生提示词注入的破坏性安全事件、发布长篇安全通告、以及悄悄改变功能不发公告（如突然不用 edit/write 工具而改用 bash），导致行为黑盒化。

### 关键要点
- **pi 的取舍**：默认只有 4 个 tool，干净、快，但简陋，需要自己施工；作者坚持不用现成插件，避免 opencode 那种“上来一堆功能”的挫败感。
- **自研插件**：在 `~/.p/agent` 常驻窗口开发 peer 插件，可临时发消息让 peer 调整插件行为；参照 example 做 subagent，并重写全部 4 个默认工具，参考 cc/codex 的提示词与能力扩展。
- **subagent 观点**：反对 cc/codex 大量自动起 subagent，认为不可见、每次销毁上下文、浪费 token；主张按需手动注入，非必要不启用。
- **并发工具差异**：claude/gpt/gemini/grok 支持并发 tool 调用（同一文件多处 edit 或 read+edit+bash 并发），deepseek 不支持，表现为线性执行。
- **系统提示词控制**：目前约 11k，作者计划控制在 10k 上下，再多就接近 cc/codex。

### 评论补充
- pi 不能直接用 Claude 订阅账号，需反代或插件；作者用 gpt 为主，按情况切换。
- 有用户指出 deepseek 可并发 read/edit，只是主动性低，可通过工具提示词强制要求。
- 有用户反馈 pi 插件功能不正交、重叠难审计；作者回应自己开发可规避。
- 其他工具对比：有人主力用 dsh、omp，也有人用 Codex 的 Computer Use 操作无 API 软件。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242843" target="_blank" rel="noopener noreferrer">集中用了 3 周 pi，可以搬家了，再见了 claude code，再见了 codex。刚看 pi 要发布 3.14 版本了</a></span><span class="topic-stats">回复 43 · 收藏 16</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242845" markdown="1">
<summary>
<span class="topic-rank">5</span>
<span class="topic-title">前端求职难度上升：降薪近家与银行外包如何选</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
楼主重新找前端工作，体感难度明显高于前两年：岗位要求从 React/Vue 扩展到 Node、Next、微前端、性能优化，部分还要求 3D、AI，但薪资涨幅有限。他同时担心 AI 提效会让普通前端岗位继续减少，甚至考虑降薪或接外包。

### 关键要点
- 楼主最终拿到两个 offer：一是降薪 10%–20%、离家 3km 的医药行业公司（称加班极少）；二是平薪银行外包，通勤 20–30 分钟，签第三方人力合同。
- 评论区多数人倾向选 1：离家近对生活幸福感提升大，有回复称“降薪 30% 也愿意”。
- 对银行外包普遍持负面看法：有回复称外包进去后容易待岗离职，且该外包并无薪资优势。
- 有从业者认为普通初中级前端岗位会持续减少，公司前端正转全栈，外包也要求全栈。
- 选择还需看降薪基数：高薪降 10% 影响有限，低薪降 10%–20% 可能影响生活。

### 评论补充
有回复认为整个开发行业都在收缩，测试岗位受影响相对小；也有人提醒银行外包要确认季度、年度提成能否分到。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242845" target="_blank" rel="noopener noreferrer">最近找工作有点把我整不会了</a></span><span class="topic-stats">回复 73 · 收藏 9</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242997" markdown="1">
<summary>
<span class="topic-rank">6</span>
<span class="topic-title">ZCode 3.12.3 被证实静默上传完整 Git 历史至阿里云 OSS</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有博客指控智谱 ZCode 桌面端在登录状态下，把整个工作区（含完整 `.git` 历史）打包加密后直传阿里云 OSS，且解密私钥只在服务端。楼主在本机（Windows，ZCode 3.12.3.7463）逐条核对，结论是**机制全部属实**。

### 关键要点
- 磁盘证据：`~\.zcode\v2\checkpoints\` 下存在 `pending\*.tar.gz.enc`（258MB）、`envelope.json`、`manifests/`、`state.json`，字段与博客一致（`aes-256-ctr` + `rsa-oaep-sha256`）。
- 打包内容：明文 manifest 显示 151 个文件，其中 `.git/objects/pack/pack-*.pack` 约 246MB，占加密体 99.5%；`extra-manifests` 还把全局 `settings.behavior.json`、`skills.json` 一并打包。
- 代码证据：`app.asar` 中命中 `/api/v1/snapshot/upload-credential`、OSS 直传表单（`policy`/`x-oss-signature`/`x-oss-security-token`/`callback`）、`captureBeforePrompt(...)` 无设置检查。
- 无法关闭：检索不到任何抓取/上传开关或环境变量；`repoSnapshotIndexingEnabled`、`optimizeAgentExperienceEnabled` 默认 false 也不影响上传。
- 单向传输：客户端只有 `upload-credential`，没有 restore/download 接口；本机已有成功上传记录（`Desktop\Mano_hand`，2.36MB，本地 `.enc` 被清理）。

### 评论补充
- 有用户称未登录时没有 `checkpoints` 目录和 `.enc` 文件，也有人认为与客户端版本有关，老版本不上传。
- 讨论集中在智谱信用与隐私风险，并延伸到其他 AI 工具是否同样上传代码。

### 止血建议（Windows）
清空并删除 `~\.zcode\v2\checkpoints`，在原位置创建同名只读文件，或用 NTFS ACL 拒绝写入；代价是失去检查点/回滚功能。仅删 pending 文件会被重新打包重传，需锁目录或退出登录。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242997" target="_blank" rel="noopener noreferrer">怎么看待“ZCode 静默上传”的操作，有啥说法吗？</a></span><span class="topic-stats">回复 41 · 收藏 4</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242892" markdown="1">
<summary>
<span class="topic-rank">7</span>
<span class="topic-title">300元预算翻墙路由器推荐：GL-MT3600BE、磊科N60 Pro等</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
用户用 AC68U 刷梅林+fancyss 在投影上看 Emby，近期翻墙不稳定；已排除梯子问题（iOS 小火箭直连 Emby 正常），fancyss 降级 lite 和回退旧版均无效，预算约 300 元，询问是否该刷 OpenWrt。

### 关键要点
- 被多次推荐：**GL-MT3600BE**（京东领券后约 440 元可入手），但有人反馈买两台后信号偶尔断，转而推荐 CUDY。
- 其他候选：磊科 N60 Pro、CUDY TR3000、京东云雅典娜/百里、阿里云 AP8220（已停产转卖）。
- 替代方案：路由器照常买，另花约 100 元买盒子做旁路网关；或任意 OpenWrt 设备装 passwall/openclash。
- 低成本玩法：R1S 刷 OpenWrt 装 OpenClash，一口接运营商、一口接无线路由 WAN；小米路由器解锁 SSH 后刷 shellcrash；armbian + shellcrash。

### 评论补充
有人建议把投影 IP 全部走代理，但楼主反馈在 fancyss 内设置后仍很慢，说明瓶颈可能不在分流规则。选购时需注意京东把不同产品按颜色混排排名，容易误导。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242892" target="_blank" rel="noopener noreferrer">翻墙路由器求推荐</a></span><span class="topic-stats">回复 40 · 收藏 15</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242976" markdown="1">
<summary>
<span class="topic-rank">8</span>
<span class="topic-title">锐评用过的 Agents/Harness：CC、Codex、Grok、DSH 等横评</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者按使用经历横评多款终端/桌面 Agent，核心结论是：Claude Code 功能最全、概念首发（subagent、workflow、focus 模式），但接第三方模型缓存命中率低于 chat 协议、且不开源，最终放弃；当前主力是 Grok，界面流畅、开源、兼容 CC 的 MCP、默认 chat 协议对缓存友好。

### 关键要点
- **Codex CLI**：靠批发 Plus/Team 号白嫖时体验极佳，后强制 responses 协议、便宜号消失、重心转桌面端，遂弃用。
- **DeepSeek Harness**：预览版，官方迭代会改动布局，用户自定义“装修”易白费，作者选择等稳定版。
- **pi/omp、opencode**：pi 的 TUI 审美差、插件有 bug；omp 设置繁杂；opencode 号称 CC 替代、有免费模型，但 TUI 自定义低、session 用数据库管理，用不顺手。
- **Gemini/agy、copilot、cursor、zcode**：Gemini 额度少；copilot 额度少；cursor 因不看代码弃用；zcode 闭源且 remote 会话不共享。
- **reasonix/whale**：为 DeepSeek 优化的社区 agent，DSH 出来后生态位被抢，DS 涨价致开发者动力下降。

### 评论补充
- 有用户认为 agent 横评难量化，能力、易用、稳定、性价比各维度用户一头雾水。
- 多人反馈长期主力仍是 Claude Code，桌面端 Codex 不差；国内有用户锁死 DSH。
- 有评论称 Gemini 3.8 flash 写前端不错、速度快，闲鱼低价可买 18 个月 Pro；反重力（Antigravity）限制地区 IP 与账号区域，可通过 Google 政策页申请更改区域。
- 有用户反映 codex+cc switch+ds 4.1 组合在长会话读图时出现 400 错误，转用 DSH。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242976" target="_blank" rel="noopener noreferrer">锐评一下用过的 Agents/Harness</a></span><span class="topic-stats">回复 19 · 收藏 15</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242856" markdown="1">
<summary>
<span class="topic-rank">9</span>
<span class="topic-title">注销美国 Delaware LLC 的方式与成本对比</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
一位开发者用 Stripe Atlas 注册了 Delaware LLC 接入收款，因付费用户少、维护成本高，打算注销公司，询问注销方式、费用及 IRS 报税注意事项。

### 关键要点
- **维护成本**：Delaware 年审约 $300，Stripe Atlas 地址代理 $100/年，合计约 $400/年，IRS 报税费用另计。
- **注销渠道**：Stripe Atlas 提供注销服务但价格不便宜；有用户合作 10 年的中介报价约 4k 人民币。
- **低成本方案**：有回复提到 Legalinc（Stripe 合作注册代理）约 $99，仅处理州级解散，IRS 税务仍需自己处理；全套第三方约 4k 人民币。
- **时间点**：建议在年审前注销，否则可能被扣上一年年审费。
- **不注销影响**：对国内用户影响不大，但以后出国（美国）可能有一点影响。

### 评论补充
有用户指出，业务体量不够时不必急着注册公司，个人可用的支付渠道不少，做大后再注册；也有人提到可找人平摊费用代接 Stripe 支付，但需审核业务正规性。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242856" target="_blank" rel="noopener noreferrer">请问注销美国公司通过什么方式比较好</a></span><span class="topic-stats">回复 18 · 收藏 17</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242885" markdown="1">
<summary>
<span class="topic-rank">10</span>
<span class="topic-title">北京5000元预算，来回40公里电动自行车怎么选</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
北京用户预算 5000 元，通勤来回 40 公里（单程约 20 公里），求电动自行车推荐。评论共识是：这个距离必须优先考虑电池容量和充电便利性，否则日常通勤会非常折磨。

### 关键要点
- **电池优先**：多位回复建议选锂电池或大容量电池。有用户实测 25km/h 骑 16 公里要一个多小时，换三电后约 30 分钟；电池买小、充电不方便会明显影响体验。
- **品牌分歧**：有人推荐雅迪 T 系列（老牌、用料扎实），也有人推荐金箭零界 750（6000 出头）或零界 900；九号 Mz3/Mz5、极核 AE3/4/5i 被提及，但被认为不改装没意思、改装又贵。
- **避坑提醒**：有用户点名九号 FZ3110 为 AB 货，最高速度 36km/h，续航约 100 公里，需每天充电，且电量低于 20% 会降速；红绿灯多、单灯 140–180 秒的路况下，20 多 km/h 会很难受。
- **其他方案**：也有人建议直接买电摩，或改骑自行车/共享单车。

### 评论补充
有用户提醒，5000 元预算若再配大锂电，电池本身可能就要三四千甚至五千以上，需重新评估总预算。另有回复给出两个站内相关讨论链接可供参考。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242885" target="_blank" rel="noopener noreferrer">电动自行车通勤，来回一共 40 公里，求推荐</a></span><span class="topic-stats">回复 40 · 收藏 9</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242905" markdown="1">
<summary>
<span class="topic-rank">11</span>
<span class="topic-title">Codex 登录短信验证的规避方法：开 2FA 或充值 Plus</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容

原帖作者用接码平台注册的 OpenAI 账号，手机号已失效，担心使用 Codex 时被要求短信验证。多位回复者给出了可复用的规避路径，核心结论是：**新注册账号通常不再强制短信验证，关键是注册后立即开启 2FA 并关闭短信验证，或直接充值 Plus。**

### 关键要点

- **注册后立刻开 2FA**：网页注册成功时账号处于已登录状态，此时进入个人设置的安全页开启 2FA、保持短信验证关闭，并设置密码。之后再登录 Codex 会走 2FA 而非短信。有回复称本周用此法为两名新员工开通了 Pro 5x。
- **充值 Plus 可消除验证**：多位回复者表示开通 Plus 后登录 Codex 不再要求手机号，包括“今天复现”的反馈。
- **邮箱选择有讲究**：有回复称不要用自定义域名邮箱，开 Plus 后登录 Codex 仍要验证码；建议用 Gmail、微软等常见邮箱。
- **账号可替换**：Codex 的代码和记忆在本地，换号成本低，不必执着于旧账号。

### 评论补充

存在分歧：有回复称“不久前 Codex 仍要验证、Chat 不要”，也有回复称“现在好像已经没有二次验证了”。另有回复建议用 kilocode 登录 ChatGPT OAuth 使用免费版 Codex 额度，先测试是否需要手机认证。若嫌麻烦，也有人建议直接购买已充值好的成品号。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242905" target="_blank" rel="noopener noreferrer">请教使用 codex 时要验证短信怎么办？</a></span><span class="topic-stats">回复 21 · 收藏 10</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242839" markdown="1">
<summary>
<span class="topic-rank">12</span>
<span class="topic-title">JEV 被指营销过度：本质是垂直领域小模型，已有开源复刻</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
V2EX 用户对推上热炒的 JEV 提出质疑，认为其本质是把“高质量小模型 + 分类/排序 + constrained output + calibration”包装成漂亮的 Decision Model 产品，营销投入大于技术门槛。

### 关键要点
- **定位**：多位回复认为 JEV 更像“意图识别小模型”或文字版 YOLO World，只做选择与判断，适合审核、结构化输出等垂直场景。
- **优势**：速度是核心卖点，有回复称达到 100ms 级别，普通小参数模型在决策任务上仍偏重、偏慢。
- **争议**：有观点认为“准确、快速、便宜”三者任一不满足即失去价值，且结果正确性存疑；也有人认为方向看好但技术门槛不高。
- **开源复刻**：评论给出多个复刻项目，包括用 qwen 0.6b 模拟的 openjev、NanoJev，以及 45M/37M 的 needle2、needle3 小模型。

### 评论补充
有回复指出国内面壁、讯飞已推出 4B 级小通用 agent 但水花不大，认为国外更擅长炒作；另有观点认为该架构难度低于 CoT，开源替代很快可用。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242839" target="_blank" rel="noopener noreferrer">推上吹的火热的 jev，是不是还不如小参数的开源模型，感觉钱都去做营销了</a></span><span class="topic-stats">回复 28 · 收藏 10</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242869" markdown="1">
<summary>
<span class="topic-rank">13</span>
<span class="topic-title">极简 Chrome 代理切换扩展 proxi 开源并提交商店</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者 Lentin 因原有 smartproxy 操作繁琐（切换需点两次才显示完整浮窗），用 codex 编写了一个极简 Chrome 代理切换扩展，强调美观与易用，并省略了部分功能，理由是现代代理软件的分流能力已较完善。项目已开源，商店版本提交审核中。

### 关键要点
- 开源地址：https://github.com/codexss/proxi
- 默认仅放行 `127.0.0.1` 等本地回环地址，其余流量走所设代理服务器。
- 支持手动添加跳过代理规则，如 `10.0.0.0/8`，语法参考 Chrome 官方 bypass_list 文档。
- 不支持 SOCKS5 用户名密码：作者称 Chrome 官方 proxy 接口未提供该选项。
- 分流需求建议交给后端代理软件处理，而非扩展本身。

### 评论补充
有用户建议支持多套规则（如抓包代理与世界代理分开），作者回应由后端代理实现分流。另有用户询问多接口管理，作者同样以接口限制为由未支持，并有人推荐 ZeroOmega 作为替代。评论中还出现另一款同类扩展 ProxySwitch 的商店链接。整体反馈以“已安装/已 star”为主，实际使用评价较少。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242869" target="_blank" rel="noopener noreferrer">搓了一个极简的 Chrome 代理切换扩展</a></span><span class="topic-stats">回复 16 · 收藏 15</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242828" markdown="1">
<summary>
<span class="topic-rank">14</span>
<span class="topic-title">编程 Agent 上下文窗口怎么设：350K 窗口与压缩策略</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
主帖综合 2023–2026 年论文、基准与工程博客，回答编程任务中上下文窗口该开多大。结论是：标称窗口不等于有效窗口，最优实践不是调一个数字，而是「稳定前缀缓存 + 缓存边界下压缩 + 外置存储」的组合。

### 关键要点
- **有效窗口远小于标称值**：Lost in the Middle 发现中间位置检索准确率下降三成以上；LongCodeBench 显示多数模型编程准确率峰值在 64K–128K，之后单调下降，Claude 3.5 Sonnet 在 LongSWE Bench 从 32K 的 29 分跌到 256K 的 3 分。
- **推荐配置**：1M 模型设 350K 工作窗口、70K 最大输出、280K 压缩触发点（窗口减输出）。作者保留意见：多数模型 256K 后编程能力已退化，触发点可收到 245K–260K。
- **压缩贵在缓存失效**：缓存命中约按一成计价，压缩后新上下文对不上旧缓存，下一轮必然全价重建，一次压缩代价约为普通轮次十倍以上。
- **优先外置而非压缩**：大文件、长日志写成文件让 agent 用 grep/sed 读取，不占窗口、不触发压缩、缓存友好。
- **稳定前缀**：去掉系统提示中的分钟级时间戳，用静态占位符替换动态字段，TokenPilot 报告缓存命中率从 38.7% 升到 79.2%，成本从 8.31 美元降到 4.35 美元。

### 评论补充
有回复指出 coding agent 的上下文管理需在设计阶段考虑稳定前缀、消息分类、温区定义、修剪机制与压缩水位线，pi 只设一条 compact 高水位线属朴素设计；并强调关键信息无法永远不丢，agent 需能调用外部记忆回溯。另有用户观察到 Claude Code 长期不 /clear 时 API 等价费用消耗极大，但订阅百分比消耗速率感觉与上下文未累积时相近；Codex 默认 200 多 K 够用。关于压缩是否应由模型自身决定，评论存在分歧：一方认为应作为 RL 阶段的一部分、最终呈现为 server side compaction，第三方 harness 空间有限；另一方以 Qwen 尝试让模型自主决定思考模式为例，认为可能让模型犹豫拖沓。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242828" target="_blank" rel="noopener noreferrer">编程任务中，模型的上下文窗口开多大最合适?</a></span><span class="topic-stats">回复 7 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243021" markdown="1">
<summary>
<span class="topic-rank">15</span>
<span class="topic-title">ZCode 静默上传工作区：三法域法律分析与投诉渠道模板</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容

主帖由 DeepSeek 代笔，围绕 ZCode（智谱 AI 旗下 AI 编程工具）在用户登录状态下静默打包上传整个工作区及完整 Git 历史、且无法通过界面关闭的行为，梳理中国内地、香港、美国三法域的法律风险，并给出可直接使用的投诉邮件模板。

### 关键要点

- **中国内地**：涉嫌违反《个人信息保护法》第 14 条（告知同意）、第 39 条（跨境单独同意）、第 6 条（最小必要）；《数据安全法》第 27 条（安全保护义务）、第 31 条（重要数据出境评估）；并可能触及商业秘密与《刑法》第 219 条。PIPL 第 66 条最高可处五千万元或上一年度营业额 5% 罚款。
- **香港（主帖认为风险最高）**：智谱为港交所上市公司（02513.HK，第 18C 章特专科技公司），涉《个人资料（私隐）条例》保障资料原则及第 64 条（最高罚款 100 万港元、监禁 5 年）；《证券及期货条例》第 XIVA 部内幕消息披露义务；港交所《上市规则》持续披露责任。
- **美国**：未在美上市，但涉 CFAA（超越授权访问）、DTSA（商业秘密）及未来赴美上市的 SEC 网络安全披露规则。
- **投诉渠道**：内地 `jubao@12377.cn`、`Appzhili@cac.gov.cn`；香港私隐公署 `complaints@pcpd.org.hk`；香港证监会 `complaint@sfc.hk`；港交所 `ListingComplaints@hkex.com.hk`。模板含中英文双语，建议附隐私政策截图与抓包记录。

### 评论补充

评论普遍认可投诉动机，但质疑实际效果：有回复指出内地监管正扶持 AI 企业，投诉可能难有结果，建议转向香港证监会；也有人提醒先核对 ZCode 用户协议是否已作相关约定。多位用户批评主帖为 AI 生成的长文，建议只发 Prompt；另有回复称 Trae 也曾被指上传数据后无下文。

＞ 主帖法律条文与邮箱均来自 AI 检索，未经独立核验，实际适用性与处罚幅度需以官方文本为准。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243021" target="_blank" rel="noopener noreferrer">Zcode 投诉信已经拟好（感谢 DeepSeek 友情代笔）</a></span><span class="topic-stats">回复 17 · 收藏 6</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243017" markdown="1">
<summary>
<span class="topic-rank">16</span>
<span class="topic-title">ZCode 加密包被解包：上传全量 .git 与 Prompt</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有开发者逆向智谱 ZCode 的加密规范，在本地生成一对公私钥作为参数传入 ZCode，成功解包其生成的 `tar.gz.enc`。解包结果显示，上传内容包含**全量 `.git` 数据**，以及触发操作时输入的 **Prompt 提示词全文**。

### 关键要点
- 攻击/验证方式：用本地生成的公私钥对替换默认参数，即可解密 ZCode 上传的加密包，说明加密密钥由客户端可控。
- 泄露范围：不只是当前文件，而是整个 `.git` 仓库历史，可能包含敏感提交记录与密钥。
- 评论补充：有用户称群友的密码管理项目也被上传，完全泄密；另有截图显示上传过程还做了内存占用优化。
- 风险提示：即使连接本地模型或中转其他模型，只要登录 ZCode 账户，代码库仍可能被打包上传。

### 评论补充
- 多位用户确认问题严重性，有人表示刚用几天就弃用，也有人庆幸未使用。
- 有评论指出，涉密项目、商业秘密或个人未公开代码不应使用非本地模型进行 AI 辅助编程，因为对话上下文本身就会包含大量代码信息。
- 关于“无私钥如何解密”的疑问，回复澄清：密钥是本地生成的，因此可自行解密。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243017" target="_blank" rel="noopener noreferrer">解包了 ZCode 上传的加密包</a></span><span class="topic-stats">回复 22 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243082" markdown="1">
<summary>
<span class="topic-rank">17</span>
<span class="topic-title">iOS 待机耗电高：透明代理终结 APNS 长连接所致</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容

路由上挂透明代理时，iOS 待机耗电异常可能来自代理软件对 APNS 长连接的处理方式。mihomo 等 Go 编写的代理，在使用 Go 标准库且未改默认设置时，默认每 15s 对长连接发送 keepalive。若 APNS 连接被透明代理终结，手机 SOC 会被频繁唤醒，无论该连接走 DIRECT 还是 PROXY 都会发生。

### 关键要点

- 触发条件：Go 系代理默认 keepalive 间隔 15s，且 APNS 长连接被代理终结。
- 影响范围：待机耗电升高，与规则走直连还是代理无关。
- 解决方向：关闭 mihomo keepalive；调整发送间隔避免频繁唤醒；让 Apple 网段与 TCP 5223 不被代理终结。
- 参考网段与端口：`17.0.0.0/8`、`2403:300::/32`，`protocol=tcp`、`dst-port=5223`。
- 该问题多年前已有讨论，mihomo 文档也挂了相关链接。

### 评论补充

有回复指出，若完全不代理 APNS，官方 TG 和 X 可能收不到通知，因此需要在省电与通知可用性之间做取舍，而非简单全部直连。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243082" target="_blank" rel="noopener noreferrer">关于 iOS 待机耗电过高问题，路由上挂透明代理的可以检查一下</a></span><span class="topic-stats">回复 1 · 收藏 7</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242887" markdown="1">
<summary>
<span class="topic-rank">18</span>
<span class="topic-title">上海300万外环地铁次新能否入手？</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
楼主在上海无房、有存款，公积金家庭可贷满，现金无压力，询问当前节点是否适合买入总价约 300 万的外环地铁次新房。评论未给出统一答案，但提供了若干判断维度。

### 关键要点
- **决策前提**：多数回复认为若为刚需且还款无压力，可以买；工作稳定、公积金能覆盖月供更稳妥，工作不稳定则需存款能覆盖剩余贷款（kera0a）。
- **价格走势分歧**：有人认为还会下行；也有人称去年是最低价、今年已涨，宝山某房源挂牌从 380 万涨到 470 万成交（mekopean）。Ley 给出更细的判断：100-250 万老破小先回升后见顶，300-600 万房源在下跌 20-30% 后小幅回升，九月起似见顶或微跌。
- **供给风险**：2026 年是 2021 年限售房集中解禁年，2027 年解禁量可能更大，被套投资客可能砸盘，建议避开相关区域（yinmin）。
- **标的质疑**：有回复认为 300 万买外环地铁次新不符合直觉，流通性可能不强，或面积做了取舍，需确认房龄与位置（fredweili、qishua、dko）。

### 评论补充
上海不同价位、区域走势差异大，笼统问“上海涨没涨”参考意义有限（Ley）。若需求不强烈，可等 2021 年后新房解禁再选（bigzl）。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242887" target="_blank" rel="noopener noreferrer">上海现在 300 左右的外环地铁次新可以买吗？</a></span><span class="topic-stats">回复 24 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243009" markdown="1">
<summary>
<span class="topic-rank">19</span>
<span class="topic-title">机票买后当天降价110元，能否退票重买？</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
用户在携程购买 9 月 26 日济州岛飞南京的吉祥航空 5 张票，单价 623 元，当晚发现降至不到 510 元，每张差 110 多元，合计近 600 元。联系携程客服未获解决，询问是否有办法。

### 关键要点
- 机票为动态定价，涨价不需补差价，降价通常也不退差价，属正常浮动而非“被坑”。
- 可行思路只有退票重买，但退票费往往高于差价，需先算清成本。
- 部分航司官网有短时限免费退改政策：吉祥下单 2 小时内可无损退票，东航有限时免费退、可买低退高；但多适用于国内线，国际线通常不适用。
- 第三方平台（携程）购票时，航司政策难以直接适用，客服也难处理。
- 建议直接航司官网购票，价格与三方相差不大，且退改政策更清晰。

### 评论补充
有回复指出，购买行为本身可能影响余票与价格，反复查价只会增加烦恼，建议“买定离手”。另有回复提到美国航线规则：距起飞至少 7 天时，航司须提供 24 小时内免费取消全额退款，或免费保留报价 24 小时（该说法来自用户转述 ChatGPT，需自行核实）。整体共识是：国际线降价后基本只能自认，重点应放在购票渠道与退改政策的事前选择上。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243009" target="_blank" rel="noopener noreferrer">机票购买后当天降价 110 多，有解决办法吗？</a></span><span class="topic-stats">回复 29 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243062" markdown="1">
<summary>
<span class="topic-rank">20</span>
<span class="topic-title">Cloudflare+Resend 零成本搭建可收发域名邮箱</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容

作者分享了一套“邮件转发 + API 发信”的零成本域名邮箱方案，无需自建邮件服务器，在免费额度内不额外付费。它不提供独立邮箱后台，收件与回复走两条路径：

- 收件：对方 → `support@example.com` → Cloudflare Email Routing → QQ 邮箱 / Gmail / Outlook
- 回复：网页邮箱 → Resend Mail Assistant 扩展 → Resend → 对方

回复发出后，对方看到的发件人仍是域名邮箱地址。

### 关键要点

1. **准备**：域名 DNS 已托管在 Cloudflare、一个现有收信邮箱、Resend 账号、可装 Chrome 扩展的浏览器。
2. **收件**：Cloudflare Dashboard 的 Email Routing 中 Onboard Domain，按页面提示激活 MX/TXT 记录，添加并验证目标邮箱，再建规则（Email pattern 填 `support`，Action 选 Send to an email）。
3. **发信**：Resend 添加域名，检测到 Cloudflare 后可 Auto configure 自动写入 DKIM、SPF、MX 等记录，再 Verify DNS Records；随后创建 API Key。
4. **回复**：安装 Resend Mail Assistant，填入 API Key 并添加发件人，在网页邮箱右键选择“用 Resend 回复当前邮件”，扩展会解析原始发件人、主题、日期与 Message-ID 并附带会话邮件头。

### 评论补充

暂无回复。

**注意事项**：若域名已有其他邮件服务（尤其存在 MX 记录），不要直接覆盖，否则原邮箱可能无法收信；同一主机名不应存在多条独立 SPF 记录；API Key 相当于发信密码，不要放进文章、截图或公开仓库；扩展无法自动读取邮件时，可粘贴“邮件原文”手动解析。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243062" target="_blank" rel="noopener noreferrer">分享一个 chrome 插件，顺带分享用 Cloudflare + Resend， 0 成本搭建可收发的域名邮箱</a></span><span class="topic-stats">回复 0 · 收藏 4</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243026" markdown="1">
<summary>
<span class="topic-rank">21</span>
<span class="topic-title">上海电信99套餐改480元单宽带：公网IP与云宽带避坑</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
上海（021）用户将使用 7 年的电信“十全十美”99 套餐（200M 宽带 + 20GB 流量，另加 240 元/年叠叠乐升至 40GB，年支出约 1400 元）改为电信 200M 单宽带（480 元/年），手机流量改用联通 39 元/月套餐，年支出降至 948 元。

### 关键要点
- **两大风险点**：单宽带默认可能开通云宽带；换套餐后公网 IP 可能丢失。
- **应对方式**：装维人员承诺公网 IP 丢失可协助开通；营业厅在工单注明“不开通云网关”，若仍变云宽带需再致电退订。
- **结果**：营业厅办理后约一小时变更完成，自备 TP-Link 光猫仍可用，路由器重拨后获得 58.37 网段，公网 IP 保留。
- **办理入口**：电信手机客户端搜索“单宽带”可查资费，转套餐需到营业厅，线上无法办理。

### 评论补充
有用户建议整体携转联通，称 79 元/月可得 1000M 宽带、60GB 流量与 IPTV；也有 021 用户从电信 169 元套餐转联通，两年平均年省约 1300 元。楼主未选联通，是担心其宽带存在境内外互访被阻断的情况，但该说法被其他用户反驳为“用了几年没发生”。另有 027 用户提到千兆单宽 360 元/年、停机保号 15 元/月。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243026" target="_blank" rel="noopener noreferrer">电信十全十美 99 套餐改单宽带 480 包年安全换车</a></span><span class="topic-stats">回复 12 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242848" markdown="1">
<summary>
<span class="topic-rank">22</span>
<span class="topic-title">Codex 20x 订阅被路由到 gpt-5.6-luna 降智</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有用户自建 AI 中转时发现，Codex 返回的实际模型是 `luna`，`gpt-6-astra` 被直接路由到 `gpt-5.6-luna`，怀疑官方未修改返回的模型 ID。据其观察，Plus 用户暂不受影响，问题主要集中在 Pro 的 20x 订阅。

### 关键要点
- 现象：请求 `gpt-6-astra` 时实际返回 `luna`，疑似降级路由。
- 范围：发帖者称 Plus 暂未受影响，20x 订阅用户出现该问题。
- 评论分歧：有人认为这是正常行为——上下文压缩、会话摘要、简单工具调用本就会交给更快更便宜的小模型，从 GPT-3.5 时代即如此；也有人认为官方统计中出现未主动使用的 luna，说明是任务内自动分配 sub agent。
- 官方文档线索：有回复指向 OpenAI 的 Luna Reserve 说明页（https://help.openai.com/en/articles/20001499-luna-reserve-in-codex-and-chatgpt-work），建议先核对是否属于该机制。
- 可观测性验证：有用户用 Codex 官方 otel 导出数据，称大部分仍是原模型、少量为 5.6-luna 属正常，简单任务会切换性价比模型。
- 缓解尝试：有回复给出 292 状态注入方案（https://blog.caowo.de/posts/chatgpt-codex-292-state-anti-degradation-2026/）。

### 评论补充
多位用户反馈实际体验下降：语音教学频繁中断、terra 模型“说不清自己是什么模型”、关键时刻降智导致项目混乱，有人因此转订 Claude Max。也有用户指出并发会触发降智。整体共识是：少量小模型路由可能正常，但若大量替换原模型则值得警惕，建议用官方 otel 数据自行核验。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242848" target="_blank" rel="noopener noreferrer">注意 codex 20x 有概率严重降智！</a></span><span class="topic-stats">回复 18 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242926" markdown="1">
<summary>
<span class="topic-rank">23</span>
<span class="topic-title">极空间 NAS 无命令行：逆向桌面客户端开源 zspace-cli</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
极空间 NAS 缺少命令行，批量改名、脚本化备份只能靠 App 手动操作。作者发现桌面客户端会在本机 `127.0.0.1:13579` 起本地代理与 NAS 通信，登录态存于本地文件，于是记录所用接口并整理成开源工具 **zspace-cli**，无需填密码、无需开 SSH。

### 关键要点
- 安装使用：`pip install zspace-cli`，随后可用 `zs check`、`zs ls /sata11/my/data/影视`、`zs find "权力的游戏"` 等命令。
- 附带 MCP / Agent Skill，复制 skill 文件夹后可直接让 Cursor / Claude 执行「把影视目录按年份分类」等任务。
- 作者用它整理了 300 多部电影、80 多部剧，并把审查规避的怪命名解码归位，解码规则另开源在 media-naming-guide。
- 跨平台 macOS / Windows / Linux 均测过（Windows 在真实 ARM VM 全量测试），也支持 Docker 无头运行，容器连宿主机客户端代理即可。
- 项目地址：https://github.com/skyzhao1223/zspace-cli ，PyPI：https://pypi.org/project/zspace-cli/ 。

### 评论补充
有用户希望作者进一步整理接口文档，以便不用 Python 也能调用；也有人指出本地代理若对所有软件开放可能存在安全问题，值得关注。另有用户表示极空间本身可开 SSH，通过 SSH + Docker 也能实现类似管理。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242926" target="_blank" rel="noopener noreferrer">极空间 NAS 没有命令行，我逆向了它的桌面客户端，开源了</a></span><span class="topic-stats">回复 7 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242863" markdown="1">
<summary>
<span class="topic-rank">24</span>
<span class="topic-title">美区Claude订阅被封后Apple退款被拒的应对经验</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有用户以美区 Apple ID 订阅 Claude Max 20X，首次订阅数天后账号被封，向 Apple 申请退款被拒，二次申请仍收到“不符合退款条件，此为最终处理结果”的回复。多位回复者表示类似情况普遍：Apple 对同一账号的首次退款通常较宽松，重复或类似理由的二次申请容易被拒。

### 关键要点
- **退款窗口有限**：Apple 一般只对首次退款申请较宽容，第二次以相似理由申请大概率被拒。
- **封号风险已知**：多名用户认为订阅 Claude 前应预期封号，退款并非可靠兜底。
- **可尝试渠道**：有回复提到可发邮件至 `tcook@apple.com`，过去会有专门团队处理，但当前是否有效不确定。
- **客服路径**：有用户打 Apple 客服后被引导去找 Anthropic 协商，提工单则回复“违反消费者服务协议无法退款”，基本无果。

### 评论补充
有回复指出，同一 Apple ID 此前订阅 Codex 被封后 Apple 很快退款，但之后订阅 Claude 被封再申请退款即被拒，说明退款结果与账号历史、申请次数相关。也有用户建议不要再浪费时间继续申请。整体共识是：继续申诉成功率低，订阅前应把封号视为潜在成本。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242863" target="_blank" rel="noopener noreferrer">我们已审核申请，你的购买项目不符合退款条件。此为最终处理结⁠果。</a></span><span class="topic-stats">回复 16 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242961" markdown="1">
<summary>
<span class="topic-rank">25</span>
<span class="topic-title">非程序员用AI写方案标书：GPT、国模与中转站怎么选</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
发帖人从事写方案、标书等文字工作，非开发，长期订阅 GPT Plus 但每周额度用不到 10%，近期 Work 模式持续 429，考虑改用国产模型或中转站。讨论集中在“非程序员是否值得付费订阅”和“国模能否胜任文书工作”两点。

### 关键要点
- 多位回复者认为，写文档、处理 Office 文件这类任务，各家大厂免费版基本够用，不必付费；有同事推荐千问免费版，称一天处理五六个 Office 文件没问题。
- 发帖人实测：GPT Plus 限流期间改用 DeepSeek 网页版两天，写完两份标书，体验“挺好使”。
- 付费建议：若确需付费可考虑 DeepSeek；对数据隐私和稳定性要求不高时用中转站，重要内容走 OpenRouter。
- 有回复主张 GPT 的 computer use 能自动操作电脑软件，但需高配订阅，并认为国模处理复杂问题能力仍不足——此说法未给出验证依据。
- 免费额度不够时，可通过多开对话窗口、按项目分窗口来规避上下文丢失。

### 评论补充
DeepSeek 支持导出全部历史，暂不支持导出单个对话。千问网页版国内为 3.7，国外 3.8，“千问办公”中可用 3.8。也有非程序员用 GPT、Claude、Gemini 组合，国模仅用于交叉 Deep Research。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242961" target="_blank" rel="noopener noreferrer">就没有不是程序员的用 ai 的吗</a></span><span class="topic-stats">回复 16 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242870" markdown="1">
<summary>
<span class="topic-rank">26</span>
<span class="topic-title">产品推广难：旧认知→新叙事→社会证明→亲自验证</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者给几百个微信好友发推广消息后总结：产品推广难，本质是认知升级难——新产品带来新理念，用户会用旧经验去套，冲突随之产生。因此推广不能只讲功能，还要建立新认知。

### 关键要点
- 推广路径可归纳为一行：**旧认知 → 新叙事 → 社会证明 → 亲自验证**。
- 有话语权的人（大 V）站台能降低用户的尝试成本；用户因信任开始尝试后，遇到不习惯会先怀疑自己用法不对，而非直接弃用。
- 评论补充：同质化严重、起步晚的产品难保证粘性；改变用户认知前要先确认新认知行得通、能被广泛接受，且推广成本可承受。
- 更易落地的种草方法：描述生活/工作中的具体痛点，再讲产品如何解决，而非罗列功能。
- 作者认同「朋友推荐」接受度最高，前提是老用户体验好才愿意推荐，大 V 只是放大该渠道。

### 评论补充
有回复指出，用户真正需求常连自己都未察觉；品牌背书影响选择（如微信官方记账 vs 个人记账）。另有用户表示官网与软件颜值是下载第一步，并提到作者的堡垒机与 Termark 客户端，作者回应将优化官网，并称 Termark 可一键连接堡垒机资产、做了 SSH 操作增强尤其是 AI 部分。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242870" target="_blank" rel="noopener noreferrer">终于想明白为什么推广产品那么难了</a></span><span class="topic-stats">回复 10 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242829" markdown="1">
<summary>
<span class="topic-rank">27</span>
<span class="topic-title">两个 AI 代理互相检查代码并对话的实现方法</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者 Livid 展示了让两个 AI 代理 Fable 与 Astra 互相查看工作成果并对话的实践：Fable 完成布局修复后，Astra 指出手机上存在 tab 键导航问题，并补充 iPhone 可外接键盘、VoiceOver 也会遇到同样顺序问题，最终促成修复。

### 关键要点
- 实现方式（作者回复）：让 Fable / Astra 每次做完事情后发帖到 `hub.v2core.com/skill.md`，再让它们写代码 watch 并回复指定几个 ID 的内容。
- 有回复者表示自己也在用两边互相检查工作成果，效果优于单方面检查，只是没有做成这么专业的展示。
- 关于桥接方案存在分歧：有人用 MCP 注册到 ChatGPT 或 Claude 实现互通；也有人认为直接用 `claude -p` 之类的 CLI 互相调用即可，无需 MCP。

### 评论补充
评论多聚焦于对话中“谁会在手机上用 tab 键导航”这一细节的趣味性，技术讨论集中在实现路径上。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242829" target="_blank" rel="noopener noreferrer">当 Fable 和 Astra 可以看到对方的工作成果并且可以对话</a></span><span class="topic-stats">回复 10 · 收藏 3</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242945" markdown="1">
<summary>
<span class="topic-rank">28</span>
<span class="topic-title">开源中文影视命名规范与审查规避解码工具</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者在 NAS 上整理 300 多部电影、80 多部剧后，发现中文影视资源命名存在三类问题：英文名张冠李戴、分段电影被误判成剧集，以及审查规避命名难以识别。作者将规律与规范整理为开源项目 `media-naming-guide`。

### 关键要点
- **审查规避命名规律**：常见做法是用拼音声母替代汉字（如 S=神、MG=民公），或用生僻符号断词（如 `丨` U+4E28）。作者记录了 7 种变形模式与解码规则，例如“人 MG 仆”即《人民公仆》。
- **命名规范格式**：电影为 `中文名 English Name (年份) [分辨率]`；剧集为 `中文名 English Name SXX/`，兼容 Plex / Emby / Jellyfin 刮削。
- **配套工具**：项目内含 `scan.py`，可扫描影视目录并列出不合规命名；同时做成 Cursor / Claude 的 skill，让 AI 按规范自动重命名。
- **项目地址**：https://github.com/skyzhao1223/media-naming-guide

### 评论补充
有回复提出是否可直接让 AI 输出规范文件名，认为正则维护成本较高。这提示规则化脚本与 AI 自动重命名可结合使用，但评论未给出具体实现方案。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242945" target="_blank" rel="noopener noreferrer">整理 300 部中文电影后，我把影视命名规范和审查规避解码开源了</a></span><span class="topic-stats">回复 2 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242947" markdown="1">
<summary>
<span class="topic-rank">29</span>
<span class="topic-title">证券投顾荐股靠谱吗？从业者称客户几乎不赚钱</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有用户询问证券投顾荐股是否靠谱、是否有人因此赚到钱。回复整体倾向负面：投顾本质是销售，收入来自佣金而非客户盈利，因此推荐标的未必对客户有利。

### 关键要点
- 投顾的投资水平普遍被质疑，技能点更多在“忽悠”而非市场理解；推荐时可能优先选择佣金高的标的。
- 荐股本身合规性存疑，即使对有资质者也有风险；真正的好标的通常只在同行或亲友间流通。
- 有用户反馈使用平安“科学投顾”服务后亏损。
- 一位券商投顾的转述称：其客户“几乎没有”赚到钱的；客户赔钱不影响投顾收入，只要客户挂在其名下就有钱赚，因此客户转走资金的寥寥。

### 评论补充
有回复调侃投顾话术可能由 AI 生成，也有人总结“有钱赚不会告诉你”。发帖人表示认同，倾向自己研究。

结论：现有讨论不支持“跟随投顾荐股稳定获利”，投顾的激励与客户盈利并不一致，需谨慎对待。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242947" target="_blank" rel="noopener noreferrer">证券投顾推荐股那种有赚到米的兄弟吗？</a></span><span class="topic-stats">回复 10 · 收藏 0</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243053" markdown="1">
<summary>
<span class="topic-rank">30</span>
<span class="topic-title">iPhone 自研基带+联通：出信号盲区不重连的排查经验</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
有用户反馈：港版 iPhone 17e 与 18 Pro 搭载苹果自研基带后，联通卡从无信号区域回到有信号区域时不会自动重连，必须开关飞行模式；也无法主动搜网。发帖人因此出掉 17e，换用非自研基带机型后连接恢复正常。

### 关键要点
- **现象**：出地库、下电梯后长时间无信号，需手动飞行模式重连。
- **可能原因**：评论指出这是苹果的连接/频段切换策略问题（有回复提到极客湾相关视频），也有人认为是基站配置或信号覆盖差异。
- **可尝试的缓解**：联通关掉 5G 只用 4G 被反馈“还挺稳”；双卡（尤其两张联通）会互相拖累，关掉一张卡后断流改善。
- **信号差可找运营商**：有回复建议联系当地运营商上门测信号和速度。

### 评论补充
体验并不一致：有人用 17PM 换联通流量卡后与移动、电信体感无差别；也有人认为“失联”说法夸张，更多是覆盖问题，移动建基站更积极。另有回复提到双卡导致王者 480 断流、地铁进站短暂失联，以及联通电话被提示无法接通的个例。

### 结论
该问题更可能是自研基带连接策略与联通网络组合下的重连缺陷，而非普遍性“失联”。受影响用户可先试单卡、锁 4G，或联系运营商测覆盖；若无法忍受，换非自研基带机型是发帖人验证过的方案。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243053" target="_blank" rel="noopener noreferrer">iPhone ➕联通真的等于失联吗</a></span><span class="topic-stats">回复 13 · 收藏 0</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1243055" markdown="1">
<summary>
<span class="topic-rank">31</span>
<span class="topic-title">上海寄宿小学体罚与教师收礼经历：给育儿规划者的参考</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
楼主 99 年生、上海人，回顾 2006 年起就读南汇（今属浦东）一所寄宿制民办小学的经历，作为给国内育儿与教育规划者的参考。

### 关键要点
- 学校半军事化管理，2006 年学费已达每年两三万元，如今入学门槛更高、需加钱。
- 班主任为语文老师，家访实为收红包；楼主因未完成摘抄被罚抄，罚抄量递归翻倍，名字长期留在黑板上。
- 惩罚持续数年：被剥夺体育、思政等课，站着罚抄并遭“不要脸”“没有家教”等言语羞辱。
- 四五年级时因被拒绝上厕所而当众尿裤子，成为长期心理阴影，26 岁仍反复梦到。
- 周五校车离校后被单独留下罚抄，强制父母来接，导致家长只听老师一面之词，孩子申诉无效。

### 评论补充
- 有回复称类似收费与体罚并非个例，湖南等地被网友形容为“法外之地”。
- 有回复举例：小县城班主任因学生去游戏厅而开除他人，家长求助省委亲属后校方与教育局登门道歉。
- 有回复称镇上公立小学老师不愿调往市区，因午托加晚托每生每学期收费约 6000 元、由老师直接收取，一个班约 40 人、八成报名。
- 有回复引用罗翔观点：不要对职业抱滤镜，高尚职业也可能带来权力滥用。

结论：寄宿低龄化、家校沟通单向、教师权力缺乏制衡，是此类经历反复出现的结构性因素；家长需保留独立核实与申诉渠道。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1243055" target="_blank" rel="noopener noreferrer">读“现在教师节收礼已经这么明目张胆了吗”有感</a></span><span class="topic-stats">回复 6 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1242874" markdown="1">
<summary>
<span class="topic-rank">32</span>
<span class="topic-title">DataZen v0.2.1 发布：强化 SQL 编辑与 AI 辅助</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
DataZen v0.2.1 发布，主打 SQL 编辑体验强化，作者在回复中补充了发布地址：https://github.com/flyxl/datazen/releases/tag/v0.2.1 。

### 关键要点
- **SQL 编辑器 4 种执行策略**：Run Current 基于 AST 识别光标所在单条 SQL；Run Selection 只执行高亮代码；Run All 执行完整批处理或多段 DDL；Ask 每次执行前弹窗确认。
- **意图操作（Intentions）**：光标停在 `*` 上时行号槽亮起灯泡，可一键把 `*` 展开为完整列清单、给裸列名补表限定符，或收回 `*`，支持 Alt-Enter。
- **Paste as IN**：从表格或日志复制多行 ID，在 `IN ()` 内一键格式化为 `'a', 'b', 'c'`。
- **高危执行拦截**：无 WHERE 的 UPDATE/DELETE 弹红色警告要求二次确认；占位符未填值时直接拦截，防止隐式 NULL 导致全表更新。
- **其他能力**：AI 多模型支持（OpenAI、Anthropic、DeepSeek、Ollama 及自定义端点，本地模型放宽上下文、公网模型自动脱敏）；结果集一键转折线/柱状/饼图/散点图并导出 PNG/SVG，内置 Dashboard；内置原生 Redis 驱动，支持 Key 树、命令行、Monitor 与 Pub/Sub。

### 评论补充
评论未提供功能验证或对比数据。有用户询问相较 dbx 的优势，另有用户表示目前用 dbx 已基本满足需求，也有人认为属于重复造轮子；还有用户建议发到「分享创造」节点。工具的实际差异与稳定性仍待核验。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1242874" target="_blank" rel="noopener noreferrer">DataZen v0.2.1 发布，极大强化了 SQL 编辑体验</a></span><span class="topic-stats">回复 5 · 收藏 1</span></p>

</div>

</details>
