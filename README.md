Retrieval Learning Bot
This project implements a simple retrieval-based chatbot using Python and the NLTK library. The bot is designed to respond to user queries based on a provided text document.

The core functionality includes:

Text Preprocessing: Lowercasing, tokenization, and lemmatization of the input text and user queries using NLTK.
TF-IDF Vectorization: Converting text data into numerical representations using Term Frequency-Inverse Document Frequency (TF-IDF).
Cosine Similarity: Calculating the similarity between the user's query and the sentences in the text document to find the most relevant response.
The bot can handle greetings, specific keywords related to "wikipedia", and provides a default response if a relevant match is not found.

To use the bot, run the script and type your questions or greetings. Type 'bye' or 'thank you' to end the conversation.
