# GhanaLLM

A community-driven project for experimenting with large language models for indigenous Ghanaian languages.

## Overview

As research around large language models (LLMs) continues to evolve, new opportunities are emerging to address long-standing challenges faced by low-resource languages. The GhanaLLM Project aims to establish a common reference point and standardized training approach for developing LLMs capable of performing a wide range of tasks in Ghanaian languages — all built upon a shared base model and powered by community support and experience sharing. Our common base model is [Llama-3.2-1B](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct) due to its broad multilingual training and resource efficient size.

## Available Models

| **Model** | **Training Dataset** | **Description** | **Demo** | **Creator** |
| :------------- | :------------- | :------------- | :------------- | :------------- |
| [Opani Coder](https://huggingface.co/ghananlpcommunity/opani-coder_1b-merged-16bit) | [Code-170k-twi](https://huggingface.co/datasets/ghananlpcommunity/Code-170k-twi) | Provides coding assistance in Twi | [Demo](https://huggingface.co/spaces/ghananlpcommunity/Opani-Coder-DEMO) | [Mich-Seth Owusu](https://www.linkedin.com/in/mich-seth-owusu/) |
| [Opani Translate](https://huggingface.co/ghananlpcommunity/opani-translate_1b-merged-16bit) | [english-twi-translate-llm-instruct-160k](https://huggingface.co/datasets/ghananlpcommunity/english-twi-translate-llm-instruct-160k) | Provides translation from English to Twi | [Demo](https://huggingface.co/spaces/ghananlpcommunity/Opani-Translate-Demo) | [Mich-Seth Owusu](https://www.linkedin.com/in/mich-seth-owusu/) |


## Contributing

We welcome contributions in several ways:

### Train Your Own Model
Follow the steps below to create and publish your own model.

### Fine-tune Existing Models
Improve model performance using our fine-tuning notebook (link to be added).

## Training and Publishing Your Model

1. **Create a Hugging Face account** and obtain your username and access token. You will need this for getting access to any of our community datasets anfd publishing your model. 

2. **Request access to a community dataset** You can visit our community page on hugging face to request any acess to the datasets in the Ghana LLM collection for training models. https://huggingface.co/collections/ghananlpcommunity/ghana-llm. Before requesting access, please read this link about contributing - https://github.com/GhanaNLP/Community-Docs/blob/main/CONTRIBUTING.md

3. **Train and publish** your model with our training notebook:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LdWBCwwIyKrNprhAJHos5ws0Kz-GgHug?usp=sharing)

4. **Share your model URL** with us to be featured on the GhanaLLM project page

## Support

For questions about this project, contact us at: natural.language.processing.gh@gmail.com
To have your model featured in this list, please send the details to [michsethowusu@gmail.com](mailto:michsethowusu@gmail.com).

---

*GhanaLLM is a community project dedicated to advancing natural language processing for Ghanaian languages.*
