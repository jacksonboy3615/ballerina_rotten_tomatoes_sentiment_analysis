# 🎬 Audience Sentiment Analysis — Ballerina (2025)

This project analyzes audience reviews of Ballerina (2025) — a film set in the John Wick universe — to understand how audiences responded, what themes they discussed, and how the character Eve Macarro is perceived.
Using VADER sentiment analysis and keyword extraction, this project explores whether audiences viewed the film positively and how strongly it stands on its own, compared to the John Wick franchise.

## 📊 Key Findings
### ⭐ Sentiment Overview

- 77.8% of Rotten Tomatoes audience reviews were classified as positive
- Neutral and negative reviews made up the remainder

*Note: Positive = VADER compound score > 0.05

### 🔎 Keyword Insights

- Top keywords were dominated by “Wick” and “John”, followed by action, great, and film
- The protagonist Eve Macarro did not appear in the Top 10 keywords

### 🎯 Interpretation

- Although audiences praised the storyline and action sequences, Ballerina still appears to be strongly overshadowed by John Wick, suggesting brand dependency.

## 📅 Dataset

- Source: Rotten Tomatoes (Audience Reviews)
- Total Reviews: 970
- Time Range: June 23, 2025 - December 19, 2025
- Format:	CSV file
- Libraries: Selenium, Pandas, VADER, and WordCloud

## 🔍 Methodology

### Data Collection
- Web-scraped viewer reviews from Rotten Tomatoes using Selenium and exported them as CSV files.
(Source Link: https://www.rottentomatoes.com/m/ballerina_2025/reviews/all-audience)

### Text Processing
- Cleaning (lowercasing, removing symbols, stopwords)
- Tokenization
- Keyword frequency analysis

### Sentiment Analysis
I. VADER classifier

VADER Score Ranges:
- Positive: compound > 0.05
- Neutral: -0.05 ≤ compound ≤ 0.05
- Negative: compound < -0.05

### Visualization
- Donut chart for sentiment distribution
- Bar chart of Top 10 keywords
- Word cloud showing word prominence

<img width="1158" height="651" alt="Slide 1" src="https://github.com/user-attachments/assets/4b830b63-2959-44e7-934f-0076bf42e4e7" />

<img width="1157" height="649" alt="Slide 2" src="https://github.com/user-attachments/assets/191a6d75-5d06-4961-90f2-c8ef364a5903" />

<img width="1157" height="644" alt="Slide 3" src="https://github.com/user-attachments/assets/86fb65bc-8299-46a0-a578-7ef61cf435f0" />

## Solutions

I. Develop a Miniseries Centered on Eve Macarro:
The series could explore events after John Wick: Chapter 4, following the fallout from John Wick’s death and deepening Eve’s backstory and motivations.

II. Plan a Comic Book Series About Assassin(s) Revenging Eve Macarro:
Before committing to a sequel series or film, releasing a comic series would both deepen audiences’ understanding of Eve Macarro and give the production team room to expand the John Wick universe.

## 🔗 Connect with Me
If you’d like to discuss data analysis, Python, or TV series 😄
Find me on [LinkedIn](https://www.linkedin.com/in/jae-hwan-kim-274190100/) or contact me via email: jkim3615@gmail.com!
