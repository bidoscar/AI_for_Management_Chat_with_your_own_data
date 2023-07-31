# AI_for_Management_Chat_with_your_own_data

Large language models or LLMs such as ChatGPT can answer questions about a lot of topics, but an LLM in isolation knows only what it was trained on, which doesn't include your personal data, such as if you're in a company and have proprietary documents not on the internet, as well as data or articles that were written after the LLM was trained. 

So wouldn't it be useful if you or others such as your customers can have a conversation with your own documents and get questions answered using information from those documents and using an LLM? 

Here, we will cover how to use LangChain to chat with your data. 

LangChain is an open-source developer framework for building LLM applications. We will first cover how to use LangChain document loaders to load data from a variety of exciting sources. We will then touch on how to split these documents into semantically meaningful chunks. Next, we'll give an overview of semantic search, a basic method for fetching relevant information given a user question. We'll then show how to use those retrieved documents to enable an LLM to answer questions about a document. Finally, we'll cover the issue of memory, and show how to build a fully functioning chatbot through which you can chat with your data. 
