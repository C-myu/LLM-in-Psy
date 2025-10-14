# LLM-in-Psy
A curated list of papers, projects, and resources at the intersection of large language models and mental health support.

[中文版本](README_zh.md)

## 2025

  * **CATCH: A Novel Data Synthesis Framework for High Therapy Fidelity and Memory-Driven Planning Chain of Thought in AI Counseling**

    > Source: EMNLP 2025 Findings [[Link]](https://arxiv.org/abs/2509.25733)
    
    The CATCH framework aims to address the challenges in existing AI consultation research, the low fidelity of treatment and the inability to capture the decision-making principles behind each response due to the one-time generation of multiple dialogue samples. It consists of two core components: a progressive dialogue synthesis strategy and a memory-driven dynamic planning (MDP) thinking model.

  * **CRISP: Cognitive Restructuring of Negative Thoughts through Multi-turn Supportive Dialogues**
    
    > Source: EMNLP 2025 Main / arXiv (2504.17238) [[Link]](https://arxiv.org/abs/2504.17238)
    
    Addresses the cognitive restructuring (CR) process in psychotherapy by proposing an innovative dialogue framework CRDial. This framework creates multi-turn dialogues through carefully designed identification and restructuring stages, and generates a large-scale, high-quality bilingual dialogue dataset Crisp for training cognitive restructuring dialogue large model Crispers.

  * **MAGneT: Coordinated Multi-Agent Generation of Synthetic Multi-Turn Mental Health Counseling Sessions**
    
    > Source: arXiv (2025.09.04) [[Link]](https://arxiv.org/abs/2509.04183)
    
    Proposes a novel multi-agent framework MAGneT for generating synthetic mental health counseling dialogues. The framework decomposes the counselor's response generation task into subtasks collaboratively handled by multiple specialized LLM agents (responsible for reflecting, questioning, providing solutions, and other key psychological techniques) to better capture the structure and nuances of real counseling sessions.

  * **DeepPsy-Agent: A Stage-Aware and Deep-Thinking Emotional Support Agent System**
    
    > Source: arxiv  (2025.03.20) [[Link]](https://arxiv.org/abs/2503.15876) Work in Progress
    
    This is an emotional support agent system that focuses on stage awareness and deep thinking, and may still be under development.

  * **Psy-Insight: Explainable Multi-turn Bilingual Dataset for Mental Health Counseling**
    
    > Source: arXiv (2025.03.05) [[Link]](https://arxiv.org/abs/2503.03607)
    
    Collects non-synthetic multi-turn bilingual counseling dialogues from sources such as blogs and books, constructing the first explainable multi-task bilingual dataset Psy-Insight for mental health. The dataset contains 520 English multi-turn counseling sessions and 431 Chinese multi-turn counseling sessions, providing rich materials for training large language models for mental health support. The collected dialogues are annotated with multiple tasks and dialogue process explanations, including psychotherapy, emotions, strategies, topic tags, as well as turn-level reasoning and session-level guidance. These annotations are not only suitable for label recognition tasks but also help large language models understand the analysis and logic behind counseling, meeting the chain-of-thought and multi-task learning needs of large language models.

  * **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling**
    
    > Source: arXiv (2025.01.16) [[Link]](https://arxiv.org/abs/2501.09426)
    
    Proposes an autonomous multi-agent framework AutoCBT for cognitive behavioral therapy (CBT). The framework utilizes single-turn counseling data similar to Quora and壹心理 (Yixinli), building a general agent framework capable of generating high-quality responses in single-turn counseling scenarios, and introduces dynamic routing and supervision mechanisms to improve the quality of automated psychological counseling services.

  * **PsyDT: Using LLMs to Construct the Digital Twin of Psychological Counselor with Personalized Counseling Style for Psychological Counseling**
    
    > Source: ACL 2025 Main [[Link]](https://aclanthology.org/2025.acl-long.55/)
    
    Proposes a new framework named PsyDT aimed at using LLMs to construct a "digital twin" of psychological counselors with personalized counseling styles. The framework analyzes the counselor's language style, counseling techniques, and simulates the user's "Big Five" personality traits, combining a small number of real cases to generate multi-turn dialogue data, enabling large models to simulate specific counselors' therapies and language styles.

  * **IntentionESC: An Intention-Centered Framework for Enhancing Emotional Support in Dialogue Systems**
    
    > Source: ACL 2025 Findings [[Link]](https://arxiv.org/abs/2506.05947)
    
    For the first time, focuses research attention on the importance of "supporter intentions" in emotional support dialogues. The paper proposes the IntentionESC framework, defines potential intentions of supporters, and designs the ICECoT (Intention-Centered Chain-of-Thought) mechanism, enabling LLMs to mimic humans' reasoning process of analyzing emotional states, inferring intentions, and selecting strategies to generate more effective supportive responses.

-----

## 2024

  * **MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents**

    > Source: AAAI2025 / arXiv (2024.11) [[Link]](https://arxiv.org/abs/2408.12142)
    
    MDD-5k is the largest dataset of mental illness diagnostic dialogues to date. Generated using a hybrid neural-symbolic multi-agent framework, this dataset uses 1,000 real, anonymized psychiatric cases to synthesize 5,000 high-quality, detailed doctor-patient diagnostic dialogues, complete with labels such as diagnostic conclusions and treatment recommendations. This is the first annotated dataset of mental disorder diagnostic dialogues in Chinese. Human evaluation has shown that the synthesized dialogues in MDD-5k closely mimic the human psychiatric diagnostic process, providing a valuable resource for AI research in mental illness diagnosis.

  * **Structured Dialogue System for Mental Health: An LLM Chatbot Leveraging the PM+ Guidelines**
    
    > Source: ICSR 2024 / arXiv (2024.11) [[Link]](https://arxiv.org/abs/2411.10681)
    
    Addresses the common problem that existing psychological counseling large models generally ignore the inherent stages of dialogue by proposing a stage-aware counseling dialogue system SuDoSys based on the World Health Organization's (WHO) PM+ (Problem Management Plus) guidelines. The system ensures better consistency and directionality in dialogues through modules such as stage controllers and topic databases.

    * **PATIENT-𝜓: Using Large Language Models to Simulate Patients for Training Mental Health Professionals**
    
    > Source: EMNLP 2024 Main [[Link]](https://aclanthology.org/2024.emnlp-main.711/)
    
    PATIENT-Ψ is a framework for training mental health professionals in cognitive behavioral therapy (CBT) by simulating patients using large language models (LLMs). By constructing a diverse patient cognitive model based on CBT principles and combining it with LLMs, we created PATIENT-Ψ, which can simulate the communication behaviors of real patients.

  * **CACTUS: Towards Psychological Counseling Conversations using Cognitive Behavioral Theory**
    
    > Source: EMNLP 2024 Findings [[Link]](https://aclanthology.org/2024.findings-emnlp.832/)
    
    Introduces a large-scale multi-turn dialogue dataset CACTUS based on cognitive behavioral therapy (CBT). The dataset generates 31,577 high-quality dialogues by simulating client roles with different dilemmas, backgrounds, and attitudes, and counselor roles employing CBT techniques, aiming to address the scarcity of real counseling data.

  * **SMILE: Single-turn to Multi-turn Inclusive Language Expansion via ChatGPT for Mental Health Support**
    
    > Source: EMNLP 2024 Findings [[Link]](https://aclanthology.org/2024.findings-emnlp.34/)
    
    Proposes the SMILE method, using ChatGPT to rewrite and expand public single-turn mental health Q&A (QA) data into multi-turn dialogues. This method constructs a large-scale dataset SMILECHAT containing 56,000 multi-turn dialogues, aiming to provide corpus close to real scenarios for model fine-tuning.

  * **NoteChat: A Dataset of Synthetic Patient-Physician Conversations Conditioned on Clinical Notes**
      
    > 来源：ACL 2024 Findings [[链接]](https://aclanthology.org/2024.findings-acl.901/)
      
    Clinical documentation is a labor-intensive process currently performed primarily by physicians, leading to physician burnout. Existing language models perform poorly in generating physician-patient conversations or corresponding electronic health records (EHRs). We propose a novel framework that leverages LLMs to generate physician-patient conversations through structured role-playing and strategic prompting to improve the efficiency and consistency of conversation generation.

  * **CPsyCoun: A Report-based Multi-turn Dialogue Reconstruction and Evaluation Framework for Chinese Psychological Counseling**
    
    > Source: ACL 2024 Findings [[Link]](https://aclanthology.org/2024.findings-acl.830/)
    
    Proposes a framework CPsyCoun for reconstructing multi-turn dialogues based on Chinese psychological counseling reports. This work not only constructs a high-quality dialogue dataset but also develops an evaluation benchmark including AI automatic scoring for effectively evaluating multi-turn psychological counseling processes.

  * **Enhancing Psychotherapy Counseling: A Data Augmentation Pipeline Leveraging Large Language Models for Counseling Conversations**
    
    > Source: IJCAI 2024 / arXiv (2024.06) [[Link]](https://arxiv.org/abs/2406.08718)
    
    Proposes a data augmentation pipeline that uses large language models to transform single-turn psychotherapy counseling dialogues into multi-turn interactions. This method addresses the scarcity of multi-turn dialogue data through two steps: "information extraction" and "multi-turn counseling generation," generating more realistic and practical training data.

  * **ESCoT: Towards Interpretable Emotional Support Dialogue Systems**
    
    > Source: ACL 2024 Main [[Link]](https://aclanthology.org/2024.acl-long.723/)
    
    Addresses the lack of interpretability in emotional support dialogue systems by proposing an ESCoT generation scheme. This scheme mimics the human process of "emotion recognition - emotion understanding - emotion regulation" by constructing a new dataset with chain-of-thought (Chain-of-Thought) to enhance the interpretability and reliability of dialogue system responses.

  * **Towards Conversational Diagnostic AI**
    
    > 来源：arxiv  (2024.01.11) [[链接]](https://arxiv.org/abs/2401.05654) 
    
    AMIE (Articulate Medical Intelligence Explorer) is an LLM-based AI system optimized for diagnostic conversations. AMIE leverages a self-playing simulation environment and automated feedback mechanisms to scale its learning across diverse disease conditions, specialties, and contexts. The paper also designed a framework to evaluate AMIE's performance across clinically relevant axes, including history taking, diagnostic accuracy, managerial reasoning, communication skills, and empathy.

  * **EmoLLM**
    
    > Source: (2024) [[Link]](https://github.com/SmartFlowAI/EmoLLM)

    EmoLLM is a series of large-scale mental health dialogue models open-sourced by SmartFlowAI. By fine-tuning instructions on these large-scale models, EmoLLM models are equipped with the psychological counseling capabilities to understand, support, and help users, providing emotional support and mental health advice. The open-source model configurations and datasets aim to promote development in this field and encourage the community to continuously optimize model capabilities and security.
  
-----

## 2023

  * **SoulChat: Improving LLMs' Empathy, Listening, and Comfort Abilities through Fine-tuning with Multi-turn Empathy Conversations**
    
    > Source: EMNLP 2023 Findings [[Link]](https://aclanthology.org/anthology-files/pdf/findings/2023.findings-emnlp.83.pdf)
    
    A mental health large model focused on enhancing the empathy, listening, and comforting abilities of large models. Through joint instruction fine-tuning with million-scale Chinese long-text instructions and multi-turn empathy dialogue data, it significantly enhances the model's multi-turn empathy dialogue capabilities.

  * **MindChat**
    
    > Source: East China University of Science and Technology (2023) [[Link]](https://github.com/X-D-Lab/MindChat)
    
    Trained with approximately 200,000 high-quality multi-turn psychological dialogue data manually cleaned, covering multiple aspects including work, family, study, life, social interactions, and safety. Its purpose is to help people relieve psychological stress and solve psychological confusions from four dimensions: psychological counseling, psychological assessment, psychological diagnosis, and psychological treatment, thereby improving mental health levels.