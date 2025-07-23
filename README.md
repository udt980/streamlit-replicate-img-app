# ✨ Image Generation App ✨

[![Streamlit Replicate Image App][https://github.com/udt980/streamlit-replicate-img-app]



## Overview

Powered by cutting-edge AI models running on [Replicate](https://replicate.com/about) and wrapped in a Streamlit interface, this app lets you transform plain text prompts into mesmerizing visual masterpieces.


## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/tonykipkemboi/streamlit-replicate-img-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd streamlit-replicate-img-app
   ```

3. Install the dependencies:

   ```python
   pip install -r requirements.txt
   ```

4. Rename the `.streamlit/example_secrets.toml` file to `.streamlit/secrets.toml`.

5. Paste your Replicate API token in the secrets.toml file:

   ```bash
   REPLICATE_API_TOKEN = "paste-your-replicate-api-token-here"
   ```

## Usage

1. Run the Streamlit app:

   ```python
   streamlit run streamlit_app.py
   ```

2. Navigate to the provided local URL, and voila! Start crafting your visual narratives.

## Contributions

Your insights can make this tool even better! Feel free to fork, make enhancements, and raise a PR.

## Attribution

- **Developed by**: The wizards over at [Stability AI](https://stability.ai/) 🧙‍♂️

- **Model type**: Diffusion-based text-to-image generative model

- **License**: [CreativeML Open RAIL++-M License](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)

- **Model Description**: This is a model that can be used to generate and modify images based on text prompts. It is a [Latent Diffusion Model](https://arxiv.org/abs/2112.10752) that uses two fixed, pretrained text encoders ([OpenCLIP-ViT/G](https://github.com/mlfoundations/open_clip) and [CLIP-ViT/L](https://github.com/openai/CLIP/tree/main)).

- **Resources for more information**: Check out our [GitHub Repository](https://github.com/Stability-AI/generative-models) and the [SDXL report on arXiv](https://arxiv.org/abs/2307.01952).
