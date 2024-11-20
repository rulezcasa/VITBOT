
# Inquiry And FAQ Chatbot Custom Trained on VIT’s Knowledge Base

## Overview
This project focuses on building a chatbot for VIT Chennai to automate university-related inquiries and make information more accessible. The chatbot will act as a one-stop solution for answering questions about programs, fees, application deadlines, and more, saving users from having to search through the university website. It’s available 24/7, offering much faster responses compared to emails or in-person inquiries.


## Directory structure

```
project_root/
├── Dataset/
│   └── data.json          #Compiled corpus
└── Llama.ipynb/
```


## Dataset

The dataset comprises of question - answer paids collected by web scraping and augmenting.

  <img width="1452" alt="Screenshot 2024-11-20 at 9 51 34 PM" src="https://github.com/user-attachments/assets/abb34bea-2de0-4869-bfae-83cb6762038b">

## Results

<p align="center">
  <img src="https://github.com/user-attachments/assets/f5f8e194-267e-4c0c-9e8a-a7d8a7305717" width="400"/>
</p>


### Model Accuracy and Response Quality
The Llama model, after being fine-tuned with the data from the university’s website, showed
considerable accuracy in understanding and responding to user queries. The integration of
LoRA for optimized tuning improved the model’s performance, enabling it to provide relevant
answers even with minimal fine-tuning. The model’s contextual understanding, powered by
Llama, ensured that queries were interpreted correctly, and the responses were both accurate
and contextually appropriate.

### Challenges and Limitations
While the system performed well overall, there were some challenges in ensuring the chat-
bot’s responses were fully accurate in handling ambiguous queries. For certain complex or
highly specific inquiries, the chatbot’s responses were less precise. Additionally, the model’s
performance could be further enhanced by integrating more structured data and expanding its
knowledge base. Further, experimentations with temperature, top p values could yield more
precise results without creating


## Appendix

**Funding:** H. Thangaraj, N. Natesan, K. Agarwal, A. Singh
contributed to this work while undertaking a research collaboration with the Department of Computer Science, Vellore Institute of Technology under Professor Nithya Darisini PS.

**Data Access Statement:** This study utilizes publicly available data scraped from VIT Chennai's website, which has been pre-processed by the authors for fine-tuning large language models (LLMs). If this pre-processed data is used in other work, please provide appropriate citation to this codebase.

**Note:** Please, when using any of the resources provided here, remember to cite this codebase

