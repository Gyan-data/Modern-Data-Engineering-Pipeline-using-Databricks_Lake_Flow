# Modern-Data-Engineering-Pipeline-using-Databricks_Lake_Flow

## What is this project?

This project shows how to build a complete data pipeline
in Databricks without writing a single line of PySpark.

I used a tool called Lakeflow Designer — a drag and drop
visual canvas inside Databricks where you connect blocks
and it runs on real data.

<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/31e526b1-6ab1-44d1-bf85-b0b92484d4fe" />


---

## What data did I use?

6 simple CSV files representing an online store.

| File | What it contains |
|---|---|
| customers.csv | Customer names and city details |
| orders.csv | Order ID, date, and status |
| order_items.csv | Products inside each order |
| products.csv | Product names and prices |
| shipments.csv | Shipping info for each order |
| reviews.csv | What customers said about products |

---

## How does the pipeline work?

<img width="1596" height="835" alt="image" src="https://github.com/user-attachments/assets/e5f72b33-bdcf-4e48-acaa-9a9568840cab" />


Step 1 — Load orders and order items, then join them together

Step 2 — Bring in customer and shipment data using Python blocks

Step 3 — Join everything into one big table

Step 4 — Group by city, sort by total sales, save as Delta table

Step 5 — Group by month and status to track order trends

Step 6 — Run AI on reviews to detect happy or unhappy customers

Step 7 — Save all results as final output tables

---

## The AI Part

This was the most interesting part of the whole project.

I used the AI Function operator on the reviews table.
No machine learning code. No model setup.
Just a plain English instruction and it ran
sentiment analysis on its own.

<img width="1598" height="734" alt="image" src="https://github.com/user-attachments/assets/c579bb37-cf10-4390-8e9b-136de0a58345" />


---

## Final Output

The pipeline produces clean, structured tables ready
for reporting and analysis.

<img width="1629" height="838" alt="image" src="https://github.com/user-attachments/assets/6272afdf-923d-4381-a49f-30877b70f12e" />


## What will you learn?

- How to use Lakeflow Designer from scratch
- How to join and transform data without code
- How AI works inside a real data pipeline
- How to save results as production Delta tables

---

## Why does this matter?

Data engineering is changing fast.

AI is now embedded inside the platform itself.
Not as a separate tool. Right inside the pipeline
you are already building.

This is where the industry is heading.

---

## Author

**Gyan Singh** —
Data Engineer | Databricks | Azure | Modern Data Platforms

