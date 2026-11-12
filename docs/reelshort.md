<div align="center">

# ReelShort 短剧下载 · 欧美短剧

**英文竖屏短剧，云端拉流、按集取件** —— 榜单或搜剧名 → 勾选集数 → 云端把 HLS 分片封装成 mp4 → 分集直链或整包 ZIP。

在线入口 <https://guoshi.app/reelshort>

<sub>非官方项目，与 ReelShort / Crazy Maple Studio 无任何关联，未获其授权或认可。</sub>

</div>

---

## 这是什么

ReelShort 是面向欧美市场的竖屏短剧 App（`www.reelshort.com`），题材集中在 werewolf / revenge / billionaire 这几类，
一部剧常见 50–70 集、每集 1–2 分钟，同样只提供「在 App 里一集一集看」。

站内 [ReelShort 栏目](https://guoshi.app/reelshort) 把它接进和红果、PineDrama **同一套**下载交付系统：
**找到剧、勾集数、云端下完、按集付费取件**，共用同一份余额和同一个任务队列。

**常见叫法**：reelshort downloader、reelshort download、ReelShort 短剧下载、ReelShort 欧美短剧下载、
欧美短剧下载、reelshort 下载器 —— 指的都是这一个栏目。

---

## 和 PineDrama 那条海外线的区别

| | PineDrama（`/global`） | ReelShort（`/reelshort`） |
|---|---|---|
| 受众 | TikTok 系竖屏，印尼 / 巴西为主 | 欧美向英文剧（werewolf / revenge / billionaire） |
| 分类 | 14 个题材分类 | **214 个题材标签** + 4 个分组 + 13 个榜单楼层 |
| 字幕 | 简中 / 英文 / 西语，按集现翻 | **没有字幕**（上游不给） |
| 剧集简介 | 上游不提供 | 详情页带上游真实简介 |
| 取流形态 | 直链 mp4 | **HLS（m3u8）**，云端 `-c copy` 封装成 mp4，几乎不耗 CPU |
| 单集体积 | 4–5 MB | 均值约 39 MB（1080P） |
| 计费 | 与国内共用余额与队列 | 同左 |

两条海外线的产出契约一致：同一套选集、同一份下载清单、同一种取件方式，换来源不用换操作习惯。

---

## 怎么用

| ① 进栏目 | ② 找到剧 | ③ 勾集数 | ④ 取件 |
|---|---|---|---|
| 打开 <https://guoshi.app/reelshort>，默认落在 New Release 楼层 | 按榜单楼层翻，或用 214 个题材标签筛；也可以直接搜英文剧名 | 打开剧集选具体集数，支持跨分段保留 | 提交任务后云端拉流封装；完成后按集取直链，或一次下整包 ZIP |

**搜到即入库**：搜到的剧会立刻写进库里，之后从榜单和标签也能再次找到；搜不到说明上游还没有这部剧，换英文原名或换一个关键词再试。

---

## 界面

<table>
<tr>
<td width="50%"><img src="../assets/screenshots/reelshort-list.png" alt="ReelShort 短剧下载 · 榜单楼层与题材标签" /></td>
<td width="50%"><img src="../assets/screenshots/reelshort-series.png" alt="ReelShort 剧集详情 · 选集与按集计价" /></td>
</tr>
<tr>
<td align="center"><sub>ReelShort 栏目 · 榜单楼层与 214 个题材标签</sub></td>
<td align="center"><sub>剧集详情 · 按集勾选与取件</sub></td>
</tr>
</table>

---

## 能下什么、有哪些限制

| 项 | 说明 |
|---|---|
| 画质 | 1080P 原画（上游 H264 / H265 双编码，站内统一出 mp4） |
| 集数 | 单剧常见 50–70 集；选集器一屏 100 集，跨分段保留 |
| 字幕 | **没有字幕轨**，不像 PineDrama 可以现翻 |
| 地区 | 上游对大陆出口直返 403，取流在海外出口执行；用户侧无感 |
| 会员集 | 与免费集同一套按集计费；可用性依上游授权状态，不可用时任务会明确失败、不扣费 |
| 交付 | 分集直链（附件形式下发，点开即下载）+ 24 小时内有效；整包 ZIP 按需生成 |

---

## 计费

- **一集一价，0.01 U/集**，与红果、PineDrama 全站同价。
- **取件才扣费**：任务跑完、你确认要哪几集，才发生扣费；失败不收费。
- **重复取件不重复扣费**：同一集第二次取不再扣钱（`job_id` 唯一键保证）。

---

## 免责

- 本项目为**非官方**第三方工具，与 ReelShort、Crazy Maple Studio 及其关联公司无任何关系，未获其授权、认可或赞助。
- 本文档只描述产品形态与工程实现，**不提供**任何内容获取工具、破解方法或可执行代码。
- 界面截图中出现的剧集名称、海报、人物形象，著作权归原权利方所有，仅作界面示意。
- 使用者应自行确保对下载内容拥有合法权利，并遵守所在地法律法规与平台服务条款。

---

<div align="center">
<sub>

**[在线体验 ReelShort 栏目 →](https://guoshi.app/reelshort?utm_source=github&utm_medium=docs&utm_campaign=reelshort)** ·
[回项目首页](https://github.com/parallelpan/hongguo-downloader)

</sub>
</div>
