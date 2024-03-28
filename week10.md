# FinVis-GPT: A Multimodal Large Language Model for Financial Chart Analysis

Author: _Ziao Wang, Yuhang Li, Junda Wu ,Jaehyeon Soon, Xiaofeng Zhang_

Link: https://arxiv.org/abs/2308.01430

Conference: The 32nd International Joint Conference on Artificial Intelligence (**IJCAI 2023**) - August 19-25th - Macao, S.A.R

## Abstract
- `FinVis-GPT` is a multimodal large language model specifically designed for financial chart analysis. It incorporates instruction tuning and multimodal capabilities to interpret financial charts and provide valuable analysis.
- The model outperforms existing state-of-the-art multimodal language models in various financial chart-related tasks, including:
    - generating descriptions,
    - answering questions, and
    - predicting future market trends.
 
## Key aspects

- Large language models (LLMs) and multimodal models (LMMs) have shown superior performance in various natural language processing (NLP) tasks and complex applications.

- The paper introduces `FinVis-GPT`, a novel multimodal LLM specifically designed for financial chart analysis in the finance domain.
 
- `FinVis-GPT` leverages the benefits of pre-trained LLMs and incorporates instruction tuning and multimodal capabilities to interpret financial charts and provide valuable analysis.

- The model is trained on a financial task-oriented dataset, comprising various types of financial charts and their corresponding descriptions, to enhance its performance in generating descriptions, answering questions, and predicting future market trends.

- The proposed FinVis-GPT demonstrates promising results, surpassing existing state-of-the-art multimodal LLMs in various financial chart-related tasks.

- The paper aims to lay the foundation for more sophisticated applications of AI in finance, potentially transforming the landscape of financial analysis.
## Design Process
![image](https://github.com/avivnur/reflections-research/assets/47585222/7dab3b54-1b9d-45f5-abe3-c10f421b2243)

## Generating multimodal Financial Dataset
1. Pre-training alignment dataset
   
  ![image](https://github.com/avivnur/reflections-research/assets/47585222/d98ffbce-8fab-4100-a46e-cdf8eb373a2c)

2. Instruction tuning

   ![image](https://github.com/avivnur/reflections-research/assets/47585222/03ea3517-ef60-4bc0-a655-690a871bbf1a)

## Model architecture
![image](https://github.com/avivnur/reflections-research/assets/47585222/586d5339-400e-439f-9774-4f76431284c3)

## Experimental results
![image](https://github.com/avivnur/reflections-research/assets/47585222/1ebff93b-d651-44c3-9099-cfc552a85f74)


## Results
|No|Tasks|Descriptions|Results|
|---|-----|--------------|------------------|
|1. |Description Generation|the models were given an image of a financial chart and were required to generate a description, capturing the key trends, patterns, and anomalies.|FinVis-GPT emerged as the most proficient, correctly recognizing the image and providing a concise and accurate description.|
|2. |Question Answering|a comprehension test where models were given an image of a financial chart along with a set of questions. The questions were designed to assess the model’s understanding of the financial context of the chart.|the response provided by FinVis-GPT was both concise and accurate, earning it the top spot amongst the compared models for this task. Its output underscores the superior efficacy of FinVis-GPT in understanding and accurately answering questions based on the given visual representation.|
|3. |Trend Prediction|the models were provided an image of a financial chart along with historical financial data and were asked to predict future trends.|FinVis-GPT’s prediction was not only accurate but also incorporated a proper description of the trend. This showcases FinVis-GPT’s superiority intrend prediction tasks, with an ability to provide both accurate and informative responses|

## References
1. Wang, Z., Li, Y., Wu, J., Soon, J., & Zhang, X. (2023). Finvis-gpt: A multimodal large language model for financial chart analysis. arXiv preprint arXiv:2308.01430.
