# areteCHAT

![DreamShaper_v7_An_etching_of_Arete_was_the_goddess_of_excellen_1](https://github.com/EveryOneIsGross/areteCHAT/assets/23621140/af72ae37-066c-49ef-ab29-356b7562ea0b)

In ancient Greek mythology, Arete was the goddess of excellence and virtue. She personified the highest potential of human character and embodied qualities such as wisdom, courage, justice, and compassion. Inspired by this concept of Arete, areteCHAT leverages the VIA Classification of Character Strengths to build personas that embody the virtues of Arete. Traditionally, the VIA Classification has been used to classify and categorize individuals' character strengths. However, areteCHAT takes a unique approach by using the VIA Classification in reverse. Rather than classifying people into predefined categories, it builds chatbot personas based on the 28 aspects.
By engaging in conversations with the chatbot personas representing different virtues, users have the opportunity to explore and reflect upon these virtues. The chatbot serves as a guide, offering insights, perspectives, and responses that align with the specific virtue's characteristics. 

## Features

- Six Core Virtues: The chatbot persona is based on the six core virtues identified in the VIA Classification of Character Strengths - Knowledge, Courage, Humanity, Justice, Temperance, and Transcendence.
- Context-Aware Conversations: The chatbot maintains the context of the conversation by using all previous messages to generate responses, enabling a more interactive and meaningful conversation.
- Sentiment Analysis: The sentiment of user inputs and bot responses is analyzed using the TextBlob library, providing an understanding of the emotional tone of the conversation.
- Keyword Extraction: Emotion-related keywords are extracted from user inputs using the NLTK library's VADER sentiment intensity analyzer.
- Virtue Selection: The chatbot selects the most relevant virtue based on user input by asking the user to rank the relevance of each virtue on a scale of 1 to 10.
- JSON Data Storage: Conversations, sentiment analysis results, and virtue responses are stored in JSON format, allowing for easy retrieval and analysis of conversation data.


## Prerequisites

- Python 3.7 or higher
- OpenAI API key
- NLTK library
- TextBlob library
- Gradio library

## Setup

1. Clone the repository:

```
git clone https://github.com/your-username/areteCHAT.git
```

2. Install the required libraries:

```
pip install -r requirements.txt
```

3. Set up the OpenAI API key:

   - Create an OpenAI account and obtain an API key.
   - Set the API key as an environment variable (e.g., `OPENAI_API_KEY`).

4. Run the script:

```
python areteCHAT.py
```

5. Access the chatbot interface:

   - Open your browser and navigate to the URL provided in the terminal (e.g., `http://127.0.0.1:7860`).
   - Interact with the chatbot by entering text in the input field.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project utilizes the VIA Classification of Character Strengths developed by Christopher Peterson and Martin Seligman.
- The chatbot implementation is inspired by OpenAI's GPT-4 model and its ChatGPT API.
- The sentiment analysis is performed using the TextBlob library.
- Emotion-related keyword extraction is performed using the NLTK library's VADER sentiment intensity analyzer.
- The Gradio library is used to create the interactive chatbot interface.
