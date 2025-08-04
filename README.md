# 🧠 RAG Check Symptom: Healthcare Assitant
**Description:**
The RAG Check Symptom is an AI app that uses Retrieval-Augmented Generation (RAG) with LangChain, embeddings vetoriais e OpenAI to identify patient sickness based on the symptoms. 

<img width="640" height="262" alt="image" src="https://github.com/user-attachments/assets/d1f379a3-668a-45d2-b2ff-0665a9bf80da" />


---

## 🚀 Functionality

- Streamlit Interface to interaction
- Dataset of sickness and symptoms vectorized
- Answer generation with LangChain + OpenAI
---

## ⚙️ Stack
- Embeddings --> OpenAIEmbeddings 
- VetorStore --> Chroma
- LLM --> OpenAI
- Framework --> RAG	LangChain
- Frontend --> Streamlit
- Backend --> Python


---

## 📦 Install 
- git clone https://github.com/miranda-santos-ricardo/rag_check_symptom/
- cd rag_check_symptom
- virtualenv venv
- .\venv\Script\activate (windows machine)
- pip install -r requirements.txt
- streamlit run app.py
- Note: don't forget to add you OPENAI_API_KEY in the .env file




