# Paper Reading Skill
一个用于论文精读的 AI Skill，基于 S. Keshav 在《How to Read a Paper》中提出的 Three-Pass Method（三遍阅读法）设计，并针对 AI / ML 论文分析场景进行了结构化扩展。
## 简介
该 Skill 会引导 AI 按照三遍阅读法分析论文：
1. **Pass 1：快速扫读**
   通过标题、摘要、引言、章节标题和结论快速判断论文价值，并回答 5C 问题。

2. **Pass 2：主线阅读**
   分析任务定义、系统输入、系统输出、方法流程、模型结构、数据集、评价指标、baseline 和实验结果。

3. **Pass 3：深度理解与批判**
   从复现和批判性阅读角度分析方法设计动机、核心假设、创新真实性、实验充分性、局限性和改进方向。

## 方法来源
本 Skill 基于以下论文阅读方法改写和扩展：
S. Keshav, **How to Read a Paper**
https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf
原文提出了用于高效阅读研究论文的 Three-Pass Method 和 5C 检查框架。
本仓库没有重新分发原 PDF，仅提供原文链接和基于该方法的 Skill 化实现。

## 使用方式
将 `SKILL.md` 复制到你的 Skill 目录中，例如：

```bash
skills/paper-reading/SKILL.md
```

## License

本仓库中的 Skill 文件和说明文档使用 MIT License。
原始论文阅读方法版权归原作者所有，请参考原文链接。
