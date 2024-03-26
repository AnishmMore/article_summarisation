# Article Summarization with PEGASUS and LLaMA 2

This repository is dedicated to the task of article summarization, utilizing advanced natural language processing techniques and models. We focus on fine-tuning the PEGASUS and LLaMA 2 models using the LoRA method for parameter-efficient training. The CNN/Daily Mail dataset serves as the foundation for our experiments, allowing us to explore and refine our summarization capabilities.

## Project Overview

The goal of this project is to advance the field of automatic text summarization. By fine-tuning state-of-the-art models on a well-established dataset, we aim to generate concise, relevant, and coherent summaries of articles. This endeavor is particularly focused on evaluating the performance improvements offered by the LoRA method when applied to the PEGASUS and LLaMA 2 models.

## Dataset

The CNN/Daily Mail dataset is a large collection of news articles accompanied by multi-sentence summaries. It is widely used for training and evaluating machine learning models in the domain of natural language understanding and summarization.

## Models

### PEGASUS Fine-Tuning

PEGASUS (Pre-training with Extracted Gap-sentences for Abstractive Summarization Sequence-to-sequence models) is specifically designed for the task of text summarization. We fine-tune PEGASUS on the CNN dataset to tailor its performance to news article summarization.

### LLaMA 2 Fine-Tuning with LoRA

LLaMA 2, the latest in the line of large language models, is fine-tuned using the LoRA (Low-Rank Adaptation) method. LoRA allows us to efficiently adapt LLaMA 2's parameters to our specific task without the need for extensive computational resources.

## Evaluation

We use the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) score to evaluate the performance of our fine-tuned models. ROUGE provides a set of metrics for evaluating automatic summarization and machine translation models, focusing on the overlap of n-grams between the generated summaries and the reference summaries.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- Transformers library
- Other dependencies listed in `requirements.txt`

### Installation

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.

### Training and Evaluation

Refer to the `.ipynb` file's for details on training the models and evaluating them using ROUGE scores.

## Contributing

We welcome contributions! Please feel free to submit pull requests, open issues, or suggest improvements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

- Hugging Face's Transformers for providing the models and training infrastructure.
- The authors of the CNN/Daily Mail dataset for their invaluable resource.
- The creators of the PEGASUS and LLaMA 2 models for their contributions to advancing NLP technology.
