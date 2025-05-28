# Log Classification Using a Hybrid Framework

This project implements a hybrid log classification framework that combines three distinct techniques to effectively handle a wide range of log complexities. By leveraging the strengths of each method, the system offers robust and adaptable classification for logs—ranging from simple and structured to complex and sparsely labeled.

## Classification Strategies
(1) Regular Expression (Regex)

- Targets straightforward and predictable log patterns.
- Ideal for capturing known structures using predefined rule-based matching.

(2) Sentence Transformers + Logistic Regression

- Designed for more complex log entries when ample labeled data is available.
- Extracts semantic embeddings using Sentence Transformers, then applies Logistic Regression for classification.

(3) Large Language Models (LLMs)

- Serves as a fallback for highly complex or poorly labeled data.
- Leverages the generalization power of LLMs to classify logs that traditional methods may struggle with.

## System Architecture
The hybrid architecture dynamically selects the most suitable classification strategy based on the complexity and availability of labeled data, ensuring both precision and scalability in log analysis.

![image](https://github.com/user-attachments/assets/6bc60588-a6d9-48b7-ab84-ca5128d5ec21)
