 # AI-for-System-Science
 ## 3.27
`backward`（BP算法）揭露学习本质

双层流可能是是复杂系统学习的本质

多巴胺-奖赏系统-反馈

梯度回溯，可以提取神经元的作用

## 4.3
NPLM loss: cross entropy

pytorch: `NN.embed`

negative sampling: 随机生成负样本，

负样本loss函数为：Log(P)

正样本loss函数为：-Log(P)

反向传播算法是最优控制的必然结果

## 4.10
#### 强化学习 Reinforcement Learning
强化学习自带干预和反事实

多主体博弈（强化学习问题，有整体目标函数，或整体博弈支付矩阵）

股票市场：每个投资主体都在适应，只有“做中学”才能应对多主体博弈

Ablation(剥离实验)

Dreamer V3


## 4.24
#### Casual Inference

阶梯：关联——>干预——>反事实(控制变量)

Data —— Bridge(Casual Inference) —— Model

Simpson Paradox

——>混淆变量 (Confounding Variable)是指与 自变量 和 因变量 均相关的变量

贝叶斯网络：表示条件概率

因果图：表示因果关系

![b2e974c277e6750d056cdb61baf2527 =100x100](https://github.com/user-attachments/assets/bca26c15-87e5-4648-b839-de147188d907)


![image](https://github.com/user-attachments/assets/755901d4-0197-4ba4-a379-e44580b00927)

《The Book Of Why》


## 5.15
#### graph neural networks
图——>随机初始节点，随机游走T步——>变成句子——>word2vec
范畴论：个体的定义由外部联系决定
集合论：个体的定义由内部元素决定


## 5.29
GLM
语言：文明的基础，意识的基础
但语言不是必须的，存在非语言交流模式
语言具有通用性（自指，自我改进，自我意识）
预训练->测试推理->自我意识（self-awareness）

#### 自注意力：动态、变权、有向的“图”，为了双向（即token两两互相的意思不同），每个token都需要准备Q, K, V，这样才能表达两个token间不同方向的信息

就如打坐：改变硬件连接，本性（比如害怕蜘蛛，刻意创造蜘蛛环境，变得不再害怕）
人机交互比单纯人工智能更有意义

LLM能在测试阶段学习，即 # in-context learning，上下文学习

一种 all in 的精神
