# Financial news sentiment classifier

In this task, I worked on a machine learning model that can classify the sentiment of a given financial news into three basic categories: positive, neutral, negative. More specifically, I fine-tuned the GPT-2 open source model with a Kaggle dataset containing 4673 news articles from BBC news. In result, I achieved 80% accuracy in f1 score.

## ~ To interact with the ML model ~

1. Download the repository with 
```bash
git clone https://github.com/bbadraa99/Sentiment_analyzer.git
```
2. Create your own Python virtual environment

```bash
python3 -m venv myenv
```
   - Activate your virtual env with
    - Windows: run "myenv\Scripts\activate"
    - Mac / OS: run "source myenv/bin/activate"
3. Run the program
    - Download Flask: 
      ```bash
      python3 -m pip install fastapi transformers uvicorn
      ```
    - Run the program
      ```bash
      python3 main.py
      ```
4. Interact with the model
   - Go to http://localhost:3000/ 
   - Type your financial news
     - Examples: (Generated by ChatGPT)
       - Global stock markets saw modest gains today as investors grew optimistic about central banks' potential easing of interest rates, following signs of slowing inflation in key economies. Analysts remain cautiously optimistic as inflation levels appear to stabilize. 
       - Oil prices rose sharply after OPEC announced a surprise cut in production, aiming to stabilize global energy markets. The reduction has raised concerns over rising fuel costs, with potential ripple effects on inflation worldwide.
       - Major tech stocks bounced back today after several companies posted better-than-expected earnings for the quarter. Investors welcomed the positive results, boosting confidence in the sector despite broader economic uncertainties.

            ### ~Thank you for your attention~
