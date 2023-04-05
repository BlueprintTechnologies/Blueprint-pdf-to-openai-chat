# Blueprint PDF-to-OpenAI Chat
Steps to take scanned PDFs, OCR them and embed them in questions to OpenAI's chat models

## Overview
Large Language Models (LLMs), such as OpenAI’s ChatGPT and GPT-4, as well as Microsoft Bing, are incredibly powerful tools. They excel in tasks like summarizing content, extracting meaning, generating new ideas, translating complex texts, and more.

While commercial implementations of OpenAI’s GPT models do not offer built-in training capabilities on your specific data, there are open-source models available for those interested in a more customized approach. However, this option can be computationally demanding and requires advanced programming skills.

Fortunately, there’s an alternative. Platforms like OpenAI and Microsoft Azure offer models that enable users to combine relevant data with a prompt or question during runtime. This allows the model to apply its language understanding capabilities and generate responses similar to those produced by ChatGPT and Bing, as though your data were part of its training corpus.

The included notebook demonstrates how to extract text from a pdf, splitting/converting data into embeddings, connecting to the OpenAI api or the Azure OpenAI service, then finally interacting with that data via chat style inputs.

## Special Thanks
This accelerator was built by [Eric Vogelpohl](https://github.com/Evogelpohl). More details about the motivation for this accelerator are available at [this blog post](https://medium.com/@EricVogelpohl/your-data-and-chatgpt-e1d6c1f050eb).
