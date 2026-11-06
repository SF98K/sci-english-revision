# sci-english-revision

面向科研论文和综述的英文修改技能，改进语法、地道表达、简洁性、段落衔接与篇章组织，保留科学含义、数据、有效引用和证据强度。

## 安装

将本仓库完整克隆到 Codex 的技能目录：

```bash
git clone https://github.com/SF98K/sci-english-revision.git ~/.codex/skills/sci-english-revision
```

Windows PowerShell：

```powershell
git clone https://github.com/SF98K/sci-english-revision.git "$env:USERPROFILE\.codex\skills\sci-english-revision"
```

目标目录已有内容时，先检查已有版本；不要直接覆盖。安装后新建 Codex 会话。

## 使用

> 使用 $sci-english-revision 润色以下英文，保留科学含义、数据和引用，并说明关键改动。

技能入口为根目录 `SKILL.md`，配套 `references/` 和 `resources/` 必须一并保留。

## Academic Phrasebank 补充

已在原有三份科技英文写作来源基础上，整合 John Morley 的《Academic Phrasebank》2021 增强版，保留原有8个修改模块，并新增：

- [按表达目的选句](resources/phrasebank-functions.md)：背景与缺口、文献综合、方法、结果、讨论、比较、数量、定义与转承。
- [原创改写演练](resources/phrasebank-examples.md)：11个明确标注的合成例子，展示如何保留条件、数据、引用和证据强度。
- [来源和适用说明](resources/phrasebank-sources.md)：PDF版本、章节页码及需要按语境调整的写作建议。

先识别句子要表达什么，再选择自然结构；保持已支持结论的直接表述，限定只用于真正不确定的内容。增强版原PDF和完整句库不随仓库分发。

## 来源与范围

知识来源、原文定位、适用条件见技能内的概览与主题资源。仓库包含蒸馏后的指令、中文转述、短引和辅助资源，不包含原教材全文。部分原始文件标识对应构建者的文档环境；常见问题所需知识已随包提供，更深入的原文核查需要访问原始文件。

底层教材的版权归相应权利人所有；本仓库不授予底层教材的使用权。
