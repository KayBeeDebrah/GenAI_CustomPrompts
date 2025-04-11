# GenAI-Powered Question Answering System for CSV Datasets

This repository showcases a robust question-answering system built using the power of Generative AI. Leveraging LangChain, ChromaDB, and OpenAI's language models, it enables users to extract insightful answers from CSV datasets.

## Features

- **Seamless Data Integration:** Loads and processes CSV datasets containing textual information (e.g., comments, reviews, articles).
- **Intelligent Chunking:** Divides large documents into smaller chunks for efficient embedding and retrieval.
- **Semantic Embeddings:** Utilizes OpenAI's advanced embedding models to convert text into numerical representations capturing semantic meaning.
- **Vector Database Storage:** Stores embeddings in a ChromaDB vector database for lightning-fast similarity search.
- **Retrieval-Augmented Generation (RAG):** Employs a RAG approach to answer questions based on relevant context retrieved from the dataset.
- **Large Language Model Integration:** Integrates with powerful LLMs like GPT-3.5-turbo or GPT-4 for comprehensive answer generation.
- **Customizable Prompting:** Enables tailoring of prompt templates to guide the LLM's behavior and ensure desired responses.
- **Enhanced Result Presentation:** Formats answers for clarity and provides source documents for transparency and verification.

## Installation

1. **Clone the repository:**
2. **Install dependencies:**
3. **Configure OpenAI API key:**
   - Create a `.env` file in the root directory.
   - Add your API key:
   OPENAI_API_KEY=your_api_key

4. **Mount Google Drive (if applicable):**
   - If using Google Colab, follow the provided code to mount your Google Drive and access the dataset.

## Usage

1. **Open the Jupyter Notebook:** Open the provided notebook (e.g., `main.ipynb`).
2. **Run the code cells:** Execute the cells to load the dataset, generate embeddings, and build the question-answering chain.
3. **Ask your questions:** Modify the `question` variable with your queries.
4. **Examine the results:** The system will retrieve relevant information and display the generated answers along with source documents.

## Contributing

Contributions are highly encouraged! If you have ideas for enhancements or encounter any issues, please open an issue or submit a pull request.
