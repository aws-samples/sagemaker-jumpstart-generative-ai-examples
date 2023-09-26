## Jumpstart Generative AI Examples
This repository contains code examples for **SageMaker Jumpstart** Generative AI, a tutorial series designed to help users get started with generative AI using Python and PyTorch.

## Disclaimer
"Sample code, software libraries, command line tools, proofs of concept, templates, or other related technology are provided as AWS Content or Third-Party Content under the AWS Customer Agreement, or the relevant written agreement between you and AWS (whichever applies). You should not use this AWS Content or Third-Party Content in your production accounts, or on production or other critical data. You are responsible for testing, securing, and optimizing the AWS Content or Third-Party Content, such as sample code, as appropriate for production grade use based on your specific quality control practices and standards. Deploying AWS Content or Third-Party Content may incur AWS charges for creating or using AWS chargeable resources, such as running Amazon EC2 instances or using Amazon S3 storage."


### Module 1: Stable Diffusion with Small Dataset of Cat Images
This repository showcases the Stable Diffusion technique, a powerful generative modeling technique that allows for the creation of high-quality images from small datasets. The repository consists of two Jupyter notebooks.

The first notebook, `01-txt2img-gen.ipynb`, demonstrates how to easily create a SageMaker endpoint for the pre-trained Stable Diffusion model and generate cat images based on user prompts. Users can input fun scenarios and prompts to generate various cat images.

<div>
    <img src="./img/cat-3.png" alt="Image 3" width="400" style="display:inline-block">
    <img src="./img/cat-4.png" alt="Image 4" width="400" style="display:inline-block">
</div>
<br>
The second notebook, `02-finetune.ipynb`, showcases the process of fine-tuning the Stable Diffusion model with a small set of images. This approach involves using images of cats from specific breeds or your own pet cats to teach the model how to recreate these images and incorporate them into various creative scenarios. This technique can be adapted to work with any set of images containing fewer than ten examples, such as images of pet dogs or other entities.

By following the steps outlined in the notebook, you can collect a few images of your chosen entity from Google Images and utilize the fine-tuning process to train the Stable Diffusion model to create new and unique compositions. This approach offers a broad range of creative possibilities, allowing you to experiment with various scenarios and unleash your imagination.

<div>
    <img src="./img/cat-1.png" alt="Image 1" width="400" style="display:inline-block">
    <img src="./img/cat-2.png" alt="Image 2" width="400" style="display:inline-block">
</div>

Overall, this repository provides users with a powerful tool for generating high-quality images, even with limited datasets. The Stable Diffusion technique offers a versatile and efficient way to create customized and imaginative images.


### Module 2: FLAN-T5-XL In-Context Learning via Prompt Engineering
This module focuses on utilizing the FLAN-T5-XL Large Language Model (LLM) to achieve N-shot learning via in-context learning. This involves leveraging the model's natural language understanding (NLU) capabilities to personalize virtual assistant responses and improve their performance for users.

In this module, you will learn step-by-step how to perform NLU tasks using FLAN-T5-XL. Specifically, you will learn how to read and understand multi-turn customer support chat transcripts, and engineer prompts that enable FLAN-T5-XL to learn in-context and improve its performance in N-shot learning. This will enhance the model's ability to infer context and answer questions derived from the chat transcripts.

Overall, this module provides an excellent opportunity to explore the capabilities of FLAN-T5-XL in solving NLU tasks, such as text summarization, abstractive question answering, sentiment analysis, and sentiment phrase extraction.

### Module 3: Cohere Medium In-Context Learning via Prompt Engineering
This module focuses on utilizing the Cohere Medium foundation model to achieve in-context learning. This involves leveraging the model's natural language understanding (NLU) capabilities to personalize user's responses and improve their performance.

In this module, you will learn step-by-step how to perform NLU tasks using Cohere Medium. Specifically, you will learn how to engineer prompts that enable Cohere Medium to learn in-context and improve its performance, such as identifying named entities via few-shot learning. This will enhance the model's ability to infer context and answer questions, providing better responses to the user.<br><br>

Overall, this module provides an excellent opportunity to explore the capabilities of Cohere Medium in solving NLU tasks, such as text summarization, abstractive question answering, named entity recognition, and other related tasks through the lens of in-context learning for the benefit of the user.

### Module 4: Legal Document Summarization and Question Answering

In this module, you will learn how to perform short and long-form abstractive text summarization and question answering for legal documents. This module demonstrates a streamlined pipeline that combines three NLP tasks - abstractive text summarization, question generation, and answer generation via abstractive question answering. All of these tasks are accomplished using a single foundation model in a zero-shot setting with prompt engineering.

This approach is common in various industries where traditionally, one might need to create multiple language models that are task-specific. In contrast, this module showcases how large language models can simplify the process of solving multiple tasks in a multi-task and zero-shot setting without providing any examples to the model or fine-tuning the model.


### Usage
Each module has its own subdirectory containing code examples and instructions for use. Simply navigate to the module you are interested in and follow the instructions in the README file.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
