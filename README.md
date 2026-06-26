# Supertrend Indicator for Indian Stock Market

## विवरण (Description)

यह एक **TradingView के लिए Pine Script v5** में लिखा गया **Supertrend Indicator** है जो भारतीय शेयर बाजार (NSE, BSE) के लिए optimized है।

## Features ✨

✅ **TradingView में 100% काम करता है**  
✅ **Buy/Sell Signals** - Clear entry और exit points  
✅ **Customizable Parameters** - Period और Multiplier adjust कर सकते हैं  
✅ **ATR-based Calculation** - Volatility के साथ adjust होता है  
✅ **Visual Indicators** - Bands और labels के साथ  
✅ **Alerts** - Buy/Sell signals के लिए notifications  

## कैसे Use करें? 📊

### Step 1: TradingView पर जाएँ
https://www.tradingview.com/

### Step 2: Pine Script जोड़ें
1. **Pine Script Editor** खोलें
2. **+ New** बटन दबाएँ
3. **Indicator** select करें
4. `supertrend.pine` की content को **paste** करें

### Step 3: Script को Chart पर Add करें
1. **Add to Chart** बटन दबाएँ
2. किसी भी Indian stock पर लागू करें
3. **Settings** से Period और Multiplier adjust करें

## Parameters ⚙️

| Parameter | Default | Range | विवरण |
|-----------|---------|-------|--------|
| **Period** | 10 | 1-50 | ATR की calculation के लिए bars की संख्या |
| **Multiplier** | 3.0 | 0.1-10 | Bands की width को control करता है |

## Signals समझें 🎯

| Signal | Color | Meaning |
|--------|-------|----------|
| **BUY** 🟢 | Green | Price supertrend को ऊपर से cross करे |
| **SELL** 🔴 | Red | Price supertrend को नीचे से cross करे |

## Indian Stocks के लिए Recommended Settings 📈

### Intraday Trading (1-5 min)
- **Period:** 8-12
- **Multiplier:** 2.5-3.0

### Swing Trading (Daily/Weekly)
- **Period:** 10-20
- **Multiplier:** 3.0-3.5

### Long Term (Weekly/Monthly)
- **Period:** 20-30
- **Multiplier:** 3.5-4.0

## कैसे काम करता है? 🔧

1. **ATR (Average True Range)** calculate करता है
2. **Upper और Lower Bands** बनाता है
3. **Price** के आधार पर **Trend direction** decide करता है
4. **Crossover/Crossunder** होने पर signals generate करता है

## NSE और BSE के लिए Popular Stocks
- TCS
- Infosys
- HDFC Bank
- Reliance
- ICICI Bank
- Bajaj Auto
- और भी बहुत से...

## License 📄

यह script freely available है। अपनी जरूरत के अनुसार modify करें।

## Support 💬

किसी भी सवाल या suggestion के लिए issue खोलें या GitHub पर contact करें।

---

**Happy Trading! शुभकामनाएँ!** 🚀📊