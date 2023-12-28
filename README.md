# Chatting with PDFs using LLAMA2

## Introduction

This notebook showcases how to use an open-source Large Language Model (LLM), Meta's LLaMA2-13B, for chatting with a provided PDF document. The model is quantized to 4-bits for performance optimization and is designed to respond to user queries by referring to the document.

## Approach

Falling under the category of **Generative Question-Answering (GQA)** and utilizing the **Retrieval-Augmented Generation (RAG)** technique, the notebook establishes a pipeline where the LLM fetches data from a given PDF document to augment its responses to user queries. This is achieved through **prompt engineering**, **vector storage**, and a **specialized ChatBot class**.

## Outputs

![error](https://i.ibb.co/zhRtwzh/pdf1.png)

![error](https://i.ibb.co/HF2sPDj/pdf2.png)
