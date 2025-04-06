====================================================
               HomeMatch - Real Estate AI
====================================================

Description:
------------
HomeMatch is an AI-powered real estate matching system that personalizes property listings based on user preferences. It uses Large Language Models (LLMs), vector databases, and multimodal embeddings (text + image) to offer a smarter and more intuitive way to search for properties.

Core Features:
--------------
- AI-generated property descriptions
- Semantic search using natural language
- Multimodal search powered by CLIP (image and text)
- Vector storage with ChromaDB
- Personalization layer using LangChain and LLMs
- Interactive UI built with Gradio

----------------------------------------------------

Dependencies:
-------------
- Python 3.9+
- Gradio
- SentenceTransformers
- OpenAI (for CLIP and GPT models)
- LangChain
- ChromaDB (or Weaviate, if configured)
- torch, torchvision
- pandas, numpy, etc.

You can find all dependencies in `requirements.txt`.

----------------------------------------------------

Folder Structure:
-----------------
- HomeMatch.ipynb          → Jupyter notebook for dev/test
- real_estate_listings.txt → Sample property listings (JSON format)
- HomeMatchReadme.txt      → This documentation file
- README.md                → Project overview for GitHub

-------