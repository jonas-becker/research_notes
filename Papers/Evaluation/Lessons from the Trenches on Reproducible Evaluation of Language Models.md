- [Link](https://arxiv.org/abs/2405.14782)
- Authors: [[(A) Stella Biderman]] [[(A) Andy Zou]]
- Topics: [[evaluation]] [[survey]]
- Venue: #arxiv
- Year: #y2024
- Read: 2024-05-28

---
### Major Contributions

- They survey 3 years of experience in evaluation LMs
- Common challenges:
	- Key problem: semantically equivalent, but syntactically different references
		- Solutions: artificially restrict answer space (e.g., multiple choice)
	- Benchmark Design and Validity
		- Number is not as important as having a proxy for a real-world problem
		- Consistent results are important
	- Implementation Difficulties and (Ir)Reproducibility
	- "Minor" Implementation Details Matter
		- LMs are incredibly sensitive to precise details that may not be obvious
		- prompts, formatting, or other implementation details
	- Lack of Agreement About “Apples to Apples”
		- fair comparisons between LMs are difficult
		- instruction-tuned models may be trained to expect certain formats
		- performance comparisons should be measured by FLOPs
	- Comparisons with Prior Work are Expensive 
	- Fast-changing Progress and Conventions
		- multi-purpose use of benchmark
		- no “ground-truth” implementation from the original benchmark authors
- Best practices:
	- Always share your exact prompts and code
	- Avoid copying results from other implementations
	- Always provide model outputs
	- Perform qualitative analyses
	- Measure and Report Uncertainty

---
### Secondary Contribution

-  => Present "LM Evaluation Harness" library based on the best practices

---
### Limitations/Future Work

- 

---
### Notes (Try to use backlinks)

- 

---
### Important Figures
