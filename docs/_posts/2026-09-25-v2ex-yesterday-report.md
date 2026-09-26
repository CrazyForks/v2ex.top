---
layout: report-post
title: "V2EX 每日热点回顾 · 2026-09-25"
date: 2026-09-25 08:30:00 +0800
categories: [v2ex, daily-report]
status: success
target_date: 2026-09-25
generated_at: "2026-09-26 08:31:59"
summary: "昨日主题 124 个，过滤 56 个，DeepSeek 分析 67 个，保留高价值内容 7 个。"
count_all: 124
count_excluded: 56
count_included: 68
count_high_signal: 0
count_valuable: 7
report_url: "/2026/09/25/"
data_url: "/data/2026-09-25.json"
---

# V2EX 2026-09-25 昨日新帖报告

<details class="topic-card" data-topic-id="1244762" markdown="1">
<summary>
<span class="topic-rank">1</span>
<span class="topic-title">安卓 TikTok 无网络连接：SIM 卡与时区检测及 nrfr 伪装方案</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
安卓上 TikTok 显示“无网络连接”并非代理失效，而是 TikTok 会检测 SIM 卡归属地和手机时区。即使 FlClash 全局模式、YouTube 正常，TikTok 仍可能拒绝加载。

### 关键要点
- 触发条件：TikTok 检测 SIM 卡与系统时区，非网络问题。
- 免 Root 方案：用 `shizuku` + `nrfr` 伪装国外 SIM 卡，发帖人实测成功。
- 注意 fork：原 repo 会报 `overrideConfig cannot be invoked by shell`，需用 fork `https://github.com/a5533348/Nrfr`。
- 其他思路：拔卡、Root 后装模块、改用网页版登录、使用破解版客户端。
- 有回复称 iPhone 只需开 TUN 模式即可，无需拔卡，但该说法与安卓实测结果存在分歧。

### 评论补充
多位用户确认 `shizuku` + `nrfr` 方案靠谱且非 Root 可用；也有人建议把默认拨号卡改为 eSIM。破解版下载地址被提及（`https://liteapks.com/tiktok-2.html`），但来源可信度与安全性未经验证，需自行评估风险。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244762" target="_blank" rel="noopener noreferrer">如何在安卓上浏览 TikTok？</a></span><span class="topic-stats">回复 15 · 收藏 16</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244759" markdown="1">
<summary>
<span class="topic-rank">2</span>
<span class="topic-title">Opus 5.5 与 Codex 对比：数据分析与发散任务选型经验</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者此前因封号与言论长期反对 Claude，转向 ChatGPT 近一年后重新订阅 Claude Pro，在“系统设计+数据分析”的研究项目中对比 Codex（sol、Astra）与 Opus 5.5，认为后者在评审实验设计上明显更强。

### 关键要点
- **实验设计评审**：作者在 prompt 中明确要求 Codex 评审实验结构，它仍未发现统计公式问题，反而把精力放在代码与防御性编程，加入大量多余退出机制；Opus 5.5 仅评审结果与架构就指出了该问题。
- **行为风格差异**：Opus 的实验代码更贴近人的思路，具主动性、不盲从；Codex 倾向在给定清晰指令后执行，指出问题时也偏零散、不触及核心。
- **选型建议**：探索性、发散任务交给 Claude，具体代码调整交给 OpenAI，双持更稳妥。

### 评论补充
- 多位用户认同 OpenAI 强项是指令遵循，代价是难跳出使用者框架；Claude 发散能力更强，对模糊指令完成度更高，甚至能补出未明说的需求。
- 反向体验：Claude 主观能动性过强、常自作主张，对强控制代码风格的人不友好；Gemini 指令遵循差，实际可用性低。
- 有用户称用 Claude 做半导体器件物理机制探索，一天约等于 ChatGPT 五天。
- 风险提示：封号问题仍被提及，有账号订阅过期后仍被封。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244759" target="_blank" rel="noopener noreferrer">打脸食言了， Opus 5.5 确实有其强大之处</a></span><span class="topic-stats">回复 9 · 收藏 2</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244782" markdown="1">
<summary>
<span class="topic-rank">3</span>
<span class="topic-title">开源截图工具 Kiri：支持标注、本地 OCR 与录屏</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者发布免费开源截图工具 Kiri，支持 macOS 与 Windows，功能覆盖截图标注、本地 OCR 和录屏。截图可加箭头、文字、马赛克，并直接识别文字或录成 MP4 / GIF；截图与录屏存入本地图库，可按名称、标签检索。OCR 默认本机运行，若配置远程 OCR，上传前需确认。

### 关键要点
- 平台要求：macOS 14+ 或 Windows 11 x64。
- 安装提示：macOS 包未做 Apple 公证，首次打开需在「隐私与安全性」点「仍要打开」；Windows 包无 Authenticode 签名，可能触发 SmartScreen。
- 官网与演示：https://kiri.yuxino.cn/zh/#demo ；源码：https://github.com/yuxino/kiri ；下载：https://github.com/yuxino/kiri/releases/latest 。
- 作者补充：标注保存后可重新修改，已有图片也能导入编辑；视频支持剪掉录错片段、加速等待部分、加文字箭头、打码和局部放大；OCR 历史文字可被搜索并回溯原截图。

### 评论补充
有用户质疑其相对 Windows 自带截图（Win+Shift+T）的优势，作者回应系统自带适合截完即复制，Kiri 侧重可再编辑标注、视频剪辑与 OCR 历史检索。评论肯定其采用 Rust 而非 Electron，并建议补长截图、优先优化 macOS；作者称长截图难点在滚动拼接易重复错位。另有用户希望支持 Linux（Wayland 缺好用的截图标注+OCR 工具），作者表示已有 PR 在做，后续会尝试。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244782" target="_blank" rel="noopener noreferrer">做了一个免费开源的截图工具 Kiri，支持标注、本地 OCR 和录屏</a></span><span class="topic-stats">回复 9 · 收藏 4</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244781" markdown="1">
<summary>
<span class="topic-rank">4</span>
<span class="topic-title">开源桌面计划软件 DeskPlan：拖入文件安排任务，不挡窗口</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
DeskPlan（日序）是一款 MIT 开源的桌面计划软件，支持 Windows、macOS 和 Linux，提供中英文界面。作者想解决的需求很小：计划常驻桌面、随时可见下一件事，但不遮挡正在工作的窗口，也无需注册账号。产品主页与 15 秒演示见 https://asoming.github.io/deskplan/zh-CN/#demo ，源码在 https://github.com/asoming/deskplan ，安装包见 releases/latest。

### 关键要点
- **文件即任务**：拖入文件、文件夹或 `.code-workspace` 创建任务，也可关联已有任务；只记录路径，不移动或上传原文件。
- **四档优先级**：马上做、尽快做、按计划做、先放着，颜色区分；「尽快做」距截止不超过 48 小时会自动升到「马上做」。作者强调这是四档优先级，不是重要性×紧急性双轴矩阵。
- **今天与本周**：今天挑出最重要的三件事；本周可拖动安排日期、填写预计耗时，计划日期与截止日期分开。
- **安静驻留**：背景与文字透明度独立可调，窗口位于桌面之上、普通应用之下；侧栏悬停才出现，可缩成小窗，托盘常驻不占任务栏。
- **本地优先**：无需账号、可离线使用，含子清单、重复任务、可选提醒、备份与导出；启用更新检查或下载时才连接 GitHub。

### 边界与限制
暂无云同步、团队协作或系统日历双向同步；附件备份只含路径不含文件本体。Linux 使用 X11/XWayland，窗口行为受桌面环境影响；Windows 安装包未签名，macOS 为临时签名且未公证，首次打开可能有系统提示。作者欢迎反馈窗口层级、托盘、拖入文件等问题，并附系统、桌面环境与复现步骤。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244781" target="_blank" rel="noopener noreferrer">开源了一个透明桌面计划软件 DeskPlan：拖入文件安排任务，工作时不挡窗口</a></span><span class="topic-stats">回复 0 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244682" markdown="1">
<summary>
<span class="topic-rank">5</span>
<span class="topic-title">face-rating.net：浏览器本地跑模型的面部评分工具</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
作者发布面部评分站 face-rating.net，主打**照片不上传**：模型文件随页面下载，照片与中间产物只存在浏览器内存，刷新即消失，站上无任何上传路径。免费、无注册、无付费墙。

### 关键要点
- **评分流程**：MediaPipe Face Mesh 先测 478 个关键点（468 点 + 10 个虹膜点），按眼睛位置摆正并裁剪脸部（不拉伸五官）；本地图像模型分别读裁剪图与其镜像版，两次预测取平均换算成 10 分制。
- **分数性质**：模型在人类照片评分数据上训练，输出的是学到的偏好，非普世审美标准；几何读数（对称性、间距、脸型、眼角角度等）来自关键点，**不参与评分**，两者不相乘也不相加。
- **已知局限**：正面照测不准下巴与鼻子的前后突出度，需侧脸照；同条件可复现，但换光线、表情、相机距离数字就会变；首次打开需下载模型，会等几秒。
- **刻意不做**：不发布平均分与百分位，不收集免费分数，不宣称医学/皮肤科/心理判断，不鼓励跨工具比分数；黄金比例争议处引了四篇论文（含 2024 年质疑文）。
- 附带六项单项工具（Golden Ratio、Face Shape、Canthal Tilt、Symmetry、Jawline、Recessed Chin）及一篇不对称脸 guide。

