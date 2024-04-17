- [Link](https://arxiv.org/abs/2312.01823)
- Authors: [[(A) Zhangyue Yin]] [[(A) Important Author]] [[(A) Xipeng Qiu]]
- Topics: [[agents]] [[reasoning]] [[factuality]]
- Venue: #arxiv
- Year: #y2023
- Read: 2024-04-17

---
### Major Contributions

- Propose Exchange-of-Thought (EoT), a framework that enables cross-model communication during problem-solving
- They assess 4 discussion paradigms across a few tasks
	- Memory, Report, Relay, Debate
- Tasks:
	- Mathematical Reasoning: [[(D) GSM8K]] [[(D) MultiArith]] [[(D) SingleEQ]] [[(D) AddSub]] [[(D) AQuA]] [[(D) SVAMP]]
	- Commonsense Reasoning: [[(D) CommonsenseQA]] [[(D) StrategyQA]]
	- Symbolic Reasoning: [[(D) Penguins in a Table]] [[(D) Date Understanding]]

---
### Secondary Contribution

- Majority Consensus: Requires full agreement by all agents in the first 5 turns, then majority agreement is enough

---
### Limitations/Future Work

- They only assessed reasoning tasks

---
### Notes (Try to use backlinks)

- All paradigms outperformed [[Chain-of-Thought]], but the performance varied across tasks. There was no clear winner
- About 3 turns were enough to lead to a good result with all paradigms

---
### Important Figures

![[2023_exchange_of_thought_paradigms.png]]