# ChatPDF-AI-Powered-PDF-Chatbot-using-LangChain-and-Google-Generative-AI
ChatPDF: AI-Powered PDF Chatbot using LangChain and Google Generative AI



📜 Overview




ChatPDF is an AI-powered tool that allows you to interact with PDF documents using natural language. With ChatPDF, you can upload one or multiple PDF files, ask questions about their content, and receive accurate answers. It leverages Google Generative AI and LangChain technologies to make PDF data exploration more intuitive and efficient.



🛠️ Key Features
Natural Language Interaction: Easily query PDF content using plain language.
Handles Multiple PDFs: Upload and process multiple PDF files at once.
Accurate Text Chunking: Uses sophisticated text splitting for efficient information retrieval.
Powered by Google Generative AI: Utilizes Google’s advanced AI models for embeddings and question answering.
Vector Store Integration: Implements FAISS for fast and efficient vector-based searching.




💡 How It Works
Upload PDFs: Select one or more PDF files to upload.
Text Extraction: The app extracts and processes the text from each page.
Text Chunking: The extracted text is split into manageable chunks for efficient searching.
Embeddings & Vector Store: The text chunks are converted into embeddings and stored in a FAISS index.
Ask Questions: Enter your question, and the AI retrieves relevant information from the PDFs to provide an accurate response.
📦 Tech Stack
Python: Main programming language
Streamlit: For building the user interface
PyPDF2: For PDF text extraction
LangChain: For handling language model tasks
FAISS: For vector-based text searching
Google Generative AI: For generating embeddings and answering questions
🚀 Getting Started
Prerequisites
Python 3.8+
A Google API Key (For Generative AI services)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/chatpdf-ai.git
Change to the project directory:
bash
Copy code
cd chatpdf-ai
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Set up your Google API Key:
Create a .env file and add your API key:
makefile
Copy code
GOOGLE_API_KEY=your-google-api-key
Running the Application
Run the Streamlit application:
bash
Copy code
streamlit run chatpdf.py


Open your browser and navigate to http://localhost:8501 to start interacting with your PDFs.


🧩 Usage

Upload your PDF files using the sidebar.

Ask any question related to the content of the uploaded PDFs.


The AI model will respond with detailed answers based on the context.




🛠️ Project Structure
bash
Copy code
chatpdf-ai/
│
├── chatpdf.py             # Main application code
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables
└── README.md              # Project README file
🤝 Contributing


Contributions are welcome! If you have any suggestions, feel free to open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🌐 Connect with Us
GitHub Issues: Have a question or suggestion? Let us know!


LinkedIn: https://www.linkedin.com/in/rishabhgupta2696/



📧 Contact
For any inquiries, you can reach out to guptarishabh261996@gmail.com

This README file covers all aspects of the project and makes it clear, informative, and engaging for anyone visiting your repository. Adjust the links and contact information as per your details.







