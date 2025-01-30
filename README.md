# Personal-Chatbot

About
This is a simple chatbot built using Python and Natural Language Processing (NLP) techniques. It reads from a text file (Data.txt) and interacts with users by finding the most relevant responses based on their input.

Features
Text Processing: Reads and processes text to make sense of user input.
Tokenization: Breaks down text into smaller parts (sentences and words).
Lemmatization: Reduces words to their base form (e.g., "running" becomes "run") for better response matching.
TF-IDF (Term Frequency-Inverse Document Frequency): Measures the importance of words in the text.
Cosine Similarity: Finds the most relevant response by comparing user input with the chatbot's text corpus.
Random Greetings: Handles simple greetings with friendly responses.
How It Works
Text Processing:

The chatbot reads text from Data.txt, converts it to lowercase, and tokenizes it into sentences and words.
Preprocessing:

Lemmatization is applied to reduce words to their base form.
Punctuation is removed for cleaner input processing.
TF-IDF Vectorization:

The chatbot uses TF-IDF to measure how important a word is in the entire text.
Response Selection:

Cosine similarity is used to compare the user's input with sentences in the text.
The chatbot selects the best matching response based on similarity scores.
Greeting Detection:

If the user says "hello," "hi," or similar phrases, the chatbot responds with a random friendly greeting.
User Interaction:

The chatbot keeps chatting until the user types "bye."
It handles polite farewells like "thanks" with friendly responses.
