# Prompt Engineering 

## Introduction

This repository contains a tutorial for prompting models GPT-3.5 & GPT-4. But before we dig into that, lets understand a few key concepts.

### What is the Prompt?​

A prompt involves instructions and context passed to a language model to achieve a desired task.​

### What is Prompt Engineering?​

Prompt Engineering is the practice of developing and optimizing prompts to efficiently use language models for a variety of applications. 

### Tokens

You can think of tokens as pieces of words used for natural language processing. For English text, 1 token is approximately 4 characters or 0.75 words. 

## Recommended Reading

(Principled Instructions Are All You Need for Questioning LLaMA-1/2, GPT-3.5/4)[https://arxiv.org/html/2312.16171v2]

### Prompting Principles 

| Number | Prompt Principle for Instructions | Example | Note |
|--------|-----------------------------------|---------|------|
| 1 | No need to add polite phrases, get straight to the point. | "Summarize the article." | Generated |
| 2 | Integrate the intended audience in the prompt. | "Explain quantum mechanics to a physicist." | Generated |
| 3 | Break down complex tasks into simpler prompts. | "What is the first step in solving a quadratic equation?" followed by subsequent steps. | Generated |
| 4 | Use affirmative directives. | "Do explain the theory of relativity." | Generated |
| 5 | Use prompts for clarity or deeper understanding. | "Explain photosynthesis to me like I'm 11 years old." | Existing |
| 6 | Add a tipping incentive for a better solution. | "I'm going to tip $20 for a better solution!" | Existing |
| 7 | Use example-driven prompting (few-shot prompting). | "Given the examples A, B, and C, how would you solve X?" | Generated |
| 8 | Start with '###Instruction###' followed by content. | "###Instruction### Explain gravity. ###Example### Like objects falling." | Generated |
| 9 | Incorporate "Your task is" and "You MUST". | "Your task is to analyze the data, and you MUST provide insights." | Generated |
| 10 | Incorporate "You will be penalized". | "You will be penalized for incorrect grammar usage." | Generated |
| 11 | Use natural, human-like responses. | "Answer the question as if you were talking to a friend." | Generated |
| 12 | Use leading words like "think step by step". | "Think step by step how you would organize a birthday party." | Generated |
| 13 | Ensure unbiased answers avoiding stereotypes. | "Ensure that your answer is unbiased and avoids relying on stereotypes." | Existing |
| 14 | Allow the model to ask questions for clarity. | "From now on, I would like you to ask me questions to clarify my requests." | Generated |
| 15 | Include a teaching component and a test. | "Teach me about Newton's laws and include a test at the end." | Existing |
| 16 | Assign a role to the model. | "You are a tutor helping a student with algebra." | Generated |
| 17 | Use Delimiters. | "####Start#### Your response here. ####End####" | Generated |
| 18 | Repeat a specific word or phrase. | "Sustainability, sustainability, sustainability is key to future development." | Generated |
| 19 | Combine Chain-of-thought with few-shot prompts. | "Given the problem A, think through the steps B, C, D to solve it. Similar to examples X, Y, Z." | Generated |
| 20 | Use output primers with the beginning of the desired output. | "The key points in this argument are: 1. ... (complete the list)" | Generated |
| 21 | Write detailed text on a topic. | "Write a detailed essay for me on the impacts of global warming in detail by adding all the information necessary." | Existing |
| 22 | Correct/change text without changing its style. | "Revise this paragraph for grammar and vocabulary while maintaining its original style." | Existing |
| 23 | Handle complex coding prompts for multi-file scripts. | "Generate a Python script that can create specified files for a multi-component app." | Generated |
| 24 | Initiate or continue a text with specific beginnings. | "I'm providing you with the beginning of a story: 'Once upon a time...'. Finish it based on the words provided." | Existing |
| 25 | Clearly state model's content production requirements. | "Write a story that includes a dragon, a castle, and a lost crown, without using violence." | Generated |
| 26 | Write text similar to a provided sample. | "Use the same tone and style based on the provided essay excerpt." | Existing |

## Setup 
### Pre-requisites (To be cleaned up)
1. Install Visual Studio Code
1. Install Python >= 3.10
1. Install Visual Studio Code Extensions:
    1. Python
    1. Jupyter Notebook

### Navigate to Notebook
Open the notebook [main.ipynb](main.ipynb) in Visual Studio Code.

## References
1. https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/advanced-prompt-engineering?pivots=programming-language-chat-completions
1. https://learn.microsoft.com/en-us/azure/cognitive-services/openai/how-to/chatgpt?pivots=programming-language-chat-completions
1. https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/prompt-engineering#best-practices
1. https://learn.microsoft.com/en-us/azure/architecture/guide/ai/conversation-summarization
1. https://news.microsoft.com/en-gb/2023/03/23/seven-things-to-know-about-responsible-ai/
