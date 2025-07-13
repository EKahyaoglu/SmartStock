# SmartStock 🧠📈

An AI-powered tool that is designed to provide recommendations on the stock market by utilizing a combination of traditional financial indicators and modern portfolio theory models. SmartStock leverages the power of Large Language Models (LLMs), particularly that of OpenAI, to analyze key performance indicators (KPIs) and provide actionable recommendations.

## 👀 What does it do?
* **Calculates** and **visualizes** popular *KPIs* like *RSI*, *Bollinger Bands*, and *MACD* for specific stocks
* Looks at the *Price-to-Earnings (P/E) ratio* to help you understand how a stock is valued
* Checks each stock’s *Beta* to show how risky or volatile it is compared to the overall market
* Uses **GPT-4o** to summarize the data and give you clear, easy-to-understand investment insights
* Helps you take steps toward an optimized portfolio by maximizing the **Sharpe Ratio** for better returns at a given level of risk
* Allows you to add your own views with the **Black-Litterman model** to create a more customized and balanced portfolio

## 🖥️ Technologies Used

- **Python** – Main programming language utilized
- **yfinance** – To fetch historical stock data
- **PyPortfolioOpt** – For portfolio optimization using MPT and Black-Litterman models
- **langchain-openai** – To interact with OpenAI's language models
- **Matplotlib** – To create visualizations
- **NumPy & Pandas** – For data manipulation and analysis.

## ⚠️ Disclaimer
SmartStock is a research and educational tool. It uses AI-generated analysis, which could potentially include inaccuracies or outdated information. This project does not offer financial advice and should not be used to make investment decisions. Always consult a qualified financial advisor or professional before making any financial decisions or ventures.

## 📁 Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/EKahyaoglu/SmartStock.git
   cd SmartStock
   ```

2. **Open the .ipynb notebook** in your preferred environment:
   - Jupyter Notebook
   - JupyterLab
   - Google Colab
   - Visual Studio Code (VS Code)

3. **Replace api_key with your OpenAI API Key**:
   ```python
   api_key = "YOUR_API_KEY"
   ```
  You can create an OpenAI API Key on https://platform.openai.com.

4. **Run the cells** and start exploring your stock insights!
   
