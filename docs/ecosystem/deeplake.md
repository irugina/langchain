# Deep Lake
This page covers how to use the Deep Lake ecosystem within LangChain.

## Why Deep Lake?
- More than just a (multi-modal) vector store. You can later use the dataset to fine-tune your own LLM models.
- Not only stores embeddings, but also the original data with automatic version control.
- Truly serverless. Doesn't require another service and can be used with major cloud providers (AWS S3, GCS, etc.)

## More Resources
1. [Ultimate Guide to LangChain & Deep Lake: Build ChatGPT to Answer Questions on Your Financial Data](https://www.activeloop.ai/resources/ultimate-guide-to-lang-chain-deep-lake-build-chat-gpt-to-answer-questions-on-your-financial-data/)
1. Here is [whitepaper](https://www.deeplake.ai/whitepaper) and [academic paper](https://arxiv.org/pdf/2209.10785.pdf) for Deep Lake
2. Here is a set of additional resources available for review: [Deep Lake](https://github.com/activeloopai/deeplake), [Getting Started](https://docs.activeloop.ai/getting-started) and [Tutorials](https://docs.activeloop.ai/hub-tutorials)

## Installation and Setup
- Install the Python package with `pip install deeplake`

## Wrappers

### VectorStore

There exists a wrapper around Deep Lake, a data lake for Deep Learning applications, allowing you to use it as a vector store (for now), whether for semantic search or example selection.

To import this vectorstore:
```python
from langchain.vectorstores import DeepLake
```


For a more detailed walkthrough of the Deep Lake wrapper, see [this notebook](../modules/indexes/vectorstores/examples/deeplake.ipynb)
