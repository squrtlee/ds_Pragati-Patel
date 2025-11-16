# ds_Pragati-Patel
Trader behavior vs market sentiment — EDA and insights

This project analyzes trader behavior using Hyperliquid trade logs combined with the Crypto Fear & Greed Index.  
The goal is to understand:

- How sentiment affects trader profitability  
- Account-level performance patterns  
- Win rate and trade-size relationships  
- Impact of fees on trading outcomes  
- PnL distribution and behavioral insights  

The analysis was performed entirely in Google Colab as per assignment requirements.
Feature Engineering
             - Extracted date, hour, weekday  
             - Merged sentiment (fear/greed index)  
             - Created metrics such as:
             - Profitability flags  
             - Win/loss outcomes  
             - Trade size categories  
             - Normalized PnL  

Exploratory Data Analysis (EDA)
Generated multiple plots including:

            - Closed PnL distribution  
            - Sentiment vs Average Closed PnL  
            - Account-level win rate  
            - Trade size vs win rate  
            - Fee impact on total profitability  
            - Hourly/weekday performance trends  

All graphs are saved in `/outputs`.

Key insights observed:

- Certain traders consistently overtrade and lose due to high fees  
- Market sentiment strongly correlates with PnL  
- Small trade sizes often have higher win rates  
- Big trades amplify volatility & losses  
- Weekday patterns show certain hours with higher losses  

Full summary in **ds_report.pdf**

Dataset Link :Link to dataset
Historical Data
**https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing**
Fear Greed Index link:
**https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing**

Google Colab LInk:
**https://colab.research.google.com/drive/1BZoM5t9LGSQuBBgeWf-6rbA0H0IBS5HG?usp=sharing**
