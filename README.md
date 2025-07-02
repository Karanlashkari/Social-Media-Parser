Social Media Parser
A deep learning-powered application to parse and analyze user-generated content from social media platforms like YouTube and Twitter. This tool supports sentiment classification and moderation of online content across various input formats including live tweet streams, tagged tweets, comments, plain text, and text files.

🧠 Model
Model Used: BERT (Bidirectional Encoder Representations from Transformers)

Accuracy: 83% on test data

Purpose: Detect hate speech, toxicity, and sentiment polarity

🔧 Features
Parse YouTube video comments

Analyze tweets by user handle or hashtags

Accept plain text or file-based input

Real-time content moderation using NLP

Sentiment and toxicity classification with transformer-based models

🚀 Tech Stack
Python

Transformers (HuggingFace)

Scikit-learn

Tweepy (for Twitter API)

YouTube API (for comment extraction)

Flask / Streamlit (optional frontend support)

📂 Input Formats
YouTube Video URL

Twitter Username or Hashtag

Raw Text

.txt Files

📊 Output
Classified sentiment: Positive / Negative / Neutral

Hate speech flag: Yes / No

Confidence score for predictions

📝 How to Run
bash
Copy
Edit
git clone https://github.com/Karanlashkari/Social-Media-Parser.git
cd Social-Media-Parser
pip install -r requirements.txt
python app.py
📌 Use Cases
Content moderation for social media platforms

Analyzing user sentiment and engagement

Detecting toxic behavior in community discussions
