# QAGen: Leveraging NLP for Question-Answering with SQuAD


### Abstract

This project explores the domain of natural language comprehension and generation using question and answer pairs, leveraging deep learning models and the SQuAD dataset. Our objective is to enhance coherence, relevance, and context preservation in generated content. The findings hold significant implications for improving conversational AI systems, virtual assistants, and educational platforms, enhancing user interactions with automated systems.

### Objectives


### Methodology

We plan to utilize advanced transformer-based models like BERT, RoBERTa, or DistilBERT for our project. These models have shown impressive results in question answering tasks by effectively capturing contextual information from input text.

Our approach involves fine-tuning these pre-trained transformer models on the Squad dataset, which contains question-answer pairs extracted from Wikipedia articles. By fine-tuning on Squad, the models can learn to extract answers directly from the provided context passages.

### Evaluation

To evaluate the performance of our QA system, we'll employ a mix of qualitative and quantitative analyses:

**Qualitative Assessment:**

- _Visual Inspection_: We'll visually scrutinize the generated answers to ensure their pertinence and correctness in the context of the input questions.
- _Error Analysis_: Examining cases where the model produces incorrect or irrelevant responses will help identify potential shortcomings and areas for improvement.

**Quantitative Evaluation:**

- _Exact Match (EM) Score_: This metric will measure the percentage of questions for which the model's answer exactly matches the ground truth from the dataset, providing insights into the system's accuracy in delivering precise responses.
- Depending on the project's requirements, we may consider incorporating additional metrics such as _F1-Score, precision, recall_, and _mean average precision_ (MAP) for more nuanced evaluation.

### Dataset
https://rajpurkar.github.io/SQuAD-explorer/

### References

- https://pytorch.org/text/stable/datasets.html#squad-2-0
- https://www.kaggle.com/datasets/stanfordu/stanford-question-answering-dataset/data
- https://www.tensorflow.org/datasets/catalog/squad
- https://huggingface.co/datasets/squad
