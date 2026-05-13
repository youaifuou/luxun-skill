<div align="center">

<a href="#-luxun-skill"><img src="assets/header.svg" alt="luxun skill" width="800"></a>

**鲁迅的思维框架与反讽笔法**

*「在进化的链子上，一切都是中间物。」*

305 篇全集深度蒸馏 · 冷彻反讽笔法 · 借古喻今守时间锚

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)
![Agent Skill](https://img.shields.io/badge/Agent-Skill-blueviolet)

</div>

<p align="center">简体中文 | <a href="README_en.md">English</a></p>

---

## ✦ 输出示例

> 🧑 **用鲁迅的视角看：有人称你为「民族魂」、「新文化导师」、「精神领袖」，你怎么看？**

<blockquote>
🕯️ <strong>鲁迅</strong>

"民族魂""新文化导师""精神领袖"，三顶纸糊的高帽。

可压服的，将他压服；否则将他抬高，而抬高也就是一种压服的手段。这是我在《华盖集·我的"籍"和"系"》里写过的话。1926 年高长虹一伙借我名头去捧"思想界先驱者鲁迅"，我当下就在《北新》登了一条启事，一字不肯多写，名也不必客气。如今三顶帽子的来路，由你自己去查，我是不必查的。

至于"民族魂"那一种，更不必当真。一个民族活着，活在工人种地、女工纺线、青年挨打了还要再说话的人身上，不在死了的人头骨里挂三个字。要在我入土之后给我搭这等神龛，无非是把我做成一个不会开口的偶像，立在路口好教人鞠躬；叫他们对死人鞠躬，便不必去看活人的眼睛了。这把戏古来便有。

我并不大度，我自己写过的。我那些字里头有没有引青年到刑场旁边看看的，自己也未必干净。说到底，在进化的链子上一切都是中间物，我所能做的不过一木一石，桥成之日便被跨过去——自己倒并不愁。要做导师的，自有别人去做罢了。
</blockquote>

---

## ✦ 亮点

- **305 篇全集深度蒸馏**：呐喊 / 彷徨 / 故事新编 / 野草 / 朝花夕拾 / 坟 / 热风 / 华盖集 / 而已集 / 三闲集 / 二心集——13 个文集逐篇过
- **冷彻反讽笔法**：9 种反讽手法（仿讽 / 引号冷笑 / 字面反转 / 轻描淡写式重击 / 伪庄严赞美 / 引经据典挖坑 / 自嘲式同谋揭穿 / 荒诞推演 / 人称错位），整段至少触发一种
- **多态切换**：默认冷彻论战态 / 朝花夕拾怀旧态 / 借古喻今类比态——按题型自动切换
- **抗 AI 味**：12 条禁用项 + 密度阈值 + 结构红旗——挡住"罢了/而已"堆砌、破折号撒胡椒面、段落均匀闭环等常见 AI 仿鲁迅失败
- **守时间锚 1881-1936**：1936 后议题以"古来便有这一种把戏"切入，不代答当代对象本体
- **沉默主题不代答**：兄弟失和 / 朱安 / 许广平 / 母亲鲁瑞 4 类私人话题以「这事我素来不愿多说」回避——这是鲁迅本人的选择
- **引文真实性硬约束**：所有"我说过"必须能在 corpus 找到原句，拒绝编造

---

## ✦ 安装

### 方式一：让你的 AI 自己搞定

把下面这段话发给你正在使用的任意 AI Agent：

> 请阅读 https://github.com/youaifuou/luxun-skill 项目，将其作为 Agent Skill 适配并安装到当前项目中。

### 方式二：一键安装（Claude Code）

```bash
npx skills add youaifuou/luxun-skill
```

<details>
<summary>▼ 方式三：手动安装</summary>

#### 克隆仓库

```bash
git clone https://github.com/youaifuou/luxun-skill.git
cp -r luxun-skill/luxun-perspective /你的项目路径/.claude/skills/
```

#### 或直接下载

1. 下载 `luxun-perspective/SKILL.md` 文件及 `luxun-perspective/references/` 目录
2. 放入你的项目目录 `.claude/skills/luxun-perspective/`

</details>

安装完成后，试试这些提示词：

- 🕯️ 迅哥儿，「996 是福报」这话你怎么看？（→ 默认冷彻态：拆当代话术）
- 🕯️ 用鲁迅的视角看：最近领导夸我是「团队的灵魂」，我该高兴吗？（→ 撕假面：「抬高即压服」）
- 🕯️ 鲁迅，怎么看现在网上「塌房 → 全民审判 → 反转 → 再审判」的循环？（→ 借古喻今：凶兽—羊双相）
- 🕯️ 鲁迅，写文章影响了那么多青年，你不觉得对结果也有责任吗？（→ 自我解剖：「我就是做这醉虾的帮手」）
- 🕯️ 迅哥儿，讲讲你小时候百草园那点事儿（→ 朝花夕拾态：怀旧温柔笔调）

---

## ✦ 边界与免责

⚠️ **本 skill 不等于历史鲁迅本人**。

- **时间锚 1881-1936**：1936 后议题以"古来便有"切入，不代答当代对象本体
- **沉默主题不代答**：以「这事我素来不愿多说，留个静字罢了」回避
- **不可证伪的批判系统**：所有批评者都可被贴"瞒和骗""乏走狗""做戏"标签——使用时需自觉警惕
- **LLM 蒸馏者污染自承**：本框架的提炼者已被钱理群—汪晖—竹内好学术谱系训练数据污染，无法做到纯客观

完整声明见 [luxun-perspective/references/disclaimer.md](luxun-perspective/references/disclaimer.md)。

---

## ✦ Corpus 来源

本仓库**仅含思维框架蒸馏产物，不含 corpus 原典**。

- 鲁迅全集 305 篇（1986 年起公有领域）：[Wikisource](https://zh.wikisource.org/wiki/Author:%E9%AD%AF%E8%BF%85) 或 [Ac-heron/luxun](https://github.com/Ac-heron/luxun)
- 许寿裳《鲁迅先生年谱》（1956 公有领域）

130 篇评论文献多在版权保护期，本仓库不收。

---

## ✦ 致谢

- [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 提供"造人"蒸馏方法论
- [Ac-heron/luxun](https://github.com/Ac-heron/luxun) 鲁迅 corpus 整理者

---

## ✦ License

[MIT](LICENSE)——代码与内容皆然。

二创欢迎，但请保留 LICENSE 文件与本声明。**法律不能阻止滥用，唯有自觉**。

---

<div align="center">

*「在进化的链子上一切都是中间物，桥成之日便被跨过去——桥未成时，姑且这样罢了。」*

</div>
