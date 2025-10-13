# LLM-in-Psy
大语言模型和心理健康支持交叉领域的论文、项目和资源的精选列表。

## 2025

  * **CATCH: A Novel Data Synthesis Framework for High Therapy Fidelity and Memory-Driven Planning Chain of Thought in AI Counseling**

    > Source: EMNLP 2025 Findings [[Link]](https://arxiv.org/abs/2509.25733)
    
    旨在解决现有AI咨询研究中，一次性生成多轮对话样本导致治疗保真度低和无法捕捉每个回应背后决策原理的挑战。CATCH框架包含两个核心组成部分：渐进式对话合成（Progressive Dialogue Synthesis）策略和记忆驱动的动态规划（Memory-Driven Dynamic Planning, MDP）思维模式。

  * **MAGneT: Coordinated Multi-Agent Generation of Synthetic Multi-Turn Mental Health Counseling Sessions**
    
    > 来源：arXiv (2025.09.04) [[链接]](https://arxiv.org/abs/2509.04183)
    
    提出一个新颖的多智能体框架 MAGneT，用于生成合成的心理咨询对话。该框架将咨询师的回应生成任务分解为由多个专业化的LLM智能体（分别负责反映、提问、提供解决方案等关键心理技术）协同处理的子任务，以更好地捕捉真实咨询的结构和细微差别。

  * **DeepPsy-Agent: A Stage-Aware and Deep-Thinking Emotional Support Agent System**
    
    > 来源：arxiv  (2025.03.20) [[链接]](https://arxiv.org/abs/2503.15876) Work in Progress
    
    关注阶段感知和深度思考的情感支持智能体系统，目前可能仍在研究中。

  * **Psy-Insight: Explainable Multi-turn Bilingual Dataset for Mental Health Counseling**
    
    > 来源：arXiv (2025.03.05) [[链接]](https://arxiv.org/abs/2503.03607)
    
    收集博客、书籍等来源的非合成多轮双语咨询对话，构建了首个面向心理健康的可解释多任务双语数据集 Psy-Insight。数据集中包含 520 个英文多轮咨询会话和 431 个中文多轮咨询会话，为训练心理健康支持的大语言模型提供了丰富素材。对收集的对话进行多任务标注和对话过程解释，标注内容包括心理治疗、情感、策略、主题标签，以及轮次级推理和会话级指导等。这些标注不仅适用于标签识别任务，还能帮助大语言模型理解咨询背后的分析和逻辑，满足大语言模型的思维链和多任务学习需求。

  * **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling**
    
    > 来源：arXiv (2025.01.16) [[链接]](https://arxiv.org/abs/2501.09426)
    
    提出了一个面向认知行为疗法（CBT）的自主多智能体框架 AutoCBT。该框架利用类似Quora和壹心理的单轮咨询数据，构建了一个能在单轮咨询场景中生成高质量回复的通用智能体框架，并引入了动态路由和监督机制，以提升自动化心理咨询服务的质量。

  * **CRISP: Cognitive Restructuring of Negative Thoughts through Multi-turn Supportive Dialogues**
    
    > 来源：EMNLP 2025 Main / arXiv (2504.17238) [[链接]](https://arxiv.org/abs/2504.17238)
    
    针对认知重构（Cognitive Restructuring, CR）这一心理治疗过程，提出了一个创新的对话框架 CRDial。该框架通过精心设计的识别与重构阶段来创建多轮对话，并由此生成了一个大规模、高质量的双语对话数据集 Crisp，用于训练认知重构对话大模型 Crispers。

  * **PsyDT: Using LLMs to Construct the Digital Twin of Psychological Counselor with Personalized Counseling Style for Psychological Counseling**
    
    > 来源：ACL 2025 Main [[链接]](https://aclanthology.org/2025.acl-long.55/)
    
    提出了一个名为 PsyDT 的新框架，旨在使用LLM构建具有个性化咨询风格的心理咨询师"数字孪生"。该框架通过分析咨询师的语言风格、咨询技术以及模拟用户的"大五"人格特质，结合少量真实案例生成多轮对话数据，从而让大模型能够模拟特定咨询师的疗法和语言风格。

  * **IntentionESC: An Intention-Centered Framework for Enhancing Emotional Support in Dialogue Systems**
    
    > 来源：ACL 2025 Findings [[链接]](https://arxiv.org/abs/2506.05947)
    
    首次将研究焦点置于情感支持对话中"支持者意图"的重要性。论文提出了 IntentionESC 框架，定义了支持者的潜在意图，并设计了 ICECoT（以意图为中心的思维链）机制，使LLM能模仿人类通过分析情感状态、推断意图、选择策略的推理过程，以生成更有效的支持性回应。

-----

## 2024

  * **MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents**

    > Source: AAAI2025 / arXiv (2024.11) [[Link]](https://arxiv.org/abs/2408.12142)
    
    构建了目前规模最大的心理疾病诊断对话数据集 MDD-5k。该数据集通过神经-符号混合的多智能体框架生成，利用 1000 个真实匿名化的精神科病例，合成了 5000 条高质量、内容详实的医患诊断对话，并附有诊断结论和治疗建议等标签。这是首个带标注的中文心理障碍诊断对话数据集。人工评估显示，MDD-5k 数据集中合成的对话在很大程度上模拟了人类精神科诊断过程。

  * **Structured Dialogue System for Mental Health: An LLM Chatbot Leveraging the PM+ Guidelines**
    
    > 来源：ICSR 2024 / arXiv (2024.11) [[链接]](https://arxiv.org/abs/2411.10681)
    
    针对现有心理咨询大模型普遍忽略对话内在阶段性的问题，提出了一个基于世界卫生组织（WHO）PM+（问题管理+）指南构建的阶段感知咨询对话系统 SuDoSys。该系统通过阶段控制器、话题数据库等模块，确保对话具有更好的一致性和导向性。

  * **CACTUS: Towards Psychological Counseling Conversations using Cognitive Behavioral Theory**
    
    > 来源：EMNLP 2024 Findings [[链接]](https://aclanthology.org/2024.findings-emnlp.832/)
    
    介绍了一个基于认知行为疗法（CBT）的大规模多轮对话数据集 CACTUS。该数据集通过模拟具有不同困境、背景和态度的客户角色，以及系统运用CBT技术的咨询师角色，生成了31,577个高质量的对话，旨在解决真实咨询数据稀缺的问题。

  * **SMILE: Single-turn to Multi-turn Inclusive Language Expansion via ChatGPT for Mental Health Support**
    
    > 来源：EMNLP 2024 Findings [[链接]](https://aclanthology.org/2024.findings-emnlp.34/)
    
    提出了 SMILE 方法，通过使用 ChatGPT 将公开的单轮心理健康问答（QA）数据改写和扩展为多轮对话。该方法构建了一个包含5.6万个多轮对话的大规模数据集 SMILECHAT，旨在为模型微调提供接近真实场景的语料库。

  * **CPsyCoun: A Report-based Multi-turn Dialogue Reconstruction and Evaluation Framework for Chinese Psychological Counseling**
    
    > 来源：ACL 2024 Findings [[链接]](https://aclanthology.org/2024.findings-acl.830/)
    
    提出了一个基于中文心理咨询报告来重建多轮对话的框架 CPsyCoun。该工作不仅构建了一个高质量的对话数据集，还开发了一套包含AI自动打分的评估基准，用于对多轮心理咨询过程进行有效评估。

  * **Enhancing Psychotherapy Counseling: A Data Augmentation Pipeline Leveraging Large Language Models for Counseling Conversations**
    
    > 来源：IJCAI 2024 / arXiv (2024.06) [[链接]](https://arxiv.org/abs/2406.08718)
    
    提出了一种数据增强流水线，利用大型语言模型将单轮的心理治疗咨询对话转化为多轮互动。该方法通过"信息提取"和"多轮咨询生成"两个步骤，旨在解决多轮对话数据稀缺的问题，并生成更具真实性和实用性的训练数据。

  * **ESCoT: Towards Interpretable Emotional Support Dialogue Systems**
    
    > 来源：ACL 2024 Main [[链接]](https://aclanthology.org/2024.acl-long.723/)
    
    针对情感支持对话系统缺乏可解释性的问题，提出了一个名为 ESCoT 的生成方案。该方案模仿人类"识别情绪-理解情绪-调节情绪"的过程，通过构建带有思维链（Chain-of-Thought）的新数据集，旨在增强对话系统响应的可解释性和可靠性。

  * **EmoLLM**
    
    > 来源：(2024) [[链接]](https://github.com/SmartFlowAI/EmoLLM)

    EmoLLM 是由 SmartFlowAI 开源的一系列心理健康对话大模型。通过在大模型上进行指令微调，EmoLLM 模型具备理解用户-支持用户-帮助用户的心理辅导能力，可以为用户提供情感支持与心理健康建议。目前已开源的模型配置及数据集旨在推动该领域的发展，鼓励社区在模型能力和安全性方面持续优化。

-----

## 2023

  * **SoulChat: Improving LLMs' Empathy, Listening, and Comfort Abilities through Fine-tuning with Multi-turn Empathy Conversations**
    
    > 来源：EMNLP 2023 Findings [[链接]](https://aclanthology.org/anthology-files/pdf/findings/2023.findings-emnlp.83.pdf)
    
    一个专注于提升大模型共情能力、倾听和安慰能力的心理健康大模型。通过百万规模的中文长文本指令和多轮共情对话数据进行联合指令微调，显著增强了模型的多轮共情对话能力。

  * **MindChat**
    
    > 来源：华东理工大学 (2023) [[链接]](https://github.com/X-D-Lab/MindChat)
    
    采用了经过人工清洗的约20万条高质量多轮心理对话数据进行训练，这些数据涵盖工作、家庭、学习、生活、社交、安全等多个方面。其目的是从心理咨询、心理评估、心理诊断、心理治疗四个维度帮助人们纾解心理压力与解决心理困惑，提高心理健康水平。