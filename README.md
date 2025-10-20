# GhanaLLM

A community-driven project for experimenting with large language models for indigenous Ghanaian languages.

## Overview

As research around large language models (LLMs) continues to evolve, new opportunities are emerging to address long-standing challenges faced by low-resource languages. The GhanaLLM Project aims to establish a common reference point and standardized training approach for developing LLMs capable of performing a wide range of tasks in Ghanaian languages — all built upon a shared base model and powered by community support and experience sharing. Our common base model is [Llama-3.2-1B](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct) due to its broad multilingual training and resource efficient size.

## Available Models

| **Model Name** | **Author** | **Description** | **Links** |
| :------------- | :------------- | :------------- | :------------- |
| Opani Coder | Mich-Seth Owusu | Provides coding assistance in Twi | [Model](https://michsethowusu/opani-coder_1b-merged-16bit) \| [Demo](https://huggingface.co/spaces/michsethowusu/Opani-Coder-DEMO) |

You’re welcome to contribute! To have your model featured in this list, please share the details via email at [michsethowusu@gmail.com](mailto:michsethowusu@gmail.com).


## Contributing

We welcome contributions in several ways:

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

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LdWBCwwIyKrNprhAJHos5ws0Kz-GgHug?usp=sharing)

5. **Share your model URL** with us to be featured on the GhanaLLM project page

## Support

For questions about this project, contact us at: natural.language.processing.gh@gmail.com

---

*GhanaLLM is a community project dedicated to advancing natural language processing for Ghanaian languages.*
