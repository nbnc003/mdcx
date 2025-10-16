## 修复

* 修复 Ollama 翻译功能的限流器配置问题
* 更新默认模型为 qwen3:8b
* 修复测试脚本中的配置初始化问题

## 新增

* 添加 Ollama 本地大模型翻译支持
  - 新增 OllamaClient 类，支持 Ollama API 调用
  - 在翻译服务中添加 OLLAMA 选项
  - 扩展配置选项，支持完整的 Ollama 参数设置
  - 实现模型可用性检查和错误处理
  - 提供测试脚本和使用文档

<details>
<summary>Full Changelog</summary>

3da1d47 feat: 添加 Ollama 本地大模型翻译支持
5f0b12d chore
1b5ca4c fix: 映射演员名时不应用 all_actors 覆盖 actors 字段

</details>