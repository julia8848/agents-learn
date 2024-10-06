# langchain-ai/langchain 项目进展 - 2024-10-06

## 新增功能
- 新增工具运行时，允许传递工具调用ID。
- 实现了将输入拆分为Jina API允许的长度。
- 增加了OpenAI提示缓存和推理令牌跟踪功能。
- 在o365加载器中实现了Excel解析器。
- 添加了支持针式检索器和文档加载器的功能。
- 为Cassandra Vector Store扩展了元数据相关方法。
- 在InfinityEmbeddings中添加了使用说明。

## 主要改进
- 发布了核心版本0.2.42。
- 更新了Azure数据库的PostgreSQL示例笔记本。
- 更新了OCI数据科学集成。
- 对Arxiv搜索逻辑进行了重构。
- 更新README.md以包含教程到用例的URL。

## 修复问题
- 修复了从DBMS服务器收到的通知中的警告问题。
- 修正了“PromptTemplate”文档中的多个拼写错误。
- 解决了AzureSearch在空列表的重新排名问题。
- 修复了pgvector的弃用警告格式问题。
- 修复了Playwright工具与Pydantic架构的兼容性问题。
- 修复了关于ChatAnthropic的max_tokens默认设置的问题。

此外，还进行了其他的文档更新和小幅改进，增强了整体可用性和用户体验。