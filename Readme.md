# **Sentiment Analysis Chatbot**

A **Python-based chatbot** that analyzes user sentiment using a **pre-trained BERT model** and generates appropriate responses based on the detected sentiment.

## **Features**

- Uses **BERT** for sentiment classification.
- Supports **multi-class sentiment detection** (very negative, negative, neutral, positive, very positive).
- Generates **responses tailored** to the user's sentiment.
- Utilizes **NLTK movie reviews dataset** for text processing.

## **Installation**

### **Prerequisites**

Ensure you have **Python 3.7+** installed.

### **Clone the Repository**

```sh
git clone https://github.com/yourusername/sentiment-chatbot.git
cd sentiment-chatbot
```

### **Install Dependencies**

Create a virtual environment (optional but recommended):

```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install required libraries:

```sh
pip install -r requirements.txt
```

## **Usage**

Run the chatbot:

```sh
python main.py
```

You can start chatting, and the bot will analyze sentiment and respond accordingly.

## **Project Structure**

```
sentiment-chatbot/
│── chatbot/
│   │── __init__.py
│   │── sentiment_model.py  # BERT-based sentiment analysis
│   │── response_generator.py  # Generates responses based on sentiment
│── data/  # Stores NLP datasets if needed
│── models/  # Folder to save fine-tuned models
│── tests/  # Contains unit tests
│── main.py  # Entry point to start chatbot
│── requirements.txt  # List of dependencies
│── README.md  # Documentation
│── .gitignore  # Excludes unnecessary files
```

## **Example Interaction**

```
You: I'm feeling great today!
Chatbot (Sentiment: very positive): That's wonderful to hear! What made your day so great?

You: I'm a bit upset about my exams.
Chatbot (Sentiment: negative): I'm sorry to hear that. Do you want to talk about what's bothering you?
```

## **Contributing**

Feel free to open issues and submit pull requests! Follow these steps to contribute:

1. **Fork** the repository.
2. **Create a new branch**: `git checkout -b feature-branch`.
3. **Commit your changes**: `git commit -m "Add new feature"`.
4. **Push to the branch**: `git push origin feature-branch`.
5. **Open a pull request**.

## **License**

This project is licensed under the **MIT License**. See the `LICENSE` file for details.



