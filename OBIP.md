# OpenBook Improvement Proposal (OBIP)

OBIPs 是 OpenBook 的社区提案标准，用于讨论、制定和实现社区提案。本文档描述了 OBIP 的标准格式和提交流程。

## OBIP 格式

所有 OBIP 必须按照以下格式进行撰写：

### 标题

OBIP 标题应该清晰明确，简短精炼，不超过 80 个字符。

### 提案类型

OBIP 必须被分配到以下类型之一：

* 标准（Standard）：标准 OBIP 描述了 OpenBook 的核心协议或应用程序的规范。
* 信息（Informational）：信息 OBIP 提供了 OpenBook 社区的背景资料，或者提出了 OpenBook 社区中的一个问题的解决方案，但并不标准化任何协议。
* 实验（Experiment）：测试 OBIP 描述了 OpenBook 协议或应用程序的实验性协议规范或实现。

### 摘要

摘要是对提案的简短描述，不超过 200 个字符。

### 动机

动机描述了提案的背景和原因，清晰说明为什么需要这个 OBIP。

### 规范

规范详细说明提案的技术规范，包括必要的算法、协议和接口。对于标准类型的 OBIP，这部分应该非常详细。

### 实现

实现说明该提案是否已经被实现，如果是，请提供相关的实现信息和链接。

### 参考文献

参考文献应该包含所有被引用的文献，包括互联网标准、学术论文和其它有关技术的出版物。

## OBIP 提交流程

要提交一个新的 OBIP，请按照以下步骤进行：

1. Fork OpenBook 的 OBIP 存储库
2. 在存储库中创建一个新的分支，分支名称遵循 `obip/<simple-name>` 格式。
3. 撰写新的 OBIP
4. 使用 Pull Request 向 OpenBook 的主存储库提交 OBIP

在提交 PR 之前，请确保您的 OBIP 格式符合上述规范，并且您已经仔细阅读了社区的相关讨论，确保您的提案在社区中没有被讨论过。

如果您的 OBIP 得到了审核人员的批准，它将被合并到主存储库中，这意味着您的提案现在成为了 OpenBook 社区的一部分！

## 许可证

待定。
