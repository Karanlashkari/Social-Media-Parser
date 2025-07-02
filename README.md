Social Media Parser
A deep learning-powered application that parses and analyzes user-generated content from platforms like YouTube and Twitter. This system supports sentiment analysis and hate speech detection using transformer-based NLP models.

🧠 Models Used

BERT (base-uncased) – For general sentiment classification

BERTweet – Fine-tuned for Twitter-specific language and slang

DistilBERT – Lightweight alternative for faster inference

Logistic Regression / SVM – Classical baselines for comparison

All models were evaluated using standard metrics (accuracy, F1-score), with BERTweet achieving up to 83% accuracy on social media text classification.

📊 NLP Tasks

Sentiment Classification – Positive / Negative / Neutral

Hate Speech Detection – Binary classification (Hate / Safe)

Toxicity & Abusive Language Detection

Named Entity Recognition (Optional extension)

📚 Dataset

TweetEval Benchmark

Multi-task benchmark dataset for sentiment, hate, and offensive language detection.

HateXplain

Annotated dataset focused on hate speech detection with rationales.

YouTube Comment Dataset (custom parsed)

🔧 Features

Parse YouTube comments using video URL

Analyze Twitter data via username or hashtag

Accepts raw text input or text file uploads

Clean UI interface (Flask or Streamlit optional)

🚀 Tech Stack

Python

Transformers (HuggingFace)

Tweepy – Twitter API integration

YouTube Data API – Comment extraction

Scikit-learn, Pandas, Numpy

Flask / Streamlit – Web Interface

🧪 How to Run

bash
Copy
Edit

git clone https://github.com/Karanlashkari/Social-Media-Parser.git
cd Social-Media-Parser
pip install -r requirements.txt
python app.py
📁 Input Formats
YouTube video URL

Twitter handle or hashtag

Plain text (via input box)

.txt file (multi-line input)

🧾 Output

Classified Sentiment: Positive, Negative, Neutral

Hate Speech Flag: Yes / No

Confidence Scores

Optional: Export report in CSV/JSON format

✅ Use Cases

Social media content moderation

Brand reputation & sentiment analysis

Analyzing online communities or campaign feedback

Academic NLP research and prototyping
