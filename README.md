# book-market-sql-analysis
#  Book App Market Analysis (SQL Project)

##  Project Overview
This project explores a database from a digital reading platform containing information about books, authors, publishers, ratings, and user reviews.

The goal is to analyze both the catalog and user behavior in order to generate insights that could support the development of a new book-related product.

---

##  Objectives
- Understand the structure and quality of the dataset
- Analyze book availability and publication trends
- Evaluate user engagement through ratings and reviews
- Identify top-performing authors and publishers
- Generate business insights for a potential book app

---

##  Tools & Technologies
- SQL (PostgreSQL)
- Python
- Pandas
- SQLAlchemy
- Jupyter Notebook

---

##  Database Structure
The database includes the following main tables:
- `books` → book information
- `authors` → author details
- `publishers` → publisher information
- `ratings` → user ratings (1–5 scale)
- `reviews` → user-written reviews

Relationships:
- Books are linked to authors and publishers
- Ratings and reviews are linked to books and users

---

##  Data Quality Checks
Performed validation on all main tables:
- No missing values in key columns
- No duplicate IDs
- Valid date ranges (1952–2020)
- Ratings range correctly between 1 and 5
- No empty or null reviews

 Conclusion: Data is clean and reliable for analysis

---

##  Key Analysis & Insights

###  Books Published After 2000
- 819 books were published after January 1st, 2000  
 Indicates strong modern catalog presence

---

###  Book Ratings Analysis
- Identified most rated books
- Calculated average rating per book

 Popular books include:
- *Twilight*
- *The Hobbit*
- *The Catcher in the Rye*

---

###  Top Publisher
- **Penguin Books** published the highest number of books (>50 pages)

 Strong market presence and content volume

---

###  Top Author (Quality Filter Applied)
- Filter: only books with ≥ 50 ratings

 **J.K. Rowling / Mary GrandPré**
- Average rating: ~4.29
- Based on 310 ratings

 Ensures statistical reliability (avoids bias from low sample sizes)

---

###  User Engagement
- Users who rated >50 books wrote on average:
  
**24 reviews per user**

➡️ Highly active users also contribute written content  
➡️ Strong engagement potential for community features

---

## Business Insights
- Modern books dominate the catalog
- Popular titles drive engagement
- A few publishers and authors dominate performance
- Highly engaged users are valuable for platform growth

---

## Conclusion
This analysis highlights key patterns in reader behavior and book performance, providing a solid foundation for designing a competitive book platform focused on user engagement and high-quality content.

---

