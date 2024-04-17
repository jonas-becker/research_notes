- [Link](https://arxiv.org/pdf/2307.05300.pdf)
- Authors: [[(A) Zhenhailong Wang]] [[(A) Heng Ji]]
- Topics: [[agents]] [[factuality]] [[reasoning]] [[prompting]]
- Venue: #arxiv
- Year: #y2023
- Read: 2024-04-17

---
### Major Contributions

- They used one LLM that gets assigned multiple personas, called Solo Performance Prompting. 
- They point out knowledge acquisition abilities, less hallucination, maintaining reasoning from [[Chain-of-Thought]].
- Tasks: 
	1) Trivia Creative Writing  
	2) Codenames Collaborative  
	3) Logic Grid Puzzle

---
### Secondary Contribution

- Dynamically allocate personas based on the input

---
### Limitations/Future Work

- 
---
### Notes (Try to use backlinks)

- They use a single instance of an LLM, applying SPP as a variant of [[Chain-of-Thought]].
- They point out that the model needs good instruction following capabilities (e.g., [[(M) GPT-4]])
	- [[(M) LLaMA2]] and [[(M) GPT-3.5]] were less capable
---
### Important Figures

![[2023_solo_performance_prompting.png]]