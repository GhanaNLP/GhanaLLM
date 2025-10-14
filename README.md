# GhanaLLM

A community-driven project to create large language models fine-tuned for indigenous Ghanaian languages.

## Overview

GhanaLLM uses a standardized LoRA approach with `unsloth/Qwen3-4B-Instruct-2507` to simplify model training and produce portable output files for easy inference and fine-tuning.

## Available Models

| **Model Name**       | **Author**         | **Description and Demo Link**                                             |
|-----------------------|--------------------|-------------------------------------------------------------|
| Twi Code Instruct     | Mich-Seth Owusu    | Coding assistance in Twi [Demo](https://huggingface.co/spaces/michsethowusu/code-in-twi)    |


## Contributing

We welcome contributions in several ways:

### Test and Provide Feedback
Use our testing notebook to evaluate models and share your feedback.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16Ld0vcjHq78b3HmAt58JrT6w1BchFxja?usp=sharing)

### Train Your Own Model
Follow the steps below to create and publish your own model.

### Fine-tune Existing Models
Improve model performance using our fine-tuning notebook (link to be added).

## Training and Publishing Your Model

1. **Create a Hugging Face account** and obtain your username and access token

2. **Select a dataset** from Hugging Face which has question and answer columns, then copy the dataset ID e.g. the ID for [this dataset](https://huggingface.co/datasets/theblackcat102/alexa-qa) is `theblackcat102/alexa-qa`.

3. **Prepare your dataset** using our data preparation notebook:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1445avuPRt9kjcr-cWO_NYSTBPIoHgksL?usp=sharing)

4. **Train and publish** your model with our training notebook:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LirzhiQzOOK1Cvf-Dm_yEMe8CncDwEw8?usp=sharing)

5. **Share your model URL** with us to be featured on the GhanaLLM project page

## Support

For questions or assistance, contact us at: michsethowusu@gmail.com

---

*GhanaLLM is a community project dedicated to advancing natural language processing for Ghanaian languages.*
