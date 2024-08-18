## LLM Answer Engine
![per](https://github.com/user-attachments/assets/03b5ba8d-7149-4ee1-8c03-a10a8e842d18)

## Project Overview

This project implements an advanced Answer Engine utilizing Large Language Models (LLMs) to generate intelligent and context-aware responses to user queries.
The LLM Answer Engine is designed to leverage the power of state-of-the-art language models to provide accurate, relevant, and natural-sounding answers to a wide range of questions. This system can be applied in various domains, from educational tools to customer support interfaces.

## Project Description

Welcome to the **LLM Answer Engine** project! This repository provides the code and instructions for building a powerful answer engine leveraging state-of-the-art technologies. The engine is designed to deliver comprehensive responses to user queries, including text, images, videos, and relevant follow-up questions. By integrating cutting-edge tools such as Groq, Mistral AI's Mixtral, Langchain.JS, Brave Search, Serper API, and OpenAI, this project is an excellent resource for developers interested in natural language processing and advanced search functionalities.

![image](https://github.com/user-attachments/assets/6f6d7c39-6890-4d3c-b915-9575fb81110f)


## Technologies Used

- **Next.js**: A React framework for building server-side rendered and static web applications.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Vercel AI SDK**: A library for creating AI-powered streaming text and chat UIs.
- **Groq & Mixtral**: Technologies for processing and understanding queries.
- **Langchain.JS**: JavaScript library for text operations, such as splitting and embeddings.
- **Brave Search**: Privacy-focused search engine for sourcing content and images.
- **Serper API**: Fetches relevant videos and images based on queries.
- **OpenAI Embeddings**: Creates vector representations of text chunks.
- **Cheerio**: HTML parsing library for extracting content from web pages.
- **Ollama (Optional)**: Supports streaming inference and embeddings.

## Getting Started
![image](https://github.com/user-attachments/assets/7dc76855-dd63-4d2e-85af-b163beb301e5)

### Prerequisites

- Node.js and npm installed on your machine.
- API keys from OpenAI, Groq, Brave Search, and Serper.

### Obtaining API Keys

- **OpenAI API Key**: [Generate your OpenAI API key](https://platform.openai.com/signup)
- **Groq API Key**: [Get your Groq API key](https://groq.com/)
- **Brave Search API Key**: [Obtain your Brave Search API key](https://brave.com/search/)
- **Serper API Key**: [Get your Serper API key](https://serper.dev/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/mohankvsnsk/answer-engine-llm.git
    ```

2. Install dependencies:
    ```bash
    npm install
    ```
    or
    ```bash
    bun install
    ```

3. Create a `.env` file in the root of your project and add your API keys:
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key
    GROQ_API_KEY=your_groq_api_key
    BRAVE_SEARCH_API_KEY=your_brave_search_api_key
    SERPER_API=your_serper_api_key
    ```

### Running the Server

To start the server, execute:
```bash
npm run dev
```
or
```bash
bun run dev
```
The server will be running on the specified port.


### Ollama Support (Partially Supported)

Streaming text responses are supported for Ollama. For embeddings and inference, ensure you have the Ollama running model on your local machine and configure it in the settings.

## Backend + Node Only Express API

For a standalone backend version using Node.js and Express, check the `express-api` directory. Detailed setup and running instructions are available in the `express-api/README.md`.

## License

This project is licensed under the MIT License.
## Conclusion

The **LLM Answer Engine** represents a significant step forward in leveraging AI and search technologies to create a robust and versatile answer engine. Whether you're a developer looking to integrate advanced NLP capabilities into your application or simply interested in exploring the potential of these technologies, this project offers a comprehensive starting point. We encourage you to experiment with the features, contribute to the development, and provide feedback to help shape the future of this project. 

## Support

I'm the developer of GEN AI Applications. Learning from YouTube and doing a master's degree in AI and ML algorithms. Follow me in GITHUB for more interesting projects and different domains.
