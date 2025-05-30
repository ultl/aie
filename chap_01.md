# **Chapter 1. Introduction to Building AI Applications with Foundation Models**

- Training AI models requires significant resources and expertise. Model as a
  Service (MaaS) enables developers to integrate advanced AI by accessing models
  as services, removing the need to build or maintain them.

## A. The Rise of AI Engineering

## **1. From Language Models to Large Language Models**

- Language models use statistical properties of language for tasks like text
  generation and understanding.
- Early history:Claude Shannon’s work in information theory (entropy,
  redundancy, channel capacity) laid the foundation for language modeling.
- Early models focused on single languages and had limited scope.
- Tokenization breaks text into tokens (words or sub-words), forming a
  vocabulary. Tokens capture more meaning than characters and make models more
  efficient.
- Example: "unhappiness" → "un", "happi", "ness".

- Types of language models:
  - **Masked Language Models (MLMs):** Predict missing tokens anywhere in a
    sequence (e.g., BERT).
  - **Autoregressive Language Models (ARLMs):** Predict the next token in a
    sequence (e.g., GPT).

> This book focuses on Autoregressive Language Models (ARLMs).

- **Self-supervised learning:** Models learn from unlabeled data by predicting
  parts of the input, enabling scalable training on large datasets.
- **Supervised learning:** Relies on labeled data, which is costly and
  time-consuming.
- **Unsupervised vs. self-supervised:** Unsupervised uses no labels;
  self-supervised creates labels from the input data itself.

- Large Language Models (LLMs) are decoder-only, trained on massive datasets
  using self-supervised learning. They generate human-like text and perform
  diverse language tasks.

## **2. From Large Language Models to Foundation Models**

- Traditionally, AI research was organized by data modality: NLP (natural
  language processing) for text, CV (computer vision) for images, and ASR
  (automatic speech recognition) for audio.
- **Foundation models** are capable of working across multiple modalities, such
  as text and images. When these models generate outputs in more than one
  modality, they are often called **large multimodal models (LMMs)**.

<p align="center">
  <img src="img/tasks.png" alt="AI Tasks" width="50%">
</p>

## **3. From Foundation Models to AI Engineering**

- **AI Engineering** is the discipline of building AI applications using
  foundation models. Key components include:
  - **Model as a Service (MaaS):** Leveraging pre-trained models through APIs.
  - **Prompt Engineering:** Designing effective inputs to influence model
    outputs.
  - **Fine-tuning:** Customizing models for specific tasks or domains.
  - **Evaluation and Monitoring:** Measuring performance and ensuring
    reliability.
- The rapid growth of AI Engineering is driven by:
  - The adaptability of general-purpose models to a wide range of tasks, unlike
    earlier task-specific models.
  - Increased investment in AI technologies.
- **Low barrier to entry:** Developers can integrate advanced models into
  applications without deep AI expertise. MaaS enables easy access to powerful
  models via APIs, removing the need for building or maintaining them.

- Common generative AI use cases in both consumer and enterprise settings
  include:

<p align="center">
  <img src="img/cases.png" alt="Generative AI Use Cases" width="50%">

[Figure 1-7](https://www.oreilly.com/library/view/ai-engineering/9781098166298/ch01.html#ch01_figure_7_1730130814920012)
shows the distribution of these use cases among the 205 open source
applications. Note that the small percentage of education, data organization,
and writing use cases doesn’t mean that these use cases aren’t popular. It just
means that these applications aren’t open source. Builders of these applications
might find them more suitable for enterprise use cases.

<p align = ' center'> <img src = 'https://www.oreilly.com/api/v2/epubs/9781098166298/files/assets/aien_0107.png' alt="Distribution of use cases in the 205 open source repositories on GitHub." width="50%"> </p>

###### Figure 1-7. Distribution of use cases in 205 open source GitHub repositories.

Enterprises typically favor lower-risk AI applications. According to the
[2024 a16z Growth report](https://oreil.ly/XWeDt), companies are quicker to
deploy internal-facing applications (like knowledge management) than
external-facing ones (such as customer support chatbots), as shown in

[Figure 1-8](https://www.oreilly.com/library/view/ai-engineering/9781098166298/ch01.html#ch01_figure_8_1730130814920037).
Internal apps help organizations build AI expertise while reducing risks related
to privacy, compliance, and failures. Many foundation model applications remain
close-ended (e.g., classification), as these are easier to evaluate and manage.

![Graph showing internal vs. external AI application deployment](https://www.oreilly.com/api/v2/epubs/9781098166298/files/assets/aien_0108.png)

###### Figure 1-8. Companies more readily deploy internal-facing AI applications.

The landscape of AI applications is rapidly evolving, with new and unexpected
use cases emerging regularly. As with the early internet, the most impactful AI
use case may still be ahead of us.
