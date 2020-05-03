# MedicalChatbot-HRL

This is the code of a task-oriented dialogue system for automatic diagnosis, where a hierarchical reinforcement learning are implemented as the dialogue policy. The low level RL consists of multi-agents and each agent is the specific policy in terms of a type of disease. While the high level RL is responsible for selecting one of the low level agent or the disease classifier, then the selected agent will interact with patient in this dialogue turn.

The datasets can be found in http://www.sdspeople.fudan.edu.cn/zywei/data/Fudan-Medical-Dialogue2.0

The paper draft is available at https://arxiv.org/abs/2004.14254

