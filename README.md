# Kimi K3.1 Pro 实测：四道前端题的提示词和作品

这是亚里那期视频《Kimi 新旗舰，真有那么强吗？》用到的四道题。我拿 Kimi K3.1 Pro 和 GPT-6 Astra、Claude Opus 5.5、DeepSeek V4.1 Flash 1017 比了一下效果。

- 视频：B 站 / YouTube 搜「亚里」
- 图文版：<https://yari.lol/kimi-k3-1-pro-review/>

四道题都是社区测评「[亿模亿样](https://gallery.arenaofbias.icu/)」上的公开题，每个文件夹里的 `提示词.txt` 和网站题面一字不差，可以直接复制去测别的模型。

| 题目 | 文件夹 | 这里有的作品 |
|---|---|---|
| 第一题：二十四节气网页动画 | [`01-solar-terms`](01-solar-terms) | Kimi K3.1 Pro、Claude Opus 5.5、DeepSeek 1017（我自己跑的） |
| 第二题：海上小岛 | [`02-island`](02-island) | Kimi K3.1 Pro、Claude Opus 5.5、DeepSeek 1017（我自己跑的） |
| 第三题：体素中国古建 | [`03-voxel-architecture`](03-voxel-architecture) | 只有提示词，作品见下面的链接 |
| 第四题：微缩铁路小镇 | [`04-railway-town`](04-railway-town) | 只有提示词，作品见下面的链接 |

## 前两题：我自己跑的

- 2026 年 10 月 25 日，三个模型都在 OpenCode 里跑；
- 提示词整段复制粘贴，思考强度开到最高（max），每题只发一次；
- 每个模型在单独的空文件夹里跑。

文件是模型交付的原样，我只改了文件名。

### 第一题：二十四节气网页动画

题面：<https://gallery.arenaofbias.icu/#/q-48c3b43eeb284f6d>

| 模型 | 作品 | 文件 | 用时 |
|---|---|---|---|
| Kimi K3.1 Pro | 《岁时》 | [`kimi-k3.1-pro.html`](01-solar-terms/kimi-k3.1-pro.html) | 17 分钟 |
| Claude Opus 5.5 | 《二十四节气》 | [`claude-opus-5.5.html`](01-solar-terms/claude-opus-5.5.html) | 16 分钟 |
| DeepSeek V4.1 Flash 1017 | 《节令》 | [`deepseek-v4.1-flash-1017.html`](01-solar-terms/deepseek-v4.1-flash-1017.html) | 23 分钟 |

### 第二题：海上小岛

题面：<https://gallery.arenaofbias.icu/#/q-f51f3f9cca233da0>

| 模型 | 作品 | 文件 | 用时 |
|---|---|---|---|
| Kimi K3.1 Pro | 《小岛晨昏》 | [`kimi-k3.1-pro.html`](02-island/kimi-k3.1-pro.html) | 24 分钟，额度用完时还没做完 |
| Claude Opus 5.5 | 《海上小屋》 | [`claude-opus-5.5.html`](02-island/claude-opus-5.5.html) | 20 分钟 |
| DeepSeek V4.1 Flash 1017 | 《孤岛小屋》 | [`deepseek-v4.1-flash-1017.html`](02-island/deepseek-v4.1-flash-1017.html) | 24 分钟 |

Kimi 用的是 OpenCode Go 套餐，K3.1 Pro 每 5 小时只给 3 美元的额度。第一题用掉 1.55 美元，第二题跑到一半额度就见底了，所以这一版是停在半路的样子：能打开，木门能开、烟囱冒烟，拉到晚上窗户亮灯，但场景元素少，小船还悬在水面上方。

### GPT-6 Astra 的前两题

这两题 GPT-6 Astra 没有在本地跑，用的是亿模亿样上同一道题的作品（Codex，Max 档，提示词一样）：

- 第一题《岁时》，wujisuan 发布：<https://gallery.arenaofbias.icu/#/q-48c3b43eeb284f6d/up-x2w4z0xf>
- 第二题《晴屿》，Miracle 发布：<https://gallery.arenaofbias.icu/#/q-f51f3f9cca233da0/up-ha1p7sf7>

## 后两题：社区作品

我的额度用完了，后两题四家的作品都来自亿模亿样，提示词和思考强度相同。作品版权归各自的发布者，这里只放链接，点进去能在线运行。

### 第三题：体素中国古建

题面：<https://gallery.arenaofbias.icu/#/chinese-architecture>

| 模型 | 作品 | 发布者 · 工具 | 链接 |
|---|---|---|---|
| Kimi K3.1 Pro | 《栖霞晚钟》 | kme7 · Kimi Code | [在线看](https://gallery.arenaofbias.icu/#/chinese-architecture/up-trz4r60s) |
| Claude Opus 5.5 | 《梵境古刹》 | 亿模亿样 · Claude Code | [在线看](https://gallery.arenaofbias.icu/#/chinese-architecture/claude-opus-5.5-max-fanjing) |
| GPT-6 Astra | 《云阙 · 九重庭》 | yizhi · Codex | [在线看](https://gallery.arenaofbias.icu/#/chinese-architecture/up-j17ojdkz) |
| DeepSeek V4.1 Flash 1017 | 《紫微云阙》 | 牛来 · DeepSeek Harness | [在线看](https://gallery.arenaofbias.icu/#/chinese-architecture/up-um53dagb) |

### 第四题：微缩铁路小镇

题面：<https://gallery.arenaofbias.icu/#/miniature-railway-town>

| 模型 | 作品 | 发布者 · 工具 | 链接 |
|---|---|---|---|
| Kimi K3.1 Pro | 《琥珀湾》 | kme7 · Kimi Code | [在线看](https://gallery.arenaofbias.icu/#/miniature-railway-town/up-ruzin7c0) |
| Claude Opus 5.5 | 《枫溪镇》 | 亿模亿样 · Claude Code | [在线看](https://gallery.arenaofbias.icu/#/miniature-railway-town/claude-opus-5.5-max-zip) |
| GPT-6 Astra | 《暮溪环线》 | tao-yu · Codex | [在线看](https://gallery.arenaofbias.icu/#/miniature-railway-town/up-9ehft9uk) |
| DeepSeek V4.1 Flash 1017 | 《松溪镇》 | wgn · DeepSeek Harness | [在线看](https://gallery.arenaofbias.icu/#/miniature-railway-town/up-3x226x6p) |

## 怎么打开

- 前两题的作品都是单个 HTML 文件，下载下来用浏览器直接打开就行。
- 第二题 Kimi 和 Opus 的作品要联网，它们会从 CDN 加载 Three.js；3D 场景第一次打开要等几秒。
- DeepSeek 第二题交付的是打包好的单文件版，Three.js 打包在里面，所以文件比较大。

## 说明

每题只跑了一次，结果有随机性，仅供参考。

## 许可证

[MIT](LICENSE)：前两题的作品文件和这份说明，随便用。四道题的提示词是亿模亿样的公开题面；GPT-6 Astra 前两题和后两题的作品在亿模亿样上，不在这个仓库里，权利归各自的发布者。
