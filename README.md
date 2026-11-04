### 黄一淳 · Yichun Huang

金融科技背景，主力 Python。做量化因子研究，也写工具类的小东西。

> 找 **量化研究 / 金融数据 / Python 工程** 方向的实习。
> （按实际投递方向改上面这一行，只留一个方向）

---

**我在意的事**

代码要能被别人跑起来。路径写死、依赖没写、README 只在自己机器上成立 —— 这类问题我在自己的
旧项目上踩过，所以现在默认加 LICENSE、写清环境要求、把已知限制摆在 README 里而不是藏着。

**项目**

**[Quant_Project](https://github.com/ZSQBFan/Quant_Project)** · Python · 2.9 万行

A 股因子研究框架，覆盖 数据 → 因子 → 合成 → 选股 → 回测 全链路。

- 装饰器注册 + 动态模块加载：新增因子/数据源/选股器/分配器不用改框架代码
- 因子流水线三层解耦：标准化（ZScore / Rank / MAD）· 合成（等权 / 动态显著性 / RollingICIR /
  RollingRegression / LightGBM）· 滚动计算
- 30+ 因子，每个都有行业中性版本
- 回测组件化：选股器 · 权重分配（最大夏普 / 最小方差 / 风险平价）· Kelly 资金管理
- `uv` 锁定依赖，README 里写了架构和**已知局限**

**[ambient-dashboard](https://github.com/ZSQBFan/ambient-dashboard)** · JavaScript / Bash + AppleScript

macOS [Übersicht](https://tracesof.net/uebersicht/) 桌面组件：大字时钟、正在播放的专辑封面、
CPU / 内存 / 磁盘 / 网络 bento 卡片。纯系统工具采集，无第三方依赖，v0.1.0。

**存档**（已停维，保留作为记录）

- [pot-app-recognize-plugin-llm-ocr](https://github.com/ZSQBFan/pot-app-recognize-plugin-llm-ocr) —
  Pot 的 LLM OCR 插件。宿主项目已于 2025 年归档。
- [Vision_for_novision_model](https://github.com/ZSQBFan/Vision_for_novision_model) —
  2025 年为纯文本模型外挂视觉输入的 Open WebUI 函数，已被原生多模态取代。

**工具**

`Python` `pandas` `numpy` `Backtrader` `LightGBM` `scikit-learn` `SQL / SQLite` `uv`
`TypeScript / React` `Git`

**联系**

- 邮箱：zsqbfan@outlook.com
- 简历：【有就放链接，没有删掉这行】
