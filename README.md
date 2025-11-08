# Assistant de recherche avec Gemini, LangChain et Chroma

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yassine-grati/Assistant-de-recherche-avec-Gemini-LangChain-and-Chroma/blob/main/Copie_de_IBI2025_RAG_LangGraph.ipynb)
# Assistant de Recherche RAG avec Gemini, LangChain et Chroma

Ce projet est un système **RAG** (Retrieval-Augmented Generation) basé sur :
- **Google Gemini** pour la génération
- **ChromaDB** pour la base vectorielle
- **LangGraph** pour organiser la logique du flux RAG

Il permet de :
✅ Charger des documents PDF  
✅ Indexer automatiquement le contenu en vecteurs  
✅ Réécrire la requête si la recherche échoue  
✅ Vérifier la pertinence des sources  
✅ Générer une réponse fiable

---

## 📌 Fonctionnalités principales

- Découpage intelligent des documents
- Embeddings générés avec Gemini
- Filtrage automatique des documents non pertinents
- Reformulation de requête en cas d’échec
- Pipeline RAG contrôlé par un graphe LangGraph

---

## 🚀 Installation

À exécuter dans Colab ou localement :

```bash
pip install -U langchain-community
pip install langchain-google-genai
pip install chromadb
pip install pypdf
pip install langgraph
