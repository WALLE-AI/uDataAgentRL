# uDataAgentRL
实现end2end的agent RL模型的数据合成策略
* 侧重于Agent RL中SFT中轨迹数据合成工作 可以参数最近关于特别火的Openmanus、OWL、Anus、brower-use的等项目
## 
在数据数据的合成上，可以使用如下方式
思维树（ToT），基于树的推理路径，使代理能够系统地探索分支可能性；
思维图（GoT），利用图结构有效表示复杂的推理依赖关系；
深度优先搜索决策树（DFSDT），通过深度优先搜索优化动作选择，增强长时规划；
蒙特卡洛树搜索（MCTS），概率地探索推理和决策路径，有效平衡探索和利用。
在推理数据样本上，有几种推理输出格式
ReAct，明确集成推理和行动，鼓励结构化决策；基于结果的推理，优化明确的预期结果预测，推动目标对齐

## Datasets
* [OpenManus-RL](https://huggingface.co/datasets/CharlieDreemur/OpenManus-RL)

## Community
* [OpenManus-RL](https://github.com/OpenManus/OpenManus-RL)
* [RAGEN](https://github.com/ZihanWang314/RAGEN)
* [Search-R1](https://github.com/PeterGriffinJin/Search-R1)
* [Agent-FLAN](https://huggingface.co/datasets/internlm/Agent-FLAN)
* [AgentInstruct](https://huggingface.co/datasets/THUDM/AgentInstruct)
* [Search-o1](https://github.com/sunnynexus/Search-o1.git)
* [R1-searcher](https://github.com/RUCAIBox/R1-Searcher.git)