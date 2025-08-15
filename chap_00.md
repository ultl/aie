# Personal Perspective

# 1. NLP before Transformers

- NLP is a field of artificial intelligence that focuses on the interaction
  between computers and humans through natural language. Before the advent of
  transformer models, NLP relied heavily on traditional machine learning
- Three architectures dominated the landscape:
  - **Recurrent Neural Networks (RNNs)**: RNNs were introduced to handle
    sequential data and showed promise in tasks like language modeling and
    machine translation. However, they struggled with long-range dependencies
    and were computationally expensive.
  - **Long Short-Term Memory (LSTM)**: LSTMs were a variant of RNNs designed to
    address the vanishing gradient problem, allowing them to capture long-term
    dependencies more effectively. They became the go-to architecture for many
    NLP tasks, including sentiment analysis and named entity recognition.
  - **Convolutional Neural Networks (CNNs)**: While primarily used for image
    processing, CNNs were also applied to text classification tasks, leveraging
    their ability to capture local patterns.

# 2. NLP after Transformers

- After transformers, NLP has still served specific tasks: text classification,
  sentiment analysis, and named entity recognition, but the underlying
  architectures evolved to leverage the strengths of transformer models.
- After the appearance of LLMs, NLP has shifted towards a more generalized
  approach, where models are trained on vast amounts of data and can perform a
  wide range of tasks without task-specific training.

# 3. NLP in the Era of Foundation Models

- Since NLP before transformers was heavily reliant on task-specific models, the
  introduction of foundation models is meant to operate across multiple
  modalities, such as text and images. As more general purposes, foundation
  models can be pre-trained on large datasets and can be fine-tuned for specific
  tasks, not just for general NLP tasks.

# 4. From Foundation Models to General-Purpose AI

- As served for general purposes, foundation models are applied to build AI
  applications that perform a wide range of tasks. As so versatile and not all
  AI applications will need all the purposes that foundation models offer, there
  are components in AI engineering that helps build on-point AI applications:
  - **Model as a Service (MaaS):** Utilizing pre-trained models via APIs.
  - **Prompt Engineering:** Crafting effective inputs to guide model outputs.
  - **Fine-tuning:** Customizing models for specific tasks or domains.
  - **Evaluation and Monitoring:** Assessing performance and ensuring
    reliability.
