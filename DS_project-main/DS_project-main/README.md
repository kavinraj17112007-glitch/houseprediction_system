<div align="center">

# 🏠 House Price Predictor

### An AI-Driven, Sentiment-Weighted Real Estate Price Estimation Dashboard

**Subject: Data Science**

# Our Team
  ### D. Akshaya - 2420030474 ###
 ### D. Aarya Deeksha - 2420030530 ###
 ### A. Rishitha - 2420030541 ###

🔗 **[View Live Project →](https://celebrated-pastelito-238b4d.netlify.app/)**

</div>

---

## About the Project

**House Price Predictor** is a Data Science mini-project that estimates Indian residential property prices in **INR**, built around the idea of combining structured real-estate data with **sentiment analysis** of market mood. Instead of relying purely on numeric inputs like a traditional calculator, this project simulates how a real-world pricing model would factor in buyer sentiment, locality trends, and property characteristics together to arrive at a final estimated value.

It was designed to **showcase core data science concepts** — feature engineering, weighted regression logic, sentiment scoring, and model confidence — through a fully interactive, visual web dashboard rather than a static notebook or script.

---

## What I Built

A single-page, fully interactive web application where a user can:

- Configure a property's specifications (area, BHK, bathrooms, type, locality, age, floor)
- Choose or enter a base price per square foot
- Adjust a live **market sentiment slider** representing NLP-driven buyer/market mood
- Instantly receive an estimated price in INR, along with a confidence score
- Explore the prediction through multiple auto-updating charts and a dedicated analytics dashboard

The goal was to make a data science concept (multi-factor price prediction + sentiment weighting) feel like a **real, usable product**, not just a backend script.

---

## How It Is Built

The entire project is built as a **single self-contained `index.html` file** — no backend server, no database, no build pipeline. Everything (structure, styling, and logic) lives in one file, making it instantly deployable anywhere as a static site.

- **HTML5** — semantic structure for the form, dashboard, and analytics sections
- **CSS3** — custom design system using CSS variables, gradients, glassmorphism-style cards, and a fully responsive grid layout
- **Vanilla JavaScript** — handles all form logic, the pricing calculation engine, and dynamic DOM/chart updates in real time
- **Chart.js** — renders all data visualizations (doughnut, bar, and line charts) and updates them live as inputs change
- **Google Fonts (Sora & Inter)** — used for a clean, modern typography system

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, gradients, responsive grid) |
| Logic | Vanilla JavaScript |
| Visualization | Chart.js |
| Typography | Google Fonts — Sora & Inter |
| Hosting | Netlify |

---
| Factor | Description |
|---|---|
| **Base ₹/sqft** | Preset or custom locality price baseline |
| **BHK Factor** | Premium scaling with number of bedrooms |
| **Bathroom Factor** | Premium scaling with number of bathrooms |
| **House Type Multiplier** | Villas/Penthouses priced higher than Studios/Flats |
| **Locality Tier** | Metro Core > Metro Suburban > Tier 2 > Tier 3 |
| **Property Age** | Older properties depreciate slightly |
| **Floor Level** | Higher floors carry a minor premium |
| **Sentiment Multiplier** | Derived from a simulated NLP sentiment score of buyer reviews, news, and market chatter |

A **confidence score** is also generated, reflecting how reliable the estimate is based on how typical or extreme the selected inputs are.

---

## Features

- 🏘️ **8 property types** — Flat, Villa, Studio, Independent House, Penthouse, Duplex, Farmhouse, Row House
- 🛏️ **Flexible BHK selection** — 1 to 10 bedrooms, including half-values (2.5, 3.5, 4.5)
- 🚿 **Bathroom count** — 1 to 6
- 💰 **Custom ₹/sqft input** — choose a preset locality tier or enter a fully custom base price
- 🧠 **Sentiment Analysis slider** — simulates NLP-derived market sentiment (bearish → bullish) influencing the final price
- 📊 **Live data visualizations**:
  - Price contribution breakdown (doughnut chart)
  - Property type price comparison
  - 6-month market sentiment trend
  - Model feature importance
  - Price distribution across BHK configurations
- 💳 **Smart dashboard card** — final price, ₹/sqft, confidence score, locality comparison, and estimated EMI
- 🎨 Fully responsive, dark-themed, modern UI

---

##  What It Can Perform

- Generate an instant, real-time INR price estimate as inputs change — no page reload needed
- Simulate the effect of market sentiment shifts on property valuation
- Compare prices across different property types and BHK configurations visually
- Estimate a 20-year EMI based on the predicted property value
- Provide a confidence score so users understand the reliability of each estimate
- Demonstrate end-to-end data science thinking: feature engineering → sentiment scoring → weighted model → visual analytics

---

## Methodology

1. **Feature Engineering** — Sqft, BHK, bathrooms, property age, floor level, and locality tier are normalized into model-ready inputs.
2. **Sentiment Analysis (NLP)** — Market mood is scored on a bearish-to-bullish index, simulating a VADER/Transformer-style sentiment pipeline applied to listings, reviews, and news.
3. **Weighted Regression** — Structured features and the sentiment multiplier are blended into a single weighted pricing function.
4. **Confidence Scoring** — A prediction confidence interval is estimated from how far inputs deviate from typical/median values.

---



## 👤 Author

### **Project:** House Price Predictor
### **Subject:** Data Science
### **Live Demo:** [House Price Predictor](https://celebrated-pastelito-238b4d.netlify.app/)

---

<div align="center">
