---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
The provided code sets up a chat interface using Gradio and the HuggingFace Inference API. It connects to the "HuggingFaceH4/zephyr-7b-beta" model to generate responses based on user input about tourism in Canada. The respond function manages the interaction history and parameters like max_tokens, temperature, and top_p for text generation. The demo variable configures the chat interface with additional inputs for system messages and response settings. Users can interact with the model through predefined examples or custom questions. The chat interface focuses on promoting Canada's tourist destinations and attractions.
