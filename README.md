# Insurance Documents RAG QA Chatbot  
Effortless Question Answering on Insurance Documents Powered by LlamaIndex and OpenAI Models  

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)  

---  

## ✨ About the Project  
The Insurance Documents RAG QA Chatbot is a smart solution for answering queries related to insurance documents. It simplifies the interpretation of dense and complex policies by integrating retrieval and generation techniques to provide accurate and contextual answers in real time.  

---  

## 🔍 Key Features  
- 🌟 **Precise Responses**: Employs a Retrieval-Augmented Generation (RAG) pipeline for highly relevant answers.  
- ⚡ **Efficient Embedding Management**: Utilizes **ChromaDB** for scalable and fast embedding storage and retrieval.  
- 🧠 **AI-Driven Answers**: Combines LlamaIndex retrieval with OpenAI GPT-4o-mini/GPT-4o for user-centric response generation.  
- 🛠️ **Caching Layers**:  
  - **Embedding Cache**: Prevents re-embedding of identical documents for optimal performance.  
  - **Query Cache**: Skips redundant searching for previously answered queries.  
- 📄 **Dynamic Document Processing**: Splits documents into smaller chunks for efficient query-based retrieval.  
- 🤖 **Interactive User Experience**: Seamlessly retrieves relevant information and generates concise answers.  

---  

## 🛠️ Tech Stack  
- **Language**: Python  
- **Frameworks/Libraries**: LlamaIndex, ChromaDB, DiskCache 
- **APIs/Models**:  
  - OpenAI's Embedding Model for vector creation  
  - LlamaIndex for document ingestion and querying  
  - GPT-4o-mini/GPT-4o for final response generation  

---  

## 🧪 Example Use Cases  
- "What is covered under this insurance policy?"  
- "What is the claim settlement process for my policy?"  

---

## 📸 Sample Output
### 1. Sample Code Output
![Sample Code Output](Sample%20Code%20output%20Screenshots/Sample%20Code%20output%201.png)

### 2. Sample Code Output Cache Response
![Sample Code Output Cache Response](Sample%20Code%20output%20Screenshots/Sample%20Code%20output%202.png)

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation
1. Clone the repo:
git clone https://github.com/SandeepGitGuy/Insurance_Documents_QA_Chatbot_RAG_LlamaIndex.git

2. Navigate to the project directory:
cd Insurance_Documents_QA_Chatbot_RAG_LlamaIndex

3. Install the required dependencies:
pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function.

4. Run the main file from Jupyter environment:
"Insurance_Doc_llamaindex_RAG.ipynb"

---

## 🛠️ Challenges/Issues Addressed  
1. **Optimized PDF Parsing**: Enhanced extraction and chunking using Llamaindex's Ingestion pipeline for seamless data ingestion.  
2. **Embedding Efficiency**: Added an embedding cache to reduce redundant embeddings in ChromaDB.  
3. **Query Optimization**: Integrated a query cache to prevent duplicate searches and improve response times.  
4. **Enhanced Passage Ranking**: Introduced a reranker for better relevance in retrieved sections.  
5. **Dynamic Embedding Updates**: Leveraged OpenAI's embedding model for high-quality vector representation.  

---  

## 🚀 Future Scope  
- Extend support for multi-lingual document processing and querying.  
- Add compatibility for non-PDF formats like Word or Excel files.  
- Integrate additional generative models like Claude AI for diverse response generation.  

---  

## 📖 Documentation  
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:  
- [LlamaIndex](https://llamaindex.ai/docs/)  
- [OpenAI](https://platform.openai.com/docs/)  
- [ChromaDB](https://docs.trychroma.com/)
- [DiskCache](https://pypi.org/project/diskcache/)

---  

## 🛡️ Conclusion  
The Insurance Documents RAG QA Chatbot bridges the gap between users and complex insurance policies by delivering precise, contextual responses. With robust caching, efficient embeddings, and intelligent document querying, it ensures a seamless experience for policyholders and professionals alike.  

---  

## 🛡️ License  
Distributed under the MIT License. See `LICENSE` for more information.  

---  

## 💬 Contact  
For any queries or feedback, reach out via:  

- **Email**: sandy974278@gmail.com
- **GitHub**: https://github.com/SandeepGitGuy
- **LinkedIn**: www.linkedin.com/in/sandeepgowda24a319192

---
