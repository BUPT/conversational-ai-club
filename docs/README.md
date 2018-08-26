# Neural Approaches to Conversational AI

This tutorial surveys neural approaches to conversational AI that were developed in the last few years. We group conversational systems into three categories: (1) question answering agents, (2) task-oriented dialogue agents, and (3) social bots. For each category, we present a review of state-of-the-art neural approaches, draw the connection between neural approaches and traditional symbolic approaches, and discuss the progress we have made and challenges we are facing, using specific systems and models as case studies.

## Authors

- [Jianfeng Gao](https://www.microsoft.com/en-us/research/people/jfgao/)
- [Michel Galley](https://www.microsoft.com/en-us/research/people/mgalley/)
- [Lihong Li](https://ai.google/research/people/105542)

## Published In

- ACL and SIGIR tutorial
- July 5, 2018

## Links

- PDF: [Neural Approaches to Conversational AI](_media/Neural Approaches to Conversational AI.pdf)
- PPT: [Neural Approaches to Conversational AI](https://1drv.ms/p/s!AshEqwB44aR6k8wgo9s-Jk3-A8ZiaQ)
- [Microsoft Research Publication](https://www.microsoft.com/en-us/research/publication/neural-approaches-to-conversational-ai/)

# Hello Test

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

#### 符号以及定义

1. $p$: 第一个Agent生成的句子
2. $q$: 第二个Agent生成的句子
3. $p_1,q_1,p_2,q_2,...,p_i,q_i$: 一段对话，或者称之为上下文.
4. $[p_i,q_i]$: Agent所处的状态，也即Agent的前两轮对话。
5. $p_{RL}(p_{i+1}|p_i,q_i)$: 策略(policy),论文中以LSTM encoder-decoder的形式出现。
6. $r$: 每个动作（每轮对话）的奖励函数。
7. $\mathbb{S}$: 人工构建的"迟钝回复"，例如“我不知道你在说什么”。
8. $N_{\mathbb{S}}$
9. 表示$N_{\mathbb{S}}$的基数
11. $h_{p_i}$
12. 和$h_{p_{i+1}}$ : 从encoder中获取的
13. 代表Agent两轮连续对话$p_i$和$p_{i+1}$的表示。
