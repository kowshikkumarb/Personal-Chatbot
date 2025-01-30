# Personal-Chatbot

About
A simple chatbot built using Python and Natural Language Processing (NLP) techniques. It reads from a text file (Data.txt) and interacts with users by finding the most relevant responses based on their input.

Features
Text Processing: Reads and processes text to make sense of user input.
Tokenization: Breaks down text into sentences and words.
Lemmatization: Reduces words to their base form (e.g., "running" becomes "run").
TF-IDF (Term Frequency-Inverse Document Frequency): Measures the importance of words in the text.
Cosine Similarity: Finds the most relevant response by comparing user input with the chatbot's text corpus.
Random Greetings: Handles simple greetings with friendly responses.
How It Works
Text Processing: Reads text from Data.txt, converts it to lowercase, and tokenizes it into sentences and words.
Preprocessing: Lemmatizes words and removes punctuation for cleaner input processing.
TF-IDF Vectorization: Measures the importance of words across the text corpus.
Response Selection: Uses cosine similarity to select the best matching response.
Greeting Detection: Recognizes simple greetings and responds accordingly.
User Interaction: Chats until the user types bye. Handles polite responses for thanks.
Code Walkthrough
Dependencies
Python 3.x
Libraries: nltk, numpy, and scikit-learn
Main Components
Corpus Handling: Reads and processes Data.txt for chatbot training.
Preprocessing: Tokenization, lemmatization, and text normalization.
TF-IDF and Cosine Similarity: Measures word importance and response similarity.
Chatbot Loop: Interacts with users until they type bye.
Setup and Usage
Clone the Project:

bash
Copy
Edit
git clone https://github.com/kowshikkumarb/Personal-Chatbot.git
cd Personal-Chatbot
Install Dependencies:

bash
Copy
Edit
pip install nltk numpy scikit-learn
Prepare Data:
Ensure Data.txt contains your text data for the chatbot.

Run the Chatbot:

bash
Copy
Edit
python chatbot.py
Download NLTK Data (if required):

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('wordnet')
Example Interaction
vbnet
Copy
Edit
ROBO: Hello! I'm your chatbot. Type 'bye' to exit.
User: Hello
ROBO: Hi! I'm glad you're talking to me!
User: What is AI?
ROBO: AI stands for Artificial Intelligence, which enables machines to mimic human intelligence.
User: Thanks
ROBO: You're welcome!
