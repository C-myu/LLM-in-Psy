# LLM-in-Psy 💭

<p align="center">
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg"></a>
  <a href="https://github.com/C-myu/LLM-in-Psy/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
  <a href="https://github.com/C-myu/LLM-in-Psy/stargazers"><img src="https://img.shields.io/github/stars/C-myu/LLM-in-Psy.svg?style=social"></a>
</p>

\[ [中文](./README_zh.md) | English \]

A curated list of papers, projects, and resources at the intersection of large language models and mental health support. 

## 2025

<details>
<summary>Click to expand</summary>

  * **MAGneT: Coordinated Multi-Agent Generation of Synthetic Multi-Turn Mental Health Counseling Sessions**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: arXiv (2025.09.04) [[Link]](https://arxiv.org/abs/2509.04183)
    
    Proposes a novel multi-agent framework MAGneT for generating synthetic mental health counseling dialogues. The framework decomposes the counselor's response generation task into subtasks collaboratively handled by multiple specialized LLM agents (responsible for reflecting, questioning, providing solutions, and other key psychological techniques) to better capture the structure and nuances of real counseling sessions.

  * **DiaCBT: A Long-Periodic Dialogue Corpus Guided by Cognitive Conceptualization Diagram for CBT-based Psychological Counseling**
    
    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source：arXiv (2025.09.03) [[Link]](http://arxiv.org/abs/2509.02999)
    
    This work constructed a DiaCBT psychological counseling dialogue dataset consisting of multiple sessions was constructed. Cognitive concept maps were introduced to simulate more realistic clients, and manually annotated real CBT dialogue cases were used as few-shots to guide the model in data synthesis.

  * **CATCH: A Novel Data Synthesis Framework for High Therapy Fidelity and Memory-Driven Planning Chain of Thought in AI Counseling**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)
    ![Chain-of-Thought](https://img.shields.io/badge/Chain_of_thought-orange)

    > Source: EMNLP 2025 Findings [[Link]](https://arxiv.org/abs/2509.25733)
    
    The CATCH framework aims to address the challenges in existing AI consultation research, the low fidelity of treatment and the inability to capture the decision-making principles behind each response due to the one-time generation of multiple dialogue samples. It consists of two core components: a progressive dialogue synthesis strategy and a memory-driven dynamic planning (MDP) thinking model.

  * **CRISP: Cognitive Restructuring of Negative Thoughts through Multi-turn Supportive Dialogues**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: EMNLP 2025 Main / arXiv (2504.17238) [[Link]](https://arxiv.org/abs/2504.17238)
    
    Addresses the cognitive restructuring (CR) process in psychotherapy by proposing an innovative dialogue framework CRDial. This framework creates multi-turn dialogues through carefully designed identification and restructuring stages, and generates a large-scale, high-quality bilingual dialogue dataset Crisp for training cognitive restructuring dialogue large model Crispers.

  * **Toward Real-World Chinese Psychological Support Dialogues: CPsDD Dataset and a Co-Evolving Multi-Agent System**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Dialogue System](https://img.shields.io/badge/Dialogue_system-yellow)

    > Source: arxiv  (2025.03.20) [[Link]](https://arxiv.org/abs/2507.07509)
    
    To address the problems of scarcity of Chinese psychological counseling dialogue data and the "routinized" responses of existing large models, this work constructed a large-scale, high-quality Chinese Psychological Support Dialogue Dataset (CPSDD) by combining expert knowledge and large-scale language models, and proposed a dialogue system (CADSS) consisting of four intelligent agents (Profiler, Summarizer, Planner, Supporter) to provide more accurate and empathetic psychological support.

  * **DeepPsy-Agent: A Stage-Aware and Deep-Thinking Emotional Support Agent System**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Chain-of-Thought](https://img.shields.io/badge/Chain_of_thought-orange)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: arxiv  (2025.03.20) [[Link]](https://arxiv.org/abs/2503.15876) Work in Progress
    
    This is an emotional support agent system that focuses on stage awareness and deep thinking, and may still be under development.

  * **Psy-Insight: Explainable Multi-turn Bilingual Dataset for Mental Health Counseling**

    ![Data collection](https://img.shields.io/badge/Data_Collection-deepskyblue)
    ![Chain-of-Thought](https://img.shields.io/badge/Chain_of_thought-orange)

    > Source: arXiv (2025.03.05) [[Link]](https://arxiv.org/abs/2503.03607)
    
    This work collects non-synthetic multi-turn bilingual counseling dialogues from sources such as blogs and books, constructing the first explainable multi-task bilingual dataset Psy-Insight for mental health. The dataset contains 520 English multi-turn counseling sessions and 431 Chinese multi-turn counseling sessions, providing rich materials for training large language models for mental health support. The collected dialogues are annotated with multiple tasks and dialogue process explanations, including psychotherapy, emotions, strategies, topic tags, as well as turn-level reasoning and session-level guidance. These annotations are not only suitable for label recognition tasks but also help large language models understand the analysis and logic behind counseling, meeting the chain-of-thought and multi-task learning needs of large language models.

  * **AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling**

    ![Dialogue System](https://img.shields.io/badge/Dialogue_system-yellow)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)
    
    > Source: arXiv (2025.01.16) [[Link]](https://arxiv.org/abs/2501.09426)
    
    Proposes an autonomous multi-agent framework AutoCBT for cognitive behavioral therapy (CBT). The framework utilizes single-turn counseling data similar to Quora and壹心理 (Yixinli), building a general agent framework capable of generating high-quality responses in single-turn counseling scenarios, and introduces dynamic routing and supervision mechanisms to improve the quality of automated psychological counseling services.

  * **PsyDial: A Large-scale Long-term Conversational Dataset for Mental Health Support**
    
    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source：ACL 2025 Main [[Link]](https://aclanthology.org/2025.acl-long.1049/)
    
    This work proposed a new method called RMRR (Retrieve, Mask, Reconstruct, Refine). This method first retrieves public "chief complaint" information related to the original conversation, then completely masks the private client utterances from the real conversation. Then, using a large language model (LLM), they reconstruct the client's utterances based on the retrieved chief complaint and the counselor's conversation content. Finally, they optimized the counselor's utterances to ensure the fluency and relevance of the conversation. In this way, they created a large-scale, privacy-preserving dataset of semi-realistic conversations, called PsyDial.

  * **PsyDT: Using LLMs to Construct the Digital Twin of Psychological Counselor with Personalized Counseling Style for Psychological Counseling**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: ACL 2025 Main [[Link]](https://aclanthology.org/2025.acl-long.55/)
    
    Proposes a new framework named PsyDT aimed at using LLMs to construct a "digital twin" of psychological counselors with personalized counseling styles. The framework analyzes the counselor's language style, counseling techniques, and simulates the user's "Big Five" personality traits, combining a small number of real cases to generate multi-turn dialogue data, enabling large models to simulate specific counselors' therapies and language styles.

  * **IntentionESC: An Intention-Centered Framework for Enhancing Emotional Support in Dialogue Systems**

    ![Chain-of-Thought](https://img.shields.io/badge/Chain_of_thought-orange)
    ![Emotional Support](https://img.shields.io/badge/Emotional_Support-cornflowerblue)

    > Source: ACL 2025 Findings [[Link]](https://arxiv.org/abs/2506.05947)
    
    For the first time, focuses research attention on the importance of "supporter intentions" in emotional support dialogues. The paper proposes the IntentionESC framework, defines potential intentions of supporters, and designs the ICECoT (Intention-Centered Chain-of-Thought) mechanism, enabling LLMs to mimic humans' reasoning process of analyzing emotional states, inferring intentions, and selecting strategies to generate more effective supportive responses.

</details>

-----

## 2024

<details>
<summary>Click to expand</summary>

  * **MDD-5k: A New Diagnostic Conversation Dataset for Mental Disorders Synthesized via Neuro-Symbolic LLM Agents**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)
    ![Clinical Diagnostic](https://img.shields.io/badge/Clinical_Diagnostic-yellowgreen)

    > Source: AAAI2025 / arXiv (2024.11) [[Link]](https://arxiv.org/abs/2408.12142)
    
    MDD-5k is the largest dataset of mental illness diagnostic dialogues to date. Generated using a hybrid neural-symbolic multi-agent framework, this dataset uses 1,000 real, anonymized psychiatric cases to synthesize 5,000 high-quality, detailed doctor-patient diagnostic dialogues, complete with labels such as diagnostic conclusions and treatment recommendations. This is the first annotated dataset of mental disorder diagnostic dialogues in Chinese. Human evaluation has shown that the synthesized dialogues in MDD-5k closely mimic the human psychiatric diagnostic process, providing a valuable resource for AI research in mental illness diagnosis.

  * **Structured Dialogue System for Mental Health: An LLM Chatbot Leveraging the PM+ Guidelines**

    ![Dialogue System](https://img.shields.io/badge/Dialogue_system-yellow)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: ICSR 2024 / arXiv (2024.11) [[Link]](https://arxiv.org/abs/2411.10681)
    
    Addresses the common problem that existing psychological counseling large models generally ignore the inherent stages of dialogue by proposing a stage-aware counseling dialogue system SuDoSys based on the World Health Organization's (WHO) PM+ (Problem Management Plus) guidelines. The system ensures better consistency and directionality in dialogues through modules such as stage controllers and topic databases.

  * **Interactive Agents: Simulating Counselor-Client Psychological Counseling via Role-Playing LLM-to-LLM Interactions**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)

    > Source：arXiv (2024.08.24) [[Link]](https://arxiv.org/abs/2408.15787)
    
    This paper propose a LLM-to-LLM interaction framework, where one LLM simulates the client and the other simulates an experienced consultant. We use the GPT-4 model to simulate multiple consultation rounds between consultants and clients using zero-shot prompts to collect a dataset.

  * **PATIENT-𝜓: Using Large Language Models to Simulate Patients for Training Mental Health Professionals**

    ![Patient simulation](https://img.shields.io/badge/Patient_Simulation-red)
    
    > Source: EMNLP 2024 Main [[Link]](https://aclanthology.org/2024.emnlp-main.711/)
    
    PATIENT-𝜓 is a framework for training mental health professionals in cognitive behavioral therapy (CBT) by simulating patients using large language models (LLMs). By constructing a diverse patient cognitive model based on CBT principles and combining it with LLMs, we created PATIENT-𝜓, which can simulate the communication behaviors of real patients.

  * **CACTUS: Towards Psychological Counseling Conversations using Cognitive Behavioral Theory**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: EMNLP 2024 Findings [[Link]](https://aclanthology.org/2024.findings-emnlp.832/)
    
    Introduces a large-scale multi-turn dialogue dataset CACTUS based on cognitive behavioral therapy (CBT). The dataset generates 31,577 high-quality dialogues by simulating client roles with different dilemmas, backgrounds, and attitudes, and counselor roles employing CBT techniques, aiming to address the scarcity of real counseling data.

  * **SMILE: Single-turn to Multi-turn Inclusive Language Expansion via ChatGPT for Mental Health Support**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)

    > Source: EMNLP 2024 Findings [[Link]](https://aclanthology.org/2024.findings-emnlp.34/)
    
    Proposes the SMILE method, using ChatGPT to rewrite and expand public single-turn mental health Q&A (QA) data into multi-turn dialogues. This method constructs a large-scale dataset SMILECHAT containing 56,000 multi-turn dialogues, aiming to provide corpus close to real scenarios for model fine-tuning.

  * **NoteChat: A Dataset of Synthetic Patient-Physician Conversations Conditioned on Clinical Notes**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)

    > Source：ACL 2024 Findings [[Link]](https://aclanthology.org/2024.findings-acl.901/)
      
    Clinical documentation is a labor-intensive process currently performed primarily by physicians, leading to physician burnout. Existing language models perform poorly in generating physician-patient conversations or corresponding electronic health records (EHRs). We propose a novel framework that leverages LLMs to generate physician-patient conversations through structured role-playing and strategic prompting to improve the efficiency and consistency of conversation generation.

  * **CPsyCoun: A Report-based Multi-turn Dialogue Reconstruction and Evaluation Framework for Chinese Psychological Counseling**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)
    > Source: ACL 2024 Findings [[Link]](https://aclanthology.org/2024.findings-acl.830/)
    
    Proposes a framework CPsyCoun for reconstructing multi-turn dialogues based on Chinese psychological counseling reports. This work not only constructs a high-quality dialogue dataset but also develops an evaluation benchmark including AI automatic scoring for effectively evaluating multi-turn psychological counseling processes.

  * **PsyChat: A Client-Centric Dialogue System for Mental Health Support**

    ![Dialogue System](https://img.shields.io/badge/Dialogue_system-yellow)

    > Source: CSCWD 2024 [[Link]](https://arxiv.org/abs/2312.04262)
    
    This work propose a client-centric conversational system called PsyChat, designed to provide mental health support through online chat. PsyChat consists of five modules: client behavior recognition, consultation strategy selection, input packager, response generator, and response selection. It aims to dynamically understand user behavior and generate the most appropriate responses during real-world user interactions.

  * **Enhancing Psychotherapy Counseling: A Data Augmentation Pipeline Leveraging Large Language Models for Counseling Conversations**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Scripts Generation](https://img.shields.io/badge/Scripts_Generation-green)

    > Source: IJCAI 2024 / arXiv (2024.06) [[Link]](https://arxiv.org/abs/2406.08718)
    
    Proposes a data augmentation pipeline that uses large language models to transform single-turn psychotherapy counseling dialogues into multi-turn interactions. This method addresses the scarcity of multi-turn dialogue data through two steps: "information extraction" and "multi-turn counseling generation," generating more realistic and practical training data.

  * **ESCoT: Towards Interpretable Emotional Support Dialogue Systems**

    ![Chain-of-Thought](https://img.shields.io/badge/Chain_of_thought-orange)
    ![Emotional Support](https://img.shields.io/badge/Emotional_Support-cornflowerblue)

    > Source: ACL 2024 Main [[Link]](https://aclanthology.org/2024.acl-long.723/)
    
    Addresses the lack of interpretability in emotional support dialogue systems by proposing an ESCoT generation scheme. This scheme mimics the human process of "emotion recognition - emotion understanding - emotion regulation" by constructing a new dataset with chain-of-thought (Chain-of-Thought) to enhance the interpretability and reliability of dialogue system responses.

  * **Towards Conversational Diagnostic AI**

    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Interactive Generation](https://img.shields.io/badge/Interactive_Generation-pin)
    ![Clinical Diagnostic](https://img.shields.io/badge/Clinical_Diagnostic-yellowgreen)

    > Source：arxiv  (2024.01.11) [[Link]](https://arxiv.org/abs/2401.05654) 
    
    AMIE (Articulate Medical Intelligence Explorer) is an LLM-based AI system optimized for diagnostic conversations. AMIE leverages a self-playing simulation environment and automated feedback mechanisms to scale its learning across diverse disease conditions, specialties, and contexts. The paper also designed a framework to evaluate AMIE's performance across clinically relevant axes, including history taking, diagnostic accuracy, managerial reasoning, communication skills, and empathy.

  * **EmoLLM**
    
    ![Emotional Support](https://img.shields.io/badge/Emotional_Support-cornflowerblue)

    > Source: (2024) [[Link]](https://github.com/SmartFlowAI/EmoLLM)

    EmoLLM is a series of large-scale mental health dialogue models open-sourced by SmartFlowAI. By fine-tuning instructions on these large-scale models, EmoLLM models are equipped with the psychological counseling capabilities to understand, support, and help users, providing emotional support and mental health advice. The open-source model configurations and datasets aim to promote development in this field and encourage the community to continuously optimize model capabilities and security.

</details>
  
-----

## 2023

<details>
<summary>Click to expand</summary>

  * **SoulChat: Improving LLMs' Empathy, Listening, and Comfort Abilities through Fine-tuning with Multi-turn Empathy Conversations**

    ![Data collection](https://img.shields.io/badge/Data_Collection-deepskyblue)
    ![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-blue)
    ![Emotional Support](https://img.shields.io/badge/Emotional_Support-cornflowerblue)

    > Source: EMNLP 2023 Findings [[Link]](https://aclanthology.org/anthology-files/pdf/findings/2023.findings-emnlp.83.pdf)
    
    A mental health large model focused on enhancing the empathy, listening, and comforting abilities of large models. Through joint instruction fine-tuning with million-scale Chinese long-text instructions and multi-turn empathy dialogue data, it significantly enhances the model's multi-turn empathy dialogue capabilities.

  * **Understanding Client Reactions in Online Mental Health Counseling**

    ![Data collection](https://img.shields.io/badge/Data_Collection-deepskyblue)
    ![Specific Therapy](https://img.shields.io/badge/Specific_Therapy-purple)

    > Source: ACL 2023 Main [[Link]](https://aclanthology.org/2023.acl-long.577/)
    
    This paper develops a annotation framework specifically designed to classify and understand the client's reactions (e.g., positive or negative) to counselors' utterances. By applying this framework to a large dataset of real-world conversations——Xinling, they analyze how different client reactions influence the final counseling outcome and how counselors can adjust their strategies based on these reactions.

  * **MindChat**

    ![Data collection](https://img.shields.io/badge/Data_Collection-deepskyblue)

    > Source: East China University of Science and Technology (2023) [[Link]](https://github.com/X-D-Lab/MindChat)
    
    Trained with approximately 200,000 high-quality multi-turn psychological dialogue data manually cleaned, covering multiple aspects including work, family, study, life, social interactions, and safety. Its purpose is to help people relieve psychological stress and solve psychological confusions from four dimensions: psychological counseling, psychological assessment, psychological diagnosis, and psychological treatment, thereby improving mental health levels.

</details>
  