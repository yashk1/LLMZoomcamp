# Overview

In this module, we will learn what LLM and RAG are and implement a simple RAG pipeline to answer questions about the FAQ Documents from our Zoomcamp courses

What we will do:

* Index Zoomcamp FAQ documents
  * DE Zoomcamp: [https://docs.google.com/document/d/19bnYs80DwuUimHM65UV3sylsCn2j1vziPOwzBwQrebw/edit](https://docs.google.com/document/d/19bnYs80DwuUimHM65UV3sylsCn2j1vziPOwzBwQrebw/edit)
  * ML Zoomcamp: [https://docs.google.com/document/d/1LpPanc33QJJ6BSsyxVg-pWNMplal84TdZtq10naIhD8/edit](https://docs.google.com/document/d/1LpPanc33QJJ6BSsyxVg-pWNMplal84TdZtq10naIhD8/edit)
  * MLOps Zoomcamp: [https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit](https://docs.google.com/document/d/12TlBfhIiKtyBv8RnsoJR6F72bkPDGEvPOItJIxaEzE0/edit)
* Create a Q&A system for answering questions about these documents

## Environment Setup

```
python -m pip install tqdm notebook==7.1.2 openai elasticsearch pandas scikit-learn ipywidgets
```
