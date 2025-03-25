# mRAG - Multimodal Retrieval Augmented Generation

## Overview
We'll create a QA system that understands both text and images using **Vertex AI**.

### Focus on Fundamentals:
- We will start with the essential design pattern of **Retrieval Augmented Generation (RAG)**—a way to find and use relevant information to answer questions.
- Expand RAG to handle both **text and images** found in PDF docs.
- Use **Vertex AI Embeddings API** and **Vertex AI Gemini API**.
- By the end, we will have a solid foundation in building **multimodal QA systems**.

## Gemini Model
Gemini is a family of **GenAI models** designed for multimodal use cases.
The **Vertex AI Gemini API** provides access to:
- **Gemini 1.0 Pro Model**
- **Gemini 1.0 Pro Vision Model**
- **Gemini 1.5 Pro Model**
- **Gemini 1.5 Flash Model**

## Comparing Text-Based RAG and mRAG
**Multimodal RAG (mRAG)** offers several advantages over text-based RAG:
- **Enhanced knowledge access**: mRAG can process both textual and visual info, creating a more comprehensive knowledge base.
- **Improved reasoning capabilities**: Incorporating visual cues allows mRAG to make better-informed inferences across data modalities.

## How to Implement RAG
We will implement RAG using:
- **Vertex AI Gemini API**
- **Vertex AI Embeddings API**
- **Text embeddings**
- **Multimodal embeddings** to build a doc search engine.

## Objectives
This project provides a step-by-step guide to building a document search engine using **mRAG**:
1. **Extract and store metadata** of documents containing both text and images.
2. **Generate embeddings** of the documents.
3. **Search metadata** with text queries to find relevant text or images.
4. **Search metadata** with image queries to find similar images.
5. **Retrieve contextual answers** using both text and images for a given query.

## Costs
Using **Vertex AI** comes with associated costs. 
- Refer to the [Vertex AI Pricing Page](https://cloud.google.com/vertex-ai/pricing) for more details.
- Use the [Google Cloud Pricing Calculator](https://cloud.google.com/products/calculator) to estimate costs.

## Repository Structure
```
📂 mRAG_Project
 ├── 📄 LICENSE  # Apache-2.0 License
 ├── 📄 README.md  # Project documentation
 ├── 📄 mRAG.ipynb  # Jupyter Notebook with the implementation
```

## License
This project is licensed under the **Apache-2.0 License**.

---

### Let's build an intelligent **multimodal QA system** using **mRAG**!
