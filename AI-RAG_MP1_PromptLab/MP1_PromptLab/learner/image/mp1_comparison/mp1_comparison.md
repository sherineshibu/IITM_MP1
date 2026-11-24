# MP1 Prompt Strategy Comparison

| Strategy         |   Snippets evaluated | Mean accuracy   | Parse rate   | Mean judge score   | Total cost (USD)   |   Median latency (s) |
|:-----------------|---------------------:|:----------------|:-------------|:-------------------|:-------------------|---------------------:|
| Zero-shot        |                   10 | 2.70 / 3        | 100%         | 24.50 / 25         | $0.006487          |                1.62  |
| Few-shot         |                   10 | 3.00 / 3        | 100%         | 25.00 / 25         | $0.006656          |                1.555 |
| Structured       |                   10 | 2.80 / 3        | 100%         | 25.00 / 25         | $0.006759          |                1.514 |
| Chain-of-thought |                   10 | 2.80 / 3        | 100%         | 25.00 / 25         | $0.007206          |                2.344 |
