# Hi, I'm Van Khoi

AI Student at the HCM University of Science (HCMUS), passionate about building multimodal AI applications and practical machine learning systems.

### 🎯 Interests

* Multimodal AI
* Computer Vision
* Large Language Models & RAG Systems
* Speech Processing
* Generative AI & Natural Language Processing

### 🛠️ Technologies

**Programming:** Python, C++, SQL  
**Machine Learning & Frameworks:** PyTorch, TensorFlow/Keras, Scikit-learn, Hugging Face Transformers, OpenCV, ONNX  
**LLM, NLP & Speech:** XLM-RoBERTa, PhoBERT, Ollama, Groq API (Llama 3.1), Whisper, Librosa, Prompt Engineering  
**Multimodal & Vision:** SigLIP-2, Florence-2, CLIP, YOLOv5, InceptionResNetV2  
**Databases, Search & Backend:** FAISS, SQLite, Firebase, FastAPI, RESTful APIs, BM25, Reciprocal Rank Fusion (RRF)  
**Tools & Deployment:** Git, GitHub, Gradio, Cloudflare Tunnel, Unity  

### 🚀 Featured Projects

#### AIC Multimodal Video Retrieval System
* Built a multimodal video retrieval pipeline processing Vietnamese natural-language queries, integrating SigLIP-2 visual embeddings, Florence-2 OCR/captions, and Whisper Large-v3 speech transcripts.
* Engineered a hybrid fusion retrieval engine combining FAISS vector search, BM25, and RapidFuzz fuzzy matching via weighted Reciprocal Rank Fusion (RRF).
* Implemented an LLM-based query decomposer (Llama 3.1) with a custom temporal dynamic programming alignment algorithm for multi-event sequences, deployed on Gradio.

#### AR Campus RAG Chatbot — HCMUS
* Developed a FastAPI-based Vietnamese campus assistant utilizing a multi-agent architecture to route queries across facility, navigation, and FAQ services powered by Ollama.
* Trained a joint intent classification and slot tagging model using an XLM-RoBERTa backbone to extract building and room entities.
* Designed an entity linking module pairing a fine-tuned PhoBERT classifier with RapidFuzz fuzzy matching, equipped with conversation memory, SQLite persistence, and Cloudflare Tunnel integration.

#### Speech Emotion Recognition
* Engineered an end-to-end classification pipeline mapping speech audio into five emotional categories across multi-source datasets.
* Extracted 193-dimensional acoustic features (MFCC, Chroma, Mel-spectrogram, Spectral Contrast, Tonnetz) via Librosa with audio data augmentation.
* Trained and benchmarked multiple classifiers, including Decision Trees, Extra Trees, KNN, and deep neural networks in Keras/TensorFlow.

#### AI-Powered License Plate Detection System
* Built a license plate localization and recognition pipeline, comparing InceptionResNetV2 bounding-box regression with YOLOv5.
* Exported the trained YOLOv5 detector to ONNX and TorchScript for lightweight inference.
* Integrated Pytesseract OCR to extract plate characters, served via an API-based web service.

### 📫 Contact

* **GitHub:** [@Khoi-Tu-2303](https://github.com/Khoi-Tu-2303)
* **Email:** 24122019@student.hcmus.edu.vn
