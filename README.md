## 🧠 Physics RAG System (Wikipedia-based)

A lightweight **Retrieval-Augmented Generation (RAG)** system for physics concepts using Wikipedia as an external knowledge source.
This project demonstrates how to build a domain-focused AI assistant without relying on paid APIs.

##🔗 **Live Demo(Hugging Face Space):**
https://sncarenyang-physics-rag-demo.hf.space/


___


## 🔍 Features
 - 🔎 Wikipedia-based retrieval (English)
 - ⚛️ Physics-focused concept answering
 - 🧠 TF-IDF semantic similarity ranking
 - 🧾 Clean and simple UI (Gradio)
 - 💡 Guided user queries for better accuracy



## 🧩 Tech Stack
 - **Python**
 - **Gradio**
 - **Scikit-learn(TF-IDF, cosine similarity)**
 - **Wikipedia API**



## 🚀 Installation & Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/physics-rag-wiki-demo.git
cd physics-rag-wiki-demo

pip install -r requirements.txt
python app.py


## 📚 Project Structure

physics-rag-wiki-demo/
├── app.py                    # Gradio UI & Main application
├── requirements.txt          # Python dependencies
└── README.md                 # Project Documentation
```

## ⚙️ How It Works
 1. User inputs a physics-related query (e.g., “Entropy”, “Spacetime”)
 2. The system retrieves relevant information from Wikipedia
 3. TF-IDF is used to rank similarity (fallback if needed)
 4. The best result is returned to the user



## 💡 Design Decisions
 -  The system guides users to input physics-related terms in English
 -  This reduces ambiguity in Wikipedia search results 
 -  Improves response accuracy without complex NLP models



## ⚠️ Limitations
- Not a full conversational AI
- Depends on Wikipedia availability
- Works best with predefined physics concepts



## 🔮 Future Improvements
- Add domain classification (physics vs medical)
- Integrate LLM for better summarization
- Support multilingual output
- Improve retrieval ranking



## 👩‍💻 Author
Shi-Ning Caren Yang



## ⭐ Highlights
- Built without paid APIs (cost-efficient AI system)
- Demonstrates real-world RAG pipeline
- Includes debugging and retrieval optimization



## 📌 Disclaimer
This project is for educational and demonstration purposes only.


## 🌐 License & Copyright
-  The code in this repository is released under the MIT License (or the license you choose).
-  The Wikipedia content retrieved via this demo is subject to Wikipedia’s own license and copyright terms.


## 📚 Acknowledgements
-  Thanks to **Hugging Face Space** for providing the free deployment platform.
-  Contributions are welcome



