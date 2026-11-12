1.验证本地工程知识库（RAG 系统）的效果、构建测试集以及管理其生命周期更新，是把 AI 玩具推向工业级生产环境最关键的“最后一公里” 要怎么做呢？

2、那 Ragas、DeepEval、Inspect AI 有什么区别？
工具	主要定位	更适合评估什么
Inspect AI	通用 LLM、Agent 基准评测	模型能力、任务成功率、工具使用、复杂推理
Ragas	RAG 质量评估，也支持 Agent 指标	检索准确性、上下文召回、答案忠实度
DeepEval	LLM 应用测试、回归测试	RAG、Agent 轨迹、工具调用、多轮对话、CI 测试
GSMA Evals	行业基准测试套件	电信领域知识、推理和诊断能力

这些工具存在重叠，不能简单理解成 Inspect AI 只测模型、Ragas 只测 RAG、DeepEval 只测 Agent。实际上，三者都能覆盖部分其他领域。
Ragas+2

3.fastapi里面streamable http有什么优势吗
