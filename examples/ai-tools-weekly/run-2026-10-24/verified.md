# verified.md · run-2026-10-24

核实员：速报核实员｜核实时间：2026-10-24 20:07（Asia/Singapore）

| 工具 | 发布方 | 发布日期 | 一手信源链接 | 状态 | 说明 |
|---|---|---|---|---|---|
| DeepInfer | DeepSeek（深度求索） | 2026-10-20 17:30（Asia/Singapore，官方 X 帖时间） | [官方 X 帖](https://x.com/deepseek_ai/status/2112476496283775135)｜[GitHub 仓库](https://github.com/deepseek-ai/DeepInfer) | 属实 | 官方称 "in-house inference framework, now fully open source"，支撑 DeepSeek-V4.1-Flash，与 picks 一致。仓库在 deepseek-ai 组织下，Apache-2.0。补充：README 写明本次开源的是离线推理部分，KV cache 系统、PD 分离、DP 副本负载均衡不在发布内，所以“完全开源”是官方原话，撰稿时最好加个限定。同串还开源了 deepseek-recipe。 |
| Kimi K3.1 Pro | 月之暗面（Moonshot AI，@Kimi_Moonshot） | 2026-10-24 01:15（Asia/Singapore，官方 X 帖时间）；官方博客页面上没标日期 | [官方 X 帖](https://x.com/Kimi_Moonshot/status/2113680701770068067)｜[官方技术博客](https://kimi.ai/blog/kimi-k3-1-pro) | 属实 | 2.8T 总参 / 104B 激活 MoE、1M 上下文、多模态，这几项都与官方一致。**注意**：权重还没开放，官方写的是 "Full model weights will be released by Nov 4, 2026"。所以 picks 的“开放权重模型”要改成“承诺 11 月 4 日前开放权重”，目前只能通过 Kimi.ai、Kimi Work、Kimi Code 和 API 使用。同时发布 K3.1 Pro Highspeed。 |
| Flint | Recursive（Recursive Superintelligence, Inc.，@Recursive_SI） | 2026-10-22 00:29（Asia/Singapore，CEO Richard Socher 帖）；公司官号帖 2026-10-22 00:41（Asia/Singapore）；HF 仓库建于 2026-10-21 22:20（Asia/Singapore） | [Recursive 官方博客](https://recursive.com/updates/introducing-recursive-flint)｜[公司官号 X 帖](https://x.com/Recursive_SI/status/2112947469826896151)｜[HF 模型页](https://huggingface.co/RecursiveSI/flint) | 属实 | picks 的来源帖是 CEO 个人号，不算公司官号，所以这里补上了公司官号帖和官网。“Recursive 首个模型、快速本地编程模型、面向编程 Agent”与官方一致。官方补充：40B 总参 / 2.5B 激活 MoE（HF 卡写 39.8B），Apache 2.0 开放权重，由 Eureka Machine 自动化研究系统参与研发。官网页面没标发布日期。 |
| MiniMax M3.1 Flash | MiniMax（@MiniMax_AI） | 正式上线：2026-10-19（官方博客日期，页面没注时区）／官方发布帖 2026-10-19 19:56（Asia/Singapore）；开放权重：2026-10-23 09:06（Asia/Singapore，官方 X 帖） | [官方博客](https://www.minimax.io/blog/minimax-m31f)｜[上线帖](https://x.com/MiniMax_AI/status/2112150867868541221)｜[开放权重帖](https://x.com/MiniMax_AI/status/2113436864904610008)｜[HF 模型页](https://huggingface.co/MiniMaxAI/MiniMax-M3.1-Flash) | 属实 | Space Bunny 是 M3.1 Flash 的早期版本，主打 Agent、编程、Computer Use 和网络安全，10-23 开放权重。这些都与官方一致。补充：约 428B 总参 / 23B 激活，多模态输入，1M 上下文。许可证是 MiniMax Community License（HF 标 other），商用有署名要求和 2000 万美元年营收门槛，所以算开放权重，不算 OSI 开源。picks 的来源帖是 10-20 04:37（Asia/Singapore）的致谢帖，不是首发帖，首发帖见左列。 |
| Raon-1 mini（预览） | KRAFTON AI（@Krafton_AI） | 2026-10-21 13:06（Asia/Singapore，官方 X 帖）；HF 仓库建于 2026-10-21 08:14（Asia/Singapore） | [官方 X 帖](https://x.com/Krafton_AI/status/2112772568776339709)｜[HF 模型页](https://huggingface.co/KRAFTON/Raon-1-mini-preview)｜[官方试用页](https://raon-mini.krafton.ai/en) | 属实 | “从零训练、30B MoE、4B 激活”与官方帖一致。HF 卡给的精确数字是 28.8B 总参 / 4.3B 激活（30B-A4B 是取整后的叫法）。权重开放，Apache 2.0 许可，但 HF 仓库要先申请访问（自动批准）。这是预览版，官方说正式版和更大的模型稍后发布。 |

## 备注
- X 帖时间都由 API 返回的 UTC 时间加 8 小时换算成 Asia/Singapore。HF 仓库创建时间取自 HF 公开 API，GitHub 仓库信息取自 GitHub 公开 API。
- 5 条都属实，“一句话”需要改的地方有两处：Kimi K3.1 Pro 的权重还没开放（承诺 11-04 前）；DeepInfer 的“完全开源”只覆盖离线推理部分。
- 引用的第三方报道（TechCrunch、TechNode）只用来交叉印证，没当作一手信源。
