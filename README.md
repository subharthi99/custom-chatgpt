# custom-chatgpt

Simple script to use ChatGPT on custom data files.


## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
Modify `constants.pyt` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys).

Place your own data into `data/data.txt` or if you're using a pdf replace 'data/machine-learning.pdf'.
