# Synthetic Data Generation with Ragas

There are a lot of cases where it is necessary to create question answer pairs.

This code uses Ragas, LangChain and OpenAI to take a simple one-page text document and create 10 question answer pairs.

Ragas will create a variety of questions from a provided text:

* Factual or Simple questions - based on specific facts in the text.
* Inference or reasoning questions - based on infering information not explicitly stated.
* Contextual questions - based on broader theme or events within the text.

This code provides an introduction to using Ragas for QA generation using Python.
