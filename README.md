# Hugging Face Tasks

This repository contains Jupyter notebooks for experimenting with various NLP and computer vision tasks using Hugging Face Transformers.

## Contents

- **Document Question Answering**: A notebook demonstrating how to use pre-trained models to answer questions about document images.
- **Language Modeling**: A comprehensive notebook covering Causal and Masked language finetuning tasks using Hugging Face models.
- **Embeddings**: A notebook showing how to generate and use text and image embeddings for similarity search and retrieval.

## Getting Started

### Prerequisites

- Python 3.12
- Required packages can be installed using Pipenv (Pipfile included)

```bash
# Install pipenv if you don't have it
pip install pipenv

# Install dependencies
pipenv install
```

### Notebooks

#### Document QA

The `document_qa.ipynb` notebook demonstrates how to:
- Set up a document question-answering pipeline using Hugging Face
- Load document images and ask questions about their content
- Use pre-trained models like "naver-clova-ix/donut-base-finetuned-docvqa"

#### Language Modeling

The `language_modeling.ipynb` notebook covers language modeling tasks including:
- Text generation
- Fine-tuning language models
- Working with the Hugging Face datasets library

#### Embeddings

The `embeddings.ipynb` notebook demonstrates:
- Generating text embeddings using sentence-transformers models
- Creating image embeddings with ViT (Vision Transformer)
- Performing similarity search with both text and image data
- Computing dot product similarity scores between embeddings

## Data

The repository includes sample data in the `data/` directory for testing the document QA functionality.

## License

This project is for educational purposes only. All Hugging Face models used are subject to their respective licenses.