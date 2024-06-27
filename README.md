# LLMZoomcamp

Deploying LLM and RAGs in production

## Project

we build a RAG prototype in Jupyter Notebook. No wheel will be re-invented. The search enginee will be [ElasticSearch](https://www.elastic.co/elasticsearch), the document will be the [FAQs collection](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/01-intro/documents.json) of all DataTalks.Club courses, and the LLM will be Groq API

Looking forward, the future of generative AI lies in creatively chaining all sorts of LLMs and knowledge bases together to create new kinds of assistants that deliver authoritative results users can verify.

## Week 0 (workshop) - Build a Q&A system for course-related FAQ documents

The LLM RAG Workshop covered the integration of Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG). It includes setting up the environment, running ElasticSearch for document indexing and retrieval, and generating answers using OpenAI. The extended workshop features using Ollama, Docker-Compose, Streamlit for web interfaces, and open-source models from HuggingFace. The practical goal is to build a Q&A system for Zoomcamp FAQ documents, enhancing the understanding and application of LLM and RAG technologies.

## Week 1

In this module, we will learn what LLM and RAG are and implement a simple RAG pipeline to answer questions about the FAQ Documents from our Zoomcamp courses

What we will do:

* Index Zoomcamp FAQ documents
  * DE Zoomcamp: [https://docs.google.com/document/d/19bnYs80DwuUimHM65UV3sylsCn2j1vziPOwzBwQrebw/edit](https://docs.google.com/document/d/19bnYs80DwuUimHM65UV3sylsCn2j1vziPOwzBwQrebw/edit)
  * ML Zoomcamp: [https://docs.google.com/document/d/1LpPanc33QJJ6BSsyxVg-pWNMplal84TdZtq10naIhD8/edit](https://docs.google.com/document/d/1LpPanc33QJJ6BSsyxVg-pWNMplal84TdZtq10naIhD8/edit)
  * MLOps Zoomcamp: [https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit](https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit)
* Create a Q&A system for answering questions about these documents
