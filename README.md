# AI Text Completion App

This project is a simple AI-powered text generation tool built using both [Hugging Face Transformers](https://huggingface.co/transformers/) and the [OpenAI API](https://platform.openai.com/). It allows users to enter a prompt and receive a completion from a large language model.

---

## Setup
This project supports two backends for AI text generation:

1. Hugging Face Transformers: No key required for public models like gpt2
2. OpenAI API

    Create an account at https://platform.openai.com

    Go to your account → API Keys → click Create new secret key

    Set your key as an environment variable

You can use either or both depending on your needs.

## Dependencies

Install the following Python libraries:

```bash
pip install openai
pip install transformers torch
```
## Usage

Using the OpenAI API or a local model via Hugging Face Transofrmers Model, enter a prompt and receive a response.

Example Promots
- "Finish this sentence: I can't go to work because..."
- "Recipe for chicken noodle soup"
- "Explain triangle congruency like i'm 10 years old."