### 评论补充
有用户用同一人的三张照片实测，得 4.4、5.2、5.5 分，跨度约 1.1 分。作者回应：若三张光线、角度、表情不同，该差距属预期噪声；若条件接近仍差 1.1 分，则说明摆正裁剪与模型对光照的敏感度需修。该用户补充三张分别来自笔记本摄像头、半年前半身照、一年前证件照，条件各异，且其他比例数值差异不大。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244682" target="_blank" rel="noopener noreferrer">做了一个面部评分站 face-rating.net：模型在浏览器本地跑，照片全程不出设备，求拍砖</a></span><span class="topic-stats">回复 4 · 收藏 1</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244770" markdown="1">
<summary>
<span class="topic-rank">6</span>
<span class="topic-title">湖北电信收紧家宽IPv6：随机丢包，运维建议关闭</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
湖北电信用户反馈家宽 IPv6 出现随机丢包阻断：白天部分时段代理节点大面积超时，访问 GPT 成功率约 50%，后连国内智谱 API 端点也大面积阻断，Ping 该端点丢包率达 75%。对照测试显示 IPv4 零丢包、IPv6 明显丢包。

### 关键要点
- 运维电话明确表示这是**预期行为**：省公司近期进一步收紧家宽 IPv6，家庭宽带套餐不承诺支持 IPv6。
- 官方给出的两个方案：在路由器中关闭 IPv6；或反复重启光猫和路由器重新拨号，尝试 roll 到较好的网段。
- 该用户宽带标称 1000M，晚高峰实测仅约 200M，上传约 35M，与 PCDN 治理背景相关。
- 排查方法：先对比 IPv4/IPv6 的 DNS 与目标端点丢包，可快速区分是线路问题还是机场问题。

### 评论补充
- 有同城湖北电信用户测试正常，说明问题可能与网段/区域有关，并非全省统一。
- 广东电信、浙江移动用户反馈 IPv6 出省曾被 reset，数月后恢复；河南联通用户称 IPv6 与 IPv4 共用老式 QoS 队列，IPv6 流量超阈值后 IPv4 变卡，最终只能关闭 IPv6。
- 有用户因运营商不再下发 IPv6 而转投联通；也有观点认为出站走 IPv4、IPv6 仅用于入站更稳妥。
- 有回复提示下行测速长期破不了 500Mbps 可能被限速，可参考站内帖 t/1146366。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244770" target="_blank" rel="noopener noreferrer">湖北电信， ipv6 随机丢包阻断，运维告知让直接关闭 ipv6</a></span><span class="topic-stats">回复 12 · 收藏 0</span></p>

</div>

</details>

<details class="topic-card" data-topic-id="1244689" markdown="1">
<summary>
<span class="topic-rank">7</span>
<span class="topic-title">Claude 封号现状：多用户实测与风控经验</span>
</summary>

<div class="topic-content" markdown="1">

<div class="topic-article" markdown="1">

### 核心内容
主帖询问 Claude 封号是否仍严重：此前 Gmail 联登每次强制绑手机号，上周突然可直接使用，怀疑是否钓鱼执法。评论呈现明显分歧——多数人近期未封号，但仍有真实封号案例，且封号后可能拒绝退款。

### 关键要点
- **未封号方**：有用户用 iOS 美区礼品卡订阅 Pro 一周后升级 5X Max，走机场节点加官方桌面客户端，未触发风控；另有用户 7 月至今注册 4 个账号、充值 2 个 Pro 和 1 个 Max 均正常。
- **付费方式**：Google Play 付费 Pro 使用 4 个月未封，配合 sub2api 反代、多设备多 IP 切换、CN 域名邮箱均正常。
- **风控变量**：有用户挂日本节点未封，认为与出国稳定使用两个月有关，出国前切换节点无效；也有用户用新加坡机房自建节点且免手机验证。
- **封号案例**：一用户主力账号用外区苹果匿名邮箱订阅半年，因给朋友注册的账号（同邮箱、新加坡 IP）次日被封，随后主力账号也被封，客服以违反 TOS 拒绝退款，怀疑是邮箱关联导致。
- **代理工具**：CC-Switch 仅用于统计用量，反代给同事用未触发风控。

### 评论补充
关于 Google Play 付款方式，有用户追问是商店内购买还是网页版走 Google Pay，未获明确答复。整体看，封号并非普遍，但账号关联、IP 与注册方式仍是主要风险点。

</div>

<p class="topic-source"><span class="topic-source-link">原链接：<a href="https://www.v2ex.com/t/1244689" target="_blank" rel="noopener noreferrer">Claude 封号现在还严重吗</a></span><span class="topic-stats">回复 9 · 收藏 0</span></p>

</div>

</details>
