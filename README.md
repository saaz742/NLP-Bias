# NLP-Bias


Dr Asgari - Spring 2023

Sharif university

98170668 -> Sara Azarnoush

98101566 -> Mohammadreza Daviran

98171007 -> Nona Ghazizadeh

## Contents

  - [Document (Page 12)](https://github.com/saaz742/NLP-Bias/blob/main/HW3.pdf)
  - [Notebook](https://github.com/saaz742/NLP-Bias/blob/main/NLP_HW3.ipynb)

## <font color='red'> Introduction

Bias in the machine means the directionality of the learned model recognition. 

Biases can have different types, Here we will examine two types of bias based on race and bias based on gender.

We use Bert models using attention and masking to get the gender bias we input some different jobs in Persian and English language and calculate each gender weight.

We use XLM-RoBERTa (MLM) for both gender and race bias in different languages.

After that, we evaluate models by scoring them.

Try to improve models by creating and finetuning models.

In the end we we evaluate the model after changing it.


## Notebook's table of contents

 - Introduction
 - Requirements
    - Download
    - Import

 - Bias in gender
  - Bert models using Attention
    - Use "bert-base-uncased" for bias in gender (English)
    - Use "distil-bigbird-fa-zwnj" for bias in gender (Persian)
   - Bert models using Masking
    - Use "bert-large-uncased" for bias in gender (English)
    - Use "bert-base-parsbert-uncased" for bias in gender (Persian)

 - Multi-language bias XLM-RoBERTa (MLM)
  - Gender
    - Persian
    - English
    - Portuguese
    - Italian
    - Japanese
    - Turkish
  - Race

- Evaluating models
  - Gender
  - Race
- Bias correction
  - Create an unbiased dataset
  - Finetune bert-fa-zwnj-base
- Evaluating models after bias correction

  
