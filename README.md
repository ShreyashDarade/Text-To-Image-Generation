# Stable Diffusion XL Image Generator

This repository provides a Gradio-based web interface for generating images using Stable Diffusion XL with perturbed attention guidance.

## Features
- Generate high-quality AI-generated images from text prompts.
- Uses [Stable Diffusion XL Base 1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0).
- Implements perturbed attention guidance from [Multimodal Art](https://huggingface.co/multimodalart/sdxl_perturbed_attention_guidance).
- Supports CUDA acceleration for efficient image generation.

## Installation
Clone this repository and install the dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the script to launch the Gradio interface:
```bash
python app.py
```

## Credits
This project utilizes the following models:
- [Stable Diffusion XL Base 1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
- [Perturbed Attention Guidance by Multimodal Art](https://huggingface.co/multimodalart/sdxl_perturbed_attention_guidance)

## License
This project is open-source and follows the licensing terms of the utilized models.

