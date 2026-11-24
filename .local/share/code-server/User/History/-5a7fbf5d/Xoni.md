Few-shot won on accuracy, averaging 3.00 / 3, with a 100% parse rate and 25.00 / 25 judge score. Zero-shot was the cheapest at $0.006487, while few-shot had the fastest median latency at 1.201 s.

It was surprising that all strategies parsed every response successfully and received perfect judge scores. Chain-of-thought was substantially slower and costlier but did not improve accuracy over zero-shot or structured prompting.

For a structured-extraction capstone domain, I would start with the structured strategy. Its explicit schema is predictable and easy to validate, making it well-suited for consistent database or API-ready output. It also performed comparably in accuracy to other strategies.

With another day, I would test clearer few-shot examples for ambiguous cases such as zero or unstated experience, add more diverse snippets, and compare this setup with a smaller or faster model. I would also repeat the judge calls to measure consistency