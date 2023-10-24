# Toys Store Analysis
the data consists of:
- Sales (which contains transactions).
- Products (which contains Product’s Info).
- Reps (Which Contains Sales Indoor).
- Stores (which Contains Store’s Info).

First I've used excel to answer some questions (you an find the answers in the pivot tables sheet is the attached folder):
- Get Top 20 Products per Sold.
- Get Top 10 Reps per Count of Order number.
- Get Top & Worst 10 Brand per Value.
- Rank Month in Each Stores.
- Rank Reps in each Stores.
- Rank Products in each Brand.

Then I've created a star schema model:
![Data Model](https://github.com/MohamedWageh09/Toys-Store-Analysis/assets/120044385/f3fd032f-8b00-45bb-87ed-c1711ea5367d)

To populate the DWH i've created a simple SSIS ETL package 

![image](https://github.com/MohamedWageh09/Toys-Store-Analysis/assets/120044385/47c4c430-3bae-4419-83f3-36a13b9a3975)
![image](https://github.com/MohamedWageh09/Toys-Store-Analysis/assets/120044385/87176136-be9f-453b-99d9-a49bcf401974)

After populating the DWH i've onnected Power BI to the DWH and created 3 dashboards for sales, stores and sales representitives.
you an find the dashboard [here](https://www.novypro.com/project/toys-store-dashboard)


