# Stable Diffusion Image Generation Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XK8uosGFsnK79b11aeQ_KW2we6wjsQoZ?usp=sharing)

## Overview

This project demonstrates how to use a Stable Diffusion model to generate images from textual descriptions. Using the `diffusers` library, the project supports both command-line and GUI-based interactions for image generation.

## Features

- **Data Loading:** Load and preprocess images and captions from the COCO 2017 dataset.
- **Text Preprocessing:** Clean and normalize captions to enhance text input quality.
- **Image Generation:** Generate images from textual prompts using a Stable Diffusion model.
- **Interactive GUI:** Utilize `ipywidgets` to input or select captions interactively.

## Installation

Make sure to install the necessary dependencies:

```bash
pip install torch torchvision transformers diffusers ipywidgets matplotlib --quiet
