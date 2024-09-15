# ✈️ Airline Reviews Sentiment Analysis

This project leverages Natural Language Processing (NLP) techniques to analyze customer reviews of airlines, providing actionable insights into passenger satisfaction. By applying sentiment analysis on data from **Airline Quality**, we aim to uncover key trends and identify improvement areas for airlines.

## 📝 Project Overview
We conducted sentiment analysis on over 23,000 customer reviews to determine the factors that contribute to positive or negative experiences. Our analysis covers both domestic and international flights, with a focus on key service categories such as seat comfort, cabin staff, inflight entertainment, and Wi-Fi connectivity.

### Key Objectives:
- **Sentiment Analysis**: Compare sentiment scores using **VADER** and **TextBlob**.
- **EDA**: Perform exploratory data analysis to visualize trends in customer satisfaction.
- **Actionable Insights**: Provide data-driven recommendations for airlines to improve their services.

## 📊 Data Summary
- **Source**: Airline reviews from **Kaggle**.
- **Size**: 23,172 reviews with multiple variables.
- **Key Columns**:
  - `Airline Name`: The airline being reviewed.
  - `Overall Rating`: Customer's rating (0-9).
  - `Review Text`: The text of the review.
  - `Seat Comfort`, `Cabin Staff`, `Food & Beverages`: Specific ratings for flight departments.

## 🧑‍💻 Methodology
### Data Cleaning:
- Handled missing data by filling text entries with 'N/A' and imputing numerical values using column means.
- Mapped categorical values for department ratings (e.g., seat comfort, inflight entertainment) to satisfaction levels.

### Sentiment Analysis:
- **VADER**: A rule-based model tuned for social media sentiment, providing a **compound score** for sentiment intensity.
- **TextBlob**: A lexicon-based tool offering **polarity** (positive/negative) and **subjectivity** scores.

### Exploratory Data Analysis:
- Visualized customer rating distributions across flight types (domestic vs. international).
- Identified key areas of customer dissatisfaction, especially in **seat comfort**, **cabin staff service**, and **Wi-Fi connectivity**.

## 📈 Results
- **Lower Sentiment Airlines**: 
  - **Domestic**: Frontier Airlines, Silver Airways, JetBlue Airways.
  - **International**: United Airlines, Royal Jordanian, Interjet Airlines.
- **Customer Satisfaction**:
  - Significant dissatisfaction with seat comfort and Wi-Fi connectivity, particularly on domestic flights.
  - Inflight entertainment on international flights showed room for improvement.


## 📊 Visualization and Insights
- **Sentiment Trends Over Time**: Showed sentiment fluctuations across key periods, including a noticeable dip during the COVID-19 pandemic.
- **Flight Department Ratings**: Visualizations highlighted customer ratings for inflight services such as seat comfort, food & beverages, and ground service, pointing out consistent underperformance areas.
  
## 🛠️ Recommendations
Based on our findings, we recommend airlines:
1. **Improve Seat Comfort**: Upgrading seating ergonomics and legroom.
2. **Enhance Wi-Fi Infrastructure**: Providing more reliable connectivity on both domestic and international flights.
3. **Staff Training**: Emphasize cabin staff training to improve customer interactions.
4. **Inflight Entertainment**: Offer diverse content for both long-haul and short-haul flights, including regional selections and up-to-date streaming services.

## 🚀 Future Work
- Incorporate additional NLP techniques like **topic modeling** to identify common themes in negative reviews.
- Extend analysis to other datasets to compare sentiment across different travel sectors.
