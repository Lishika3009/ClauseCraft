# ClauseCraft – AI-Powered Legal Assistant with CrewAI, RAG, Streamlit, Tavily, and VectorDB

An intelligent AI legal assistant that understands legal issues, researches relevant laws, and generates tailored legal documents using advanced AI and retrieval-augmented generation.

---

## ✨ Features

### **Advanced Legal Issue Understanding**
- Utilizes CrewAI agents and natural language processing to classify a wide range of legal issues based on user input.
- Supports nuanced queries and complex legal contexts.

### **Automated Legal Research**
- Integrates Tavily search and RAG pipeline to efficiently retrieve relevant legal sections, statutes, and precedent cases.
- Searches across legal databases and indexed documents in VectorDB.

### **Generative Legal Document Drafting**
- Automatically generates tailored legal documents such as:
  - Contracts
  - Agreements
  - Petitions
- Uses generative AI to adapt tone, jurisdiction, and clauses to user requirements.

### **Streamlit Web Interface**
- User-friendly interface for interacting with the assistant.
- Upload or type queries, select document type, and receive instant outputs.

---

## 🏗 Architecture

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/fa1ea5f6-2f00-4518-8ea3-7ebccb41ae07" />

*The system uses CrewAI to orchestrate specialized agents for classification, retrieval, and drafting. A VectorDB enables RAG-based legal research, and the Streamlit UI allows users to interact with the assistant seamlessly.*

---

## 🔧 Installation

**Clone the repository:**
```bash
git clone https://github.com/Lishika3009/ClauseCraft.git
cd ClauseCraft
````

**Install dependencies:**

```bash
pip install -r requirements.txt
```

**Set up environment variables:**
Create a `.env` file in the root folder with:

```
GROQ_API_KEY=your_groq_api_key_here
TAVILY_API_KEY=your_tavily_api_key_here
IPC_JSON_PATH=path_to_your_ipc.json
PERSIST_DIRECTORY_PATH=path_to_your_chroma_vectordb_directory
IPC_COLLECTION_NAME=ipc_collection
```

**Workflow:**

1. Enter your legal query.
2. Select analysis type: legal issue classification, research, or drafting.
3. Receive structured output with references and downloadable legal documents.

---

## 🔍 Analysis Types

* **Legal Issue Classification:** Categorizes user queries into legal domains.
* **Legal Research:** Finds relevant statutes, precedents, and sections.
* **Document Drafting:** Generates customized legal documents.
* **Combined Analysis:** End-to-end classification → research → drafting.

---

## 🔧 Technical Stack

* **Backend:** CrewAI, LangChain, FastAPI
* **Document Retrieval:** RAG pipeline with VectorDB
* **Search:** Tavily API
* **Frontend:** Streamlit
* **AI Models:** GPT-4 / LLaMA 3 via API integrations

---

## 🚀 Future Enhancements

* Real-time legal Q\&A
* Multi-language legal support
* Calendar and deadline integration for case tracking
* Advanced legal analytics and risk assessment
* Integration with government legal APIs


