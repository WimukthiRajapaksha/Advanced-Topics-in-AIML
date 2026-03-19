Large Language Models (LLMs) have become very popular topic in last 5-10 years just because of the ground breaking researches and products which were thought as impossible for decades. One of those studies is Reinforcement Learning with Human Feedback (RLHF). RLHF aligns reponse of LLMs with human expectations by using 3 steps, Supervised Fine-Tuning (SFT), Reward Modelling (RM) and Policy Optimization (PPO).

In this project i’ve implemented full RLHF pipeline using different open source models and datasets. The key objectives behind the project are,

• Train baseline instruction following model using SFT
• Build RM using human preference dataset
• Apply PPO to align the model accoringly
• Evaluate model helpfulness, alignment and preference improvements
• Compare performance of different open-source models and datasets


SFT is used to lean the basic instructions of the model. It learns the basic structure of language responses. Furthermore SFT is trained while minimizing cross entropy loss. But model is not yet optimized for human preferences. On the other hand, RM learns how human responses are and how human like one response over the other.

In this article i’m describing the practical understanding of the model, techniques used how the performance depends on model architecture and other factors.
