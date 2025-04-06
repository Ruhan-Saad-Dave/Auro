### **📌 AuroFinance: Gemini Financial Chatbot**  
AURO is a Generative AI-powered financial assistant built to tackle the growing challenge of financial illiteracy in India. While millions of new investors are entering the markets, access to personalized, trustworthy financial guidance remains scarce. Traditional approaches simply cannot scale to support this massive influx.

We aim to bridge this gap using the power of GenAI.

AURO allows users to converse naturally about their financial goals, whether it's understanding stock market trends, evaluating investment options, or learning about loan structures. Auro powered by transformer-based deep learning models, AURO delivers data-driven, educational, and personalized financial guidance at scale—no human advisors needed.

Our vision is to revolutionize financial decision-making in India by making financial literacy accessible, actionable, and conversational for every investor.

---

### **🔹 Features (Updated for Financial Literacy & Decision-Making)**  
- 📈 Fetch historical financial data: Stocks, currencies, crypto, and commodities (gold, silver, copper, platinum) to help users analyze trends.
- 🔮 Stock price prediction & insights: Uses transformers to forecast stock prices and provides educational explanations on market factors affecting the trend.
- 💹 Intraday stock price & prediction: Tracks real-time intraday data and delivers short-term forecasts to aid day traders and active investors.
- 🏢 Company stock info retrieval: Displays stock details along with financial ratios (P/E ratio, dividend yield, etc.) to help users evaluate investments.
- 📰 News sentiment analysis: Analyzes news articles and social media to provide sentiment scores for a specific stock, company, or financial topic.
- 📊 Top 10 daily gainers and losers: Offers a summary of why certain stocks are moving up or down and educates users on market volatility.
- 🏦 Loan and mortgage calculator: Computes monthly payments, total costs, and interest, while explaining financial concepts like APR and amortization.
- 🎓 Financial literacy tips: Provides AI-powered insights on investment strategies, risk management, and wealth-building habits.
- 💡 Smart decision assistance: Offers personalized financial advice based on the user's profile, risk appetite, and market conditions.
- 🗣️ Speech-to-text & multilingual support: Users can interact using voice and receive input/output in multiple languages, enhancing accessibility.

---

### **🚀 Getting Started**  

#### **1️⃣ Installation**  
```bash
git clone https://github.com/Ruhan-Saad-Dave/Auro.git
cd Auro
```
If you are using windows (CMD, not powershell):
```bash
python -m venv myenv
myenv\Scripts\activate
```
And for MAC and Linux
```bash
python -m venv myenv
source myenv/bin/activate
```
Then downloading the dependencies:
```bash
pip install -r requirements.txt
```

#### **2️⃣ API Setup**  
In order to setup the API keys, create a .env file and write the following details:  
```bash
GEMINI_API_KEY="Your_Gemini_Api_Key"
ALPHA_API_KEY="Your_Alpha_Vantage_Api_Key"
CLOUDINARY_CLOUD_NAME="Your_Cloudinary_Cloud_Name"
CLOUDINARY_API_KEY="Your_Cloudinary_Api_Key"
CLOUDINARY_API_SECRET="Your_Cloudinary_Api_Secret"
```

#### **3️⃣ Running the Bot**  
For windows:
```bash
python app.py
```
For Mac/Linux:
```bash
python3 app.py
```
From here you should get some links which will redirect you to the gradio interface which contains the chatbot.
---
