# Customer Behavior Analysis Project

This project focuses on analyzing customer behavior, sentiment, and engagement across various touchpoints in their journey. It aims to provide actionable insights for marketing and customer management improvements.

## Project Objectives

### Marketing Analysis
- Identify factors influencing customer engagement.
- Analyze the stage at which customers are dropping off.
- Study how customer reviews impact purchasing behavior.
- Evaluate the performance of products, locations, and customer segments.

### Customer Management
- Perform sentiment analysis on customer reviews.
- Identify key complaints and areas for improvement.
- Explore patterns between negative reviews and product performance.
- Provide data-driven recommendations to enhance customer satisfaction.

## Setup

Create and activate the local virtual environment:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

The project reads the PostgreSQL connection from `.env`:

```env
DATABASE_URL=postgresql+psycopg2://postgres:DS2711@localhost:5432/Customer_Behavior_Analysis
```

## Technologies Used
- Python / PostgreSQL
- Pandas
- Natural Language Processing (NLP)
