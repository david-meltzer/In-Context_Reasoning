# In-Context_Reasoning

This repository contains work in progress on investigating the ability of LLMs to learn a classification problem from in-context learning.
The classification task we consider is identifying whether a sentence is written using either American or British English.
To perform in-context learning, the model is presented with pairs of sentences and labels, where we arbitrarily chose the labels so a sentence is marked as "True" if it uses American English spelling and "False? if it uses British English spelling.
We generated our sentences using two LLMs, Anthropic's Claude and OpenAI's ChatGPT. 
We then tested the ability of GPT-4 to learn to perform in-context learning using the OpenAI API.
The summary of our current results can be found in the LLM_report.pdf file and our current code can be found in the in_context_learning.ipynb file.

In the future, we hope to add to this repository more examples of in-context learning where we study to what extent LLMs can identify patterns in mathematical expressions.
