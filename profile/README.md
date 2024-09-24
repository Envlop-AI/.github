# 📧 Envelope AI

**Envelope AI** is an intelligent email management system that utilizes **Python**, the **Gmail API**, and **OpenAI's API** to revolutionize the way you handle your inbox. Say goodbye to sifting through dozens or even hundreds of emails. With Envelope AI, your emails are automatically categorized, prioritized, and summarized, ensuring you never miss anything important. The system also goes a step further by learning from your email habits to help generate more efficient and personalized email responses.

---

## 🌟 Features

- **Email Prioritization**: Automatically ranks emails by importance.
- **Category Sorting**: Groups emails into relevant categories such as work, personal, promotions, etc.
- **Smart Summarization**: Provides concise summaries of emails, saving you time and effort.
- **Custom Email Generation**: Learns from your past emails and writing style to help draft more effective and efficient responses.
- **Integration with Gmail API**: Uses Gmail's API to securely access your inbox.
- **OpenAI-powered Intelligence**: Utilizes OpenAI's GPT models to analyze and summarize your emails and assist in email generation.

---

## 🚀 Technologies Used

- **Python**: The core language for building Envelope AI.
- **Gmail API**: Used to retrieve, send, and organize emails directly from your Gmail account.
- **OpenAI GPT API**: Powers the AI-driven summarization, categorization, and email generation functionalities.
- **FAST API**: For setting up the web interface.
- **OAuth 2.0**: Secure authentication for Gmail integration.
- **SQLite**: Database to store learned user preferences and email history locally.
- **Pandas**: For organizing and managing email data.
- **Natural Language Processing (NLP)**: NLP techniques to improve text analysis and classification.

---

## 🛠️ How It Works

1. **Step 1: Authentication**  
   Envelope AI connects to your Gmail account using the Gmail API, securely authenticating with OAuth 2.0.

2. **Step 2: Email Retrieval & Categorization**  
   Once authenticated, the system fetches your recent emails and categorizes them into groups like "Work," "Personal," "Promotions," etc.

3. **Step 3: Prioritization**  
   Emails are automatically sorted by their priority levels using an AI-based ranking system that considers factors such as sender, content, and your interaction history.

4. **Step 4: Summarization**  
   Each email is summarized into a short, easy-to-digest snippet, so you can quickly understand the gist without reading the full message.

5. **Step 5: Email Generation**  
   Envelope AI learns your writing style and preferences, offering personalized email drafts that you can approve and send with minimal effort.
