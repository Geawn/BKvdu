## Introduction
**BKvdu** (BK Visual Table Question Answering) is an advanced document understanding approach that leverages an OCR-free, end-to-end Transformer model. Without relying on external OCR engines or APIs, it achieves state-of-the-art performance across various visual document understanding tasks. In this model, we specifically focus on the Table VQA task with support for the Vietnamese language.
## Pre-trained Models and Web Demos

Our model is built upon Vintern-1B-v2, a powerful OCR-free Vietnamese language model. 

The link to the original model is provided below:
- [`vintern-1B-v2`](https://huggingface.co/5CD-AI/Vintern-1B-v2)
## Dataset
We employed web crawling techniques to extract tabular data from Wikipedia, covering a wide range of topics and categories.
![image](images/dataset.png)
The links to the wikitable-generated datasets are here:

- [`wiki-table`](https://huggingface.co/datasets/YuukiAsuna/VietnameseTableVQA): Vietnamese, 5k.

