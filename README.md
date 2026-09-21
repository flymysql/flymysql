<div align="center">

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=6366F1&center=true&vCenter=true&width=720&lines=Systems+%26+AI-Infra+Engineer+%40+Tencent;LLM+Inference+%C2%B7+KV+Cache+%C2%B7+RDMA+Zero-Copy;Distributed+Storage+%26+Query+Engines;From+AST+all+the+way+down+to+NIC+DMA+%F0%9F%9A%80" alt="typing" />
</a>

 *桃李春风一杯酒，江湖夜雨十年灯。*

[**Blog**](https://gitpull.cn) · [**RSS**](https://gitpull.cn/rss.xml) · [flyphp@outlook.com](mailto:flyphp@outlook.com)

</div>

---

### 🧑‍💻 关于我

- 🐔 **兰州小红鸡**，系统软件工程师 @ Tencent，主线 **LLM 推理基础设施 / 分布式存储**，早年做过 **图数据库（Nebula）/ 查询引擎 / 推荐系统**
- 🧊 当前在做：**KV Cache 分层存储**（去中心化 · RDMA 零拷贝 · 无中心 master）与 **Agent 远程工作区**
- ✍️ 在 [**gitpull.cn**](https://gitpull.cn) 写工程师手账（[RSS](https://gitpull.cn/rss.xml)）｜ [旧站归档](https://flymysql.github.io)

### 🌍 开源贡献

**上游代码贡献（PR 已合并）**

- 🅽 [**NebulaGraph**](https://github.com/vesoft-inc/nebula) —— 分布式图数据库内核性能优化
  - [#5762](https://github.com/vesoft-inc/nebula/pull/5762) Optimize meta session manager & remove session lock（+176/-150）
  - [#5754](https://github.com/vesoft-inc/nebula/pull/5754) Reduce write-lock blocking time when deleting space（+15/-8）

**活跃 issue / 讨论**

- ⚡ [**SGLang**](https://github.com/sgl-project/sglang) —— LLM 推理框架
  - [#31445](https://github.com/sgl-project/sglang/issues/31445) UnifiedRadixCache extra-pool prefetch 生命周期缺失导致 segfault
  - [#31296](https://github.com/sgl-project/sglang/pull/31296) Fix host_indices use-after-free segfault（修复 PR，已 review）
- 🅽 NebulaGraph：[#5767](https://github.com/vesoft-inc/nebula/issues/5767) 类型系统 · [#5750](https://github.com/vesoft-inc/nebula/issues/5750) coredump · [#5483](https://github.com/vesoft-inc/nebula/issues/5483) GO yield · [#5456](https://github.com/vesoft-inc/nebula/issues/5456) storaged 启动 · [#5347](https://github.com/vesoft-inc/nebula/issues/5347) snapshot 循环
- 🦆 [**DeepSeek Smallpond**](https://github.com/deepseek-ai/smallpond) —— 分布式数据处理
  - [#24](https://github.com/deepseek-ai/smallpond/issues/24) Ray 多机集群调度错误 · [#7](https://github.com/deepseek-ai/smallpond/issues/7) 计算节点调度机制探讨

**DSH 插件生态** —— 维护 dsh-remote / dsh-memory 等插件，并收录进多个 awesome 列表

### ✍️ 博客精选 · [gitpull.cn](https://gitpull.cn)

| 📝 文章 | 主题 |
| --- | --- |
| [用 AI 做好软件项目：上下文工程实践指南](https://gitpull.cn/post/20260615/) | AI 工程实践 |
| [PeerCache：一个去中心化的 RDMA 零拷贝 KV 缓存后端](https://gitpull.cn/post/20260601/) | AI 基础设施 |
| [大模型推理的 PD 分离：原理、动机与 Mooncake 的实现](https://gitpull.cn/post/20260529/) | LLM 推理 |
| [CPTI：手机上就能玩的恋爱人格小测验](https://gitpull.cn/post/20260514/) | 趣味开发 |

### 🌟 主要项目

**🕰️ 早期作品（2018–2019）**

- 📚 [**WeChat-applets**](https://github.com/flymysql/WeChat-applets) `2018 · v2.1` —— 微信小程序「小鸡背单词」（已迁移腾讯云开发）
- 🐍 [**Py-Compiler**](https://github.com/flymysql/Py-Compiler) `2019 · v2.0` —— 一个用 Python 写的编译器（已现代化 Python 3.10+）
- ✨ [**CET4-Mouse-click-effects**](https://github.com/flymysql/CET4-Mouse-click-effects) `2018 · v2.0` —— 点击随机弹四级单词的鼠标特效（已重构 ES Module）

**🚀 近期 · 进行中（2026）**

- 🔌 [**dsh-remote**](https://github.com/flymysql/dsh-remote) `MIT · npm dsh-remote` —— DeepSeek Harness 远程工作区助手：多机 SSH、远程文件树、SFTP 镜像同步、端口转发
- 🐍 [**PeerCache**](https://github.com/flymysql/PeerCache) `Apache-2.0` —— 适用于 SGLang HiCache 的去中心化 L3 KV Cache 后端（RDMA 零拷贝，无中心 master；单卡达 `ib_read_bw` 94%，8 卡聚合 413 GB/s）
- 📖 [**flybook**](https://github.com/flymysql/flybook) —— Node 搭建的简书风格博客框架，简约可定制
- 🧠 [**dsh-memory**](https://github.com/flymysql/dsh-memory) —— DSH 跨会话记忆库（npm: `dsh-memory-vault`）
