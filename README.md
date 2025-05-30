# Generative AI with Diffusion, CLIP, BLIP, and VQA

This project demonstrates the power of multimodal AI by combining image generation, classification, captioning, and question answering using models from Hugging Face and PyTorch.

You'll explore how to generate images from text prompts, evaluate them using vision-language models, and perform reasoning about visual content.

## Technologies Used

- **Stable Diffusion XL (SDXL)** for text-to-image generation
- **CLIP (Contrastive Language–Image Pretraining)** for image-text similarity evaluation
- **BLIP (Bootstrapped Language Image Pretraining)** for image captioning and visual question answering
- **BLIP-VQA** for answering questions about visual content
- Powered by **Hugging Face Transformers**, **Diffusers**, and **PyTorch**

---

## Project Capabilities

### 1. Text-to-Image Generation
Generate realistic and artistic images from simple or complex natural language prompts using Stable Diffusion XL.

### 2. Image Classification with CLIP
Classify images with short labels and detailed descriptions by comparing image-text alignment probabilities.

### 3. Complex Scene Generation
Generate scenes involving multiple objects (e.g., "3 deer, 2 trees, 1 sun") and verify object counts visually.

### 4. Visual Verification with CLIP
Evaluate whether generated scenes match expected object counts using CLIP.

### 5. Image Captioning with BLIP
Generate rich, human-like captions for images using BLIP's large-scale image captioning model.

### 6. Visual Question Answering
Ask BLIP-VQA questions about an image (e.g., “How many clouds are there?”) and get meaningful answers.

---

## Example

**Prompt:** `3 deer with 2 trees in the background with 1 sun and 1 cloud`

- Image generated via Stable Diffusion XL
- Caption from BLIP: `"three deer in a grassy field with trees"`
- VQA responses:
  - How many deer? → `3`
  - How many trees? → `2`
  - How many clouds? → `1`

---

## Getting Started

### Setup

```bash
git clone https://github.com/kexin516/Generative-AI-with-Diffusion-CLIP-BLIP-and-VQA.git
cd Generative-AI-with-Diffusion-CLIP-BLIP-and-VQA

# Install dependencies
pip install -r requirements.txt
