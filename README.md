# -crypto-trading-dashboard
working crypto bot for coinbase
# Crypto Trading Dashboard

Een Streamlit-app om crypto trading data te visualiseren met RSI en Moving Averages.  
Gebouwd met [ccxt](https://github.com/ccxt/ccxt) en [Streamlit](https://streamlit.io).

## 🚀 Installatie

Clone de repo:

```bash
git clone https://github.com/jouwgebruikersnaam/crypto-trading-dashboard.git
cd crypto-trading-dashboard
pip install -r requirements.txt
streamlit run app.py
# 📊 Crypto Trading Dashboard

Een interactieve **Streamlit-app** om crypto trading data te visualiseren en te analyseren.  
De app gebruikt **RSI** en **Moving Averages** om koop- en verkoopsignalen te genereren en toont grafieken met prijs en indicatoren.

---

## 🚀 Functies
- Verbinding met **Coinbase** via [ccxt](https://github.com/ccxt/ccxt)
- Dynamische keuze van trading pairs (BTC, SOL, XRP, DOGE, ADA)
- Instelbare **timeframes**, **stop-loss** en **take-profit**
- Automatische berekening van beschikbare saldo en maximale trade size
- Grafieken met:
  - Prijs + MA20 + MA50
  - RSI-indicator met overbought/oversold zones
- Koop- en verkoopsignalen op basis van RSI + MA-strategie

---

## 🛠️ Installatie

Clone de repository:

```bash
git clone https://github.com/jouwgebruikersnaam/crypto-trading-dashboard.git
cd crypto-trading-dashboard
