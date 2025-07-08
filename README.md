**Speaker1**

A RAG (Retrieval-Augmented Generation) system for document analysis and semantic search using OpenAI and Pinecone.

## 📋 What's Included

- **Document Analysis**: Perform analysis on various document formats using OpenAI's language model.
- **Semantic Search**: Leverage Pinecone's vector database for efficient semantic search and retrieval of relevant documents.
- **Vector Embeddings**: Utilize OpenAI's embeddings to generate dense vector representations of documents.
- **Document Retrieval**: Retrieve relevant documents based on user queries and perform ranking using Pinecone's database.

## 🛠️ Installation

To get started with Speaker1, please install the required dependencies:
```bash
pip install langchain openai pinecone
```

## 📊 Usage

### Setting up the environment

1. Initialize the Pinecone environment by creating an account and setting up your API keys.
2. Install the required dependencies using pip.
3. Configure your OpenAI API keys and Pinecone API keys in the `config.py` file.

### Running the application

1. Run the following command to start the application:
```bash
python app.py
```
2. Use the provided API endpoints to interact with the RAG system.

### Example API Endpoints

- **/search**: Perform a semantic search on a given query.
- **/analyze**: Analyze a document and retrieve its vector embedding.

## 🔧 Technologies

- **Python** - Programming language
- **langchain** - RAG system library
- **openai** - Language model and embeddings library
- **pinecone** - Vector database library

## 📄 License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.