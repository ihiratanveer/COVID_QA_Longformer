# COVID-QA: Longformer Question Answering

## Overview
COVID-QA is a powerful question answering system based on the Longformer model, designed specifically for COVID-19 related research. This repository contains the code and resources necessary to train and deploy the Longformer model for COVID-19 question answering tasks.

## Features
- Utilizes the Longformer model, which overcomes the limitations of traditional transformers in processing long sequences of text.
- Fine-tuned on the COVID-QA dataset, consisting of 2,019 question/answer pairs annotated by biomedical experts on scientific articles related to COVID-19.
- Implements a sliding window local attention mechanism to handle sequences containing thousands of tokens.
- Achieves state-of-the-art performance in COVID-19 question answering, providing accurate and contextually rich answers.

## Requirements
- Python 3.7 or higher
- Jupyter Notebook
- PyTorch
- Transformers library

## Getting Started
1. Clone this repository to your local machine.
2. Open the `covid_longformer_qa_training.ipynb` file in Jupyter Notebook.
3. All requirements installed through pip in the Jupyter notebook.
4. Follow the instructions provided in the notebook to train and evaluate the Longformer model.
5. Customize the notebook to suit your specific needs or use the pre-trained model for inference.

## Dataset
The COVID-QA dataset consists of 2,019 question/answer pairs annotated by volunteer biomedical experts on scientific articles related to COVID-19. The dataset focuses on 147 scientific articles from the CORD-19 dataset, providing a specialized resource for training the Longformer model in COVID-19 question answering.

## Results
- Achieved an F1-score of 93.15 and an Exact Match score of 86.92 on the COVID-QA dataset, surpassing previous benchmarks.
- Outperformed other transformer-based models like RoBERTa in COVID-19 question answering tasks.
- Provided accurate and contextually rich answers to COVID-19 queries, helping advance COVID-19 research and awareness.

## Blog posts explaining the mechanism and thought behind the idea:
- [Unleashing the Power of Long Sequences in NLP: Why can Longformers be used for Question Answering systems?]([url](https://ihiratanveer.medium.com/unleashing-the-power-of-long-sequences-in-nlp-why-can-longformers-be-used-for-question-answering-27099ecb3d1c))
- [Longformer: Empowering COVID-19 Research with Advanced Transformer Capabilities]([url](https://ihiratanveer.medium.com/longformer-empowering-covid-19-research-with-advanced-transformer-capabilities-cf70fd3e8509))

## Contributions
Contributions to this project are welcome! If you find any issues or have ideas for improvements, please feel free to open an issue or submit a pull request.

