# Space Law Chatbot

## Objective of the chatbot

The objective of this chatbot is to serve as a virtual legal assistant for space law rules and regulation-related queries. The chatbot is trained on the space laws and regulations legislated by the UNOOSA. The dataset is divided into four documents United Nations treaties, Principles adopted by the General Assembly, Related resolutions adopted by the General Assembly and Other documents. These documents are in the form of pdf which are fed to the model. On this data following libraries perform the operations:

### Langchain
* Langchain serves as the foundation for implementing NLP functionalities, including text analysis, query processing, and response generation for the space law chatbot.
* The output is based on the dataset(Laws) provided to the model in form of pdf. Langchain is used to load and process PDF files containing space laws. It provides functionalities like document loading, text processing, and indexing.

### VectorStore
VectorStore DB complements Chroma DB by storing vector embeddings of space law documents. It facilitates similarity search operations, allowing the chatbot to find relevant documents or passages based on semantic similarity to user queries.


### OpenAI 
OpenAI API key is utilized to access OpenAI's language models, these models are leveraged for tasks such as generating responses to user queries and understanding natural language. 

## Accuracy achieved : 98.09%


## Output

![WhatsApp Image 2024-03-11 at 17 35 52](https://github.com/samiksha-badgujar/Space-Law-Chatbot/assets/126308884/b428f1b5-4803-4606-bb0b-fbc73ecf8c47)

![WhatsApp Image 2024-03-11 at 17 37 07](https://github.com/samiksha-badgujar/Space-Law-Chatbot/assets/126308884/81e0ad72-4afc-4060-b630-43d69984eb7e)

![WhatsApp Image 2024-03-11 at 17 36 39](https://github.com/samiksha-badgujar/Space-Law-Chatbot/assets/126308884/3f82f8b1-f86c-4162-9fbe-7f1fb1dbb40f)
