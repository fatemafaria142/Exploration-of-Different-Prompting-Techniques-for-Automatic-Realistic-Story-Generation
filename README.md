# Exploration of Different Prompting Techniques for Automatic Realistic Story Generation

This project explores various prompting techniques for automatic realistic story generation, utilizing the GPT-2 language model. The techniques include `Zero Shot`, `Chain of Thought`, and `Automatic Chain of Thought`. The story evaluation is conducted using the `BertScore` metric.

## Dataset

- **Dataset Name:** Atlas Storyteller
- **Dataset Link:** [Atlas Storyteller Dataset](https://huggingface.co/datasets/AtlasUnified/atlas-storyteller?row=42)
- **Description:** The "atlas-storyteller" dataset serves as the foundation for training and testing the story generation models.

## GPT-2 Model

- **Model Source:** [Hugging Face GPT-2](https://huggingface.co/docs/transformers/model_doc/gpt2)
- **Description:** The GPT-2 model from Hugging Face is employed as the core language model for the story generation task.

## Prompting Techniques

### 1. Zero Shot

- **Description:** Zero Shot prompting involves generating a story without any initial context or seed. The model is presented with a blank canvas, and the narrative unfolds based on the inherent capabilities of the GPT-2 model.

### 2. Chain of Thought

- **Description:** Chain of Thought prompting entails providing a series of prompts sequentially. Each prompt builds upon the preceding one, guiding the model's thought process and encouraging the development of a coherent storyline.

### 3. Automatic Chain of Thought

- **Description:** Automatic Chain of Thought combines the principles of Chain of Thought with automated prompt generation. The model dynamically generates prompts during the story generation process, ensuring a continuous and evolving narrative.

## Story Evaluation - BertScore

- **Metric:** BertScore
- **Description:** BertScore is used to evaluate the generated stories. It assesses the quality of the generated text by comparing it to reference text using contextual embeddings.
