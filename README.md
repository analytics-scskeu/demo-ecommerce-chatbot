# E-commerce Chatbot

In the rapidly evolving world of e-commerce, providing exceptional customer service and personalized shopping experiences is crucial. One effective way to achieve this is through the integration of intelligent chatbots. However, building a chatbot that can effectively handle both structured and unstructured data is a complex challenge.

To address this challenge, we employ a multi-step approach:
- **Step 1: Data Filtering with LLM** - We use a Large Language Model (LLM) to pre-filter the data.
- **Step 2: Relevant Data Extraction with RAG** - We implement the LLM in a Retrieval-Augmented Generation (RAG) architecture to identify the most relevant parts of the data and generate accurate responses.

Experiments show that RAG on its own is not very accurate and often produces random answers. However, pre-filtering the data using an LLM results in more deterministic and consistent outcomes.


Data Source: [Amazon Product Dataset 2020 - Kaggle](https://www.kaggle.com/datasets/promptcloud/amazon-product-dataset-2020?resource=download)

