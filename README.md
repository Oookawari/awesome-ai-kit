# Awesome AI Kit

我的 Prompt、Skill 与 AI 工作流工具箱。

这个仓库用于整理日常可复用的 AI 工具材料。自有内容会完整保存在仓库中；外部内容只提供简短说明和原始链接。

## 快速导航

### 按目标查找

#### 通用 AI 使用

- [将模糊需求优化为清晰 Prompt](prompts/prompt-optimizer/README.md)

#### 科研

- [翻译学术论文并生成中文 PDF](prompts/academic-paper-translator/README.md)
- [创建每日科研简报 Automation](prompts/daily-research-brief/README.md)

#### 内容维护

- [添加或整理新内容](skills/local/content-maintainer/SKILL.md)

### 按内容类型浏览

- [Prompt](prompts/README.md)：单次提交即可独立完成任务的指令
- [Skill](skills/README.md)：带有规则、资源或脚本的可安装能力
- [Workflow](workflows/README.md)：需要多轮交互或多个步骤完成的流程
- [AI Coding 技巧](coding-tips/README.md)：AI Coding 工具的操作与配置技巧
- [可复用模板](templates/README.md)：项目初始化和 Agent 指令模板

## 内容边界

- Prompt 必须能够在新对话中独立使用；依赖多轮上下文的任务归入 Workflow。
- 不保存案例、私人对话、个人信息、密钥或未公开的个人研究内容。
- 通用科研方法可以收录，但必须移除具体研究数据、主题和结论。
- 自有内容可以完整保存；第三方内容不复制全文，只保留说明与可靠的原始链接。

## 添加内容

可以手动按照各分类的格式添加，也可以让 Codex 使用 [`$content-maintainer`](skills/local/content-maintainer/SKILL.md) 完成分类、整理、隐私检查和索引更新。

每个内容条目使用独立目录，目录名称采用小写英文和连字符：

```text
prompts/prompt-optimizer/README.md
workflows/literature-review/README.md
coding-tips/codex-code-review/README.md
skills/local/example-skill/SKILL.md
```

## 参与维护

仓库主要由个人维护，但欢迎通过 Issue 或 Pull Request 提供建议。提交前请阅读 [贡献说明](CONTRIBUTING.md)。

## 许可证

本仓库的原创内容采用 [MIT License](LICENSE)。外部链接指向的内容仍遵循其原作者声明的许可证和使用条款。
