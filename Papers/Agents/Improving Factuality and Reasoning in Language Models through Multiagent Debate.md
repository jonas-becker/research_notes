- [Link](http://arxiv.org/abs/2305.14325)
- Authors: [[(A) Yilun Du]] [[(A) Joshua Tenenbaum]]
- Topics: [[agents]] [[factuality]]
- Venue: #arxiv
- Year: #y2023

---
### Major Contributions

- They employ multi-turn conversation between agents to debate their reasoning
	- Improves factuality in math and strategic scenarios
- Tasks: 
	- Reasoning: Arithmetic, [[(D) GSM8K]] Math, Chess Move Prediction
	- Factuality: Biographies, [[(D) MMLU]], Chess Move Validity
- Longer debates -> More than 4 rounds return result similar to 4 rounds
- More agents -> Higher math accuracy
- Different personas improve performance on [[(D) MMLU]]

---
### Secondary Contribution

- Consenus: Models almost always converge to a single answer with the right prompting
- LMs are relatively "agreeable" (possibly due to RLHF)
- For 5 or more agents they summarize the responses rather than concatenating due to context length of ChatGPT ([[(M) GPT-3.5]]). This improves performance.
- Debates work better with [[Chain-of-Thought]]

---
### Limitations/Future Work

- computationally expensive
- potentially self-improve a model by back-distilling?
- models struggle with long debate contexts

---
### Notes (Try to use backlinks)

- They take a look into the characteristics of discussion, including context length, debate rounds, and number of agents

---
### Important Figures

![[2023_agent_debate_example.png]]