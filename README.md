# GenIA
Ce notebook est conçu pour démontrer l'utilisation des modèles TranslateGemma de Hugging Face. un pipeline de image-text-to-text en utilisant le modèle google/translategemma-4b-it. Traduction d'images :  traduire le contenu d'une image. 

## Description

This project demonstrates how to use the TranslateGemma model for text and image translation. It leverages the Hugging Face `transformers` library to build a translation pipeline.

## Getting Started

### Prerequisites

*   Google Colab environment
*   Hugging Face API token (stored in Colab secrets as `HF_TOKEN`)

### Installation

All necessary libraries are imported at the beginning of the notebook.

### Running the Notebook

1.  Ensure your Hugging Face token is correctly set up in Colab secrets.
2.  Run all cells sequentially.

## Usage

### Text Translation

Modify the `text` variable and the `target_lang_code` in the `messages` list to translate different text snippets to various languages.

### Image Translation

To translate an image, upload your image to the `/content/` directory in your Colab environment and update the `image` path to point to your image file (e.g., `Image.open("/content/your_image.jpg")`). You can also change the `target_lang_code` for different target languages.
