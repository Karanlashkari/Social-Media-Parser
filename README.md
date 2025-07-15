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

Project Images:

![WhatsApp Image 2025-04-19 at 11 48 24_f1adca88](https://github.com/user-attachments/assets/f11fcea5-7729-454b-8fb0-f1b259e0f337)

![WhatsApp Image 2025-04-19 at 11 42 35_f93307c8](https://github.com/user-attachments/assets/b6561afc-cf21-4913-a9b8-1f86bc6c657a)

![WhatsApp Image 2025-04-19 at 11 42 35_4d1379ea](https://github.com/user-attachments/assets/993b55d1-060a-4575-ab54-057cd564c446)

![WhatsApp Image 2025-04-19 at 11 44 42_de8cd582](https://github.com/user-attachments/assets/92a0c389-b6af-434b-b691-fcfeca765897)

![WhatsApp Image 2025-04-19 at 11 44 42_9053f5a3](https://github.com/user-attachments/assets/8bcbe61d-5a66-4df3-89e9-f61768cfb4a6)

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
