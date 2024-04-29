# A Multimodal LLM for Chart Understanding and Generation

Author: Yucheng Han, Chi Zhang, Xin Chen, Xu Yang,
Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang

Link: https://arxiv.org/abs/2311.16483

Reflection:
- Generate data from a theme and trend, then generate figures based off of that data using GPT-4
- Fine-tune ChartLlama, a model based on LLaVA-1.5, trained on generated datasets as well as existing datasets, to read raw data and a chart’s description and interpret Q&A questions about it. 558k images are utilized in total
- Data generation is based on theme, data trends, column/row length (to limit dataset size), and chart type
- Figure generation is based on Python and matplotlib code, feeding in previous high-quality “in-context” examples so the model is aware of proper code structure to generate
- ChartLlama can take in text data or interpret given figures, and is evaluated on metrics against ground truth results through the use of GPT-4. Through the ability to interpret figures, it allows for editing of existing figures. It also has a Q&A ability to answer questions about provided data

Technology used:
- LLM: ChartLlama (based on GPT-4 and LLaVA-1.5)
- Language for Front End: Python and matplotlib for chart generation
