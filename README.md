# RAG-Based-Question-Answering-System
This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain and HuggingFace Transformers. The system allows users to ask questions related to a PDF document, and it provides accurate answers based on the document's content.  

The RAG approach combines:

.Vector Store Search (FAISS) for retrieving relevant document chunks.
I.nstruction-tuned Language Model for generating human-like answers.

Features

. Load and process PDF documents.
. Split text into chunks for efficient retrieval.
.Create embeddings using HuggingFace sentence-transformers.
.Store embeddings in FAISS vector database.
.Accept user queries interactively.
.Generate relevant answers using a HuggingFace instruction model.
.Avoid repeated or redundant answers.
.Fully executable in Google Colab.

Step 1 Installation

<img width="305" height="131" alt="image" src="https://github.com/user-attachments/assets/a41ae20c-7fe5-412b-b262-92461e34a176" />

Step 2 – Imports

<img width="584" height="190" alt="image" src="https://github.com/user-attachments/assets/0c92382c-fc83-4e7a-8e21-424dfd971d2b" />

Step 3 – Load PDF and extract text

<img width="542" height="140" alt="image" src="https://github.com/user-attachments/assets/f9c661df-e396-4886-9294-34bb1cbe29e0" />

Step 4 – Split text into chunks

<img width="403" height="118" alt="image" src="https://github.com/user-attachments/assets/f3a6d3c3-4c00-412d-9015-d9bf74476a43" />

Step 5 – Create embeddings and FAISS vectorstore

<img width="736" height="119" alt="image" src="https://github.com/user-attachments/assets/04404bae-5eeb-49b3-961d-86c45b0afed2" />

Step 6 – Load HuggingFace instruction model

<img width="643" height="346" alt="image" src="https://github.com/user-attachments/assets/c209744d-2907-41ff-8512-3cf56637190b" />

Step 7 – Create RAG QA chain

<img width="661" height="132" alt="image" src="https://github.com/user-attachments/assets/0319410e-9bd2-45a9-9371-11b61bef81a1" />

Step 8 – Ask multiple questions

<img width="403" height="219" alt="image" src="https://github.com/user-attachments/assets/e12603d3-4a68-481a-a62b-a62a2e7cd33a" />

Output

<img width="487" height="94" alt="image" src="https://github.com/user-attachments/assets/6da26955-272c-4768-b22c-2844057e7630" />







