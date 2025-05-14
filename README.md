# Exploring the Feasibility of Multilingual Grammatical Error Correction with a Single LLM up to 9B parameters: A Comparative Study of 17 Models - dataset


## What is this?

This repository contains the dataset used in the paper: 

Exploring the Feasibility of Multilingual Grammatical Error Correction with a Single LLM up to 9B parameters: A Comparative Study of 17 Models (accepted at MTSummit 2025)

## And how about some more details?

Can a single, moderately-sized LLM effectively correct grammar in multiple languages simultaneously? We put 17 popular models to the test on English, German, Italian, and Swedish datasets.
🔍 Our analysis goes beyond just accuracy — we looked at:
how well models preserve meaning,
whether they minimize unnecessary edits,
how they handle already-correct text,
and whether they "drift" into English when they shouldn't.
🏆 Gemma 9B came out on top, but smaller models like Gemma 2B and EuroLLM 1.7B also performed impressively for their size — proving that smart training matters more than just the number of parameters.
📄 Paper: https://arxiv.org/abs/2505.06004
📂 Code & outputs: https://github.com/laniqo-public/grammar-data-mtsummit25

**In this repository you can find examples of sentences and corrections proposed by evaluated language models**

## Where can I find the paper?

You can read this paper here: [https://www.arxiv.org/abs/2505.06010](https://arxiv.org/abs/2505.06004) 

## Citing this work:

```
@misc{wisniewski2025exploringfeasibilitymultilingualgrammatical,
      title={Exploring the Feasibility of Multilingual Grammatical Error Correction with a Single LLM up to 9B parameters: A Comparative Study of 17 Models}, 
      author={Dawid Wisniewski and Antoni Solarski and Artur Nowakowski},
      year={2025},
      eprint={2505.06004},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2505.06004}, 
}
```
