# research-coding-agent
relate to a codeing direction, collect thesis

# agent code
2024: CODEAGENT: Enhancing Code Generation with tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges<br>
提出codeagentbench仓库级别代码生成的基准。提出仓库级别代码生成的方法。使用4个agent策略：react, tool-planning, OpenAIFunc, Rule-based

2024: [ChatDev: Communicative Agents for Software Development](https://arxiv.org/pdf/2307.07924)<br>
提出统一的语言规范，促进多代理协同，为LLM代理之间自主解决任务

2024: [Enhancing LLM-Based Coding Tools through Native Integration of IDE-Derived Static Context](https://arxiv.org/pdf/2402.03630)
提出IDECoder，一种使用IDE本地静态上下文方法实现跨文档代码生成。

2024: [Repoformer: Selective Retrieval for Repository-Level Code Completion](https://arxiv.org/pdf/2403.10059)
RAG频繁的搜索对代码生成并没有产生任何好处或者害处，所以提出了一个选择性RAG框架避免不必要的检索。

2024: [Dataflow-Guided Retrieval Augmentation for Repository-Level Code Completion](https://arxiv.org/pdf/2405.19782)
提出数据流检索的方式补齐仓库级别代码。私有存储库解析后，通过扩展的数据流分析来建立他们的关系，行程存储上下文图。

2024: [Enhancing Repository-Level Code Generation with Integrated Contextual Information](https://arxiv.org/pdf/2406.03283)
利用静态分析器提取类型依赖关系，并将信息与检索到的代码合并作为全面的提醒。即静态类型编程的新型代码生成框架。

2024: [R2C2-Coder: Enhancing and Benchmarking Real-world Repository-level Code Completion Abilities of Code Large Language Models](https://arxiv.org/pdf/2406.01359)
通过构建候选键所持和完成提示来增强仓库级别代码补全能力

2024: [GraphCoder: Enhancing Repository-Level Code Completion via Code Context Graph-based Retrieval and Language Model](https://arxiv.org/pdf/2406.07003)
基于土建所生成过程来增强仓库级代码增强的方法

2024: [Iterative Refinement of Project-Level Code Context for Precise Code Generation with Compiler Feedback](https://arxiv.org/pdf/2403.16792)
解决生成代码api、类、数据结构错误的情况。提出CoCoGEN方法。从代码库爹迭代定位错误。

2024: [How to Understand Whole Software Repository](https://arxiv.org/pdf/2406.01422)
ASE automatic software engineering方法。
自上而下将知识库的关键信息压缩成知识图谱。给与agent提供帮助，引导agent进行总结、分析和计划。

2024: [M2rc-Eval: Massively Multilingual Repository-level Code Completion Evaluation](https://arxiv.org/pdf/2410.21157)
现有的评估LLM的代码能力局限于5种编程语言之内，没办法很好的评估。本文提出了多编程语言的评估基准，涵盖18种语言。

2024: Repository-Level Compositional Code Translation and Validation https://arxiv.org/pdf/2410.24117
提出AlphaTrans自动翻译仓库级别的代码。

2024: [Repository-level Code Translation Benchmark Targeting Rust](https://arxiv.org/pdf/2411.13990)
原来代码翻译评估基线是codetransocean，却没有考虑真实时间上下文语境的问题。这里首次提出仓库级别代码翻译极限

2024: [EVOR: Evolving Retrieval for Code Generation](https://aclanthology.org/2024.findings-emnlp.143.pdf)
提出了EVOR，一种信息pipeline。采用查询和不同知识库的同步进步，解决代码生成任务中需要外部知识的2个显示设置。

2023: [CODEGEN: AN OPEN LARGE LANGUAGE MODEL FOR CODE WITH MULTI-TURN PROGRAM SYNTHESIS](https://arxiv.org/pdf/2203.13474)
训练了一个codegen模型，研究程序综合多步骤返利，其单个程序被分解为指定子问题的多个提示。

2023: [InferFix: End-to-End Program Repair with LLMs over Retrieval-Augmented Prompts](https://arxiv.org/pdf/2303.07263)
结合通过对比学习目标预训练retriever-Transformer编码器，为了在搜索语义上等相应的修复。根据受监督的错误修复数据进行微调，并通过添加错误类型注释和从外部非参数内存检索到的语义相似的修复来增强提示。

2023: [RepoCoder: Repository-Level Code Completion Through Iterative Retrieval and Generation](https://arxiv.org/pdf/2303.12570)
对于自动完成代码，很难去理解不同文件的有用信息。通过迭代检索生成管道中合并基于相似性的检索其和预训练代码语言模型，简化了存储库级别的代码过程。

2023: [CodePlan: Repository-level Coding using LLMs and Planning](https://arxiv.org/pdf/2309.12499)
综合了一个多步骤的计划连，其中每个步骤都导致对代码位置LLM的条用，该代码位置具有整个仓库上下文语境和特定任务的指令。

2023: [RepoFusion: Training Code Models to Understand Your Repository](https://arxiv.org/pdf/2306.10998)
一个训练模型框架以合并相关库内容。

2023: [CROSSCODEEVAL: A Diverse and Multilingual Benchmark for Cross-File Code Completion](https://arxiv.org/pdf/2310.11248)
提出了CROSSCODEEVAL，多样化和多语言的代码去完成基准，深入了解跨文件上下文理解，准确完成代码。4种流行标称。提取直接有效静态分析的方法来精确定位当前文件跨文件上下文的使用。

2023:[Guiding Language Models of Code with Global Context using Monitors](https://arxiv.org/pdf/2306.10763)
LM遭受限制的全局意识和虚幻。提出了monitor-guided decoding (MGD)，其中监视器使用静态分析来指导解码。

2023: [ML-BENCH: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code](https://arxiv.org/pdf/2311.09835)
基于现实世界编程应用程序的基准开发ML-BENCH。解决LLM解释长代码和转换为精确的可执行脚本。

2023: [MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/pdf/2308.00352)
复杂的任务分解为多个子任务给多个代理进行工作。

2022: [Repository-Level Prompt Generation for Large Language Models of Code](https://arxiv.org/pdf/2206.12839)
提出repo-level prompt generator框架，学习使用提示建议生成特定示例的提示。

#Coder LLMs



# survey papers
2024: [A Survey on Large Language Models for Code Generation](https://arxiv.org/pdf/2406.00515)
2024: [If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents](https://arxiv.org/pdf/2401.00812)


# relate to papers
2023: [StarCoder: may the source be with you!](https://arxiv.org/pdf/2305.06161)

2021: [Evaluating Large Language Models Trained on Code](https://arxiv.org/pdf/2107.03374)

CodeWhisperer 
亚马逊开发的实时AI编程

# RAG
