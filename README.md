
---

# **ChatPDF: AI-Powered PDF Chatbot using LangChain and Google Generative AI**

## 📜 **Overview**
ChatPDF is an AI-powered tool that allows you to interact with PDF documents using natural language. With ChatPDF, you can upload one or multiple PDF files, ask questions about their content, and receive accurate answers. It leverages Google Generative AI and LangChain technologies to make PDF data exploration more intuitive and efficient.

## 🛠️ **Key Features**
- **Natural Language Interaction**: Easily query PDF content using plain language.
- **Handles Multiple PDFs**: Upload and process multiple PDF files at once.
- **Accurate Text Chunking**: Uses sophisticated text splitting for efficient information retrieval.
- **Powered by Google Generative AI**: Utilizes Google’s advanced AI models for embeddings and question answering.
- **Vector Store Integration**: Implements FAISS for fast and efficient vector-based searching.

## 💡 **How It Works**
1. **Upload PDFs**: Select one or more PDF files to upload.
2. **Text Extraction**: The app extracts and processes the text from each page.
3. **Text Chunking**: The extracted text is split into manageable chunks for efficient searching.
4. **Embeddings & Vector Store**: The text chunks are converted into embeddings and stored in a FAISS index.
5. **Ask Questions**: Enter your question, and the AI retrieves relevant information from the PDFs to provide an accurate response.

## 📦 **Tech Stack**
- **Python**: Main programming language
- **Streamlit**: For building the user interface
- **PyPDF2**: For PDF text extraction
- **LangChain**: For handling language model tasks
- **FAISS**: For vector-based text searching
- **Google Generative AI**: For generating embeddings and answering questions

## 🚀 **Getting Started**

### **Prerequisites**
- Python 3.8+
- A Google API Key (For Generative AI services)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chatpdf-ai.git
   ```
2. Change to the project directory:
   ```bash
   cd chatpdf-ai
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up your Google API Key:
   - Create a `.env` file and add your API key:
     ```
     GOOGLE_API_KEY=your-google-api-key
     ```

### **Running the Application**
1. Run the Streamlit application:
   ```bash
   streamlit run chatpdf.py
   ```
2. Open your browser and navigate to `http://localhost:8501` to start interacting with your PDFs.

## 🧩 **Usage**
- Upload your PDF files using the sidebar.
- Ask any question related to the content of the uploaded PDFs.
- The AI model will respond with detailed answers based on the context.

## 🛠️ **Project Structure**
```
chatpdf-ai/
│
├── chatpdf.py             # Main application code
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables
└── README.md              # Project README file
```

## 📹 Demo Video           

[Demo Video]  (https://youtu.be/2lUpNpEhEck](https://youtu.be/wtqqPsIQ2vs)


## 🤝 **Contributing**
Contributions are welcome! If you have any suggestions, feel free to open an issue or submit a pull request.



## 🌐 **Connect with Us**
- [GitHub Issues](https://github.com/rishabh261996): Have a question or suggestion? Let us know!
- [LinkedIn](https://www.linkedin.com/in/rishabhgupta2696/): Connect with us for updates.

## 📧 **Contact**

For any inquiries, you can reach out to [your-email@example.com](guptarishabh261996@gmail.com).

---

This README file covers all aspects of the project and makes it clear, informative, and engaging for anyone visiting your repository. Adjust the links and contact information as per your details.
