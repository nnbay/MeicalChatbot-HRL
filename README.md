# MedicalChatbot-HRL

This is the code of a task-oriented dialogue system for automatic diagnosis, where a hierarchical reinforcement learning are implemented as the dialogue policy. The low level RL consists of multi-agents and each agent is the specific policy in terms of a type of disease. While the high level RL is responsible for selecting one of the low level agent or the disease classifier, then the selected agent will interact with patient in this dialogue turn.

The datasets can be downloaded in http://www.sdspeople.fudan.edu.cn/zywei/data/Fudan-Medical-Dialogue2.0

The paper draft is available at https://arxiv.org/abs/2004.14254

# How to run the code

1. download the datasets and unzip this folder in src/data.
2. Using the following command to run the code.
```
cd src/dialogue_system/run
python run.py --help
```


# Cite
```
@inproceedings{wei2018task,
  title={Task-oriented Dialogue System for Automatic Diagnosis},
  author={Liu, Qianlong and Wei, Zhongyu and Peng, Baolin and Tou, Huaixiao and Chen, Ting and Huang, Xuanjing and Wong, Kam-Fai and Dai, Xiangying},
  booktitle={Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)},
  volume={2},
  pages={201--207},
  year={2018}
}
```
