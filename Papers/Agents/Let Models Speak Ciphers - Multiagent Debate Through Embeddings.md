- [Link](https://arxiv.org/abs/2310.06272)
- Authors: [[(A) Chau Pham]] [[(A) Hongxia Yang]]
- Topics: [[agents]] [[reasoning]]
- Venue: #arxiv
- Year: #y2024
- Read: 2024-04-29

---
### Major Contributions

- They skip the token sampling step during agent discussion by working on the embeddings directly
	- generating the weighted average of all tokens’ embeddings in the vocabulary set, instead of yielding a single token
		- richer discourse, especially when uncertain
		- potentially this also skips some information loss
- 5 reasoning tasks:
	- [[(D) GSM8K]] [[(D) High School Math]] [[(D) Formal Logic]] [[(D) Professional Psychology]] [[(D) Arithmetic]]
- Models: [[(M) LLaMA2]] and others

---
### Secondary Contribution

- might benefit smaller LLMs for discourse
- more agents or rounds is benefitial (performance trade-off)
- The order of prior rounds responses provided matters only with agents that generate with varying temperatures
- CIPHER benefits most when combining a low-temperature agent with a high-temperature agent (and sampling the low-temperature answer as final response)
- cipher is most helpful in uncertain situations

---
### Limitations/Future Work

- Are there other more efficient ways (besides embeddings) to exchange information between agents?
- LLM agents all need the same vocabulary set and tokenizer
- No personas, i.e., more agents are similar to more debate rounds
- What about other non-reasoning tasks?

---
### Notes (Try to use backlinks)

- Natural Language Communication
	- sample next tokens from vocabulary
- 
- Communication is humanly interpretable by remapping the embeddings to natural language

---
### Important Figures

![[2024_models_speak_ciphers.png]]
![[2024_ciphers.png]]