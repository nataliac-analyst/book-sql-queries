# SQL Book Database Analysis

This project contains a set of SQL queries executed within a Python Jupyter Notebook to explore and analyze a dataset of books, authors, publishers, ratings, and user reviews.
The objective is to practice SQL queries commonly used in data analysis and answer analytical questions about publishing trends, author performance, and user engagement.

## Tools

- SQL
- Python
- Jupyter Notebook
- sqlalchemy 
- Pandas

## Analytical Questions

The analysis focuses on answering the following questions:

1. How many books were published after January 1, 2000?
2. What is the number of user reviews and the average rating for each book?
3. Which publisher has released the highest number of books with more than 50 pages?
4. Which author has the highest average book rating among authors with at least 50 ratings?
5. What is the average number of text reviews among users who have rated more than 50 books?

## Skills Demonstrated

The queries demonstrate the use of:

- Data filtering
- Aggregations and grouping
- JOIN operations across multiple tables
- Subqueries
- Analytical SQL queries

## Dataset

The dataset includes information about books, authors, publishers, user ratings, and reviews.  
It is structured across several related tables:

- **books** – information about books (title, author, num_pages, publisher_id, publication_date)
- **authors** – author information
- **publishers** – publishing companies
- **ratings** – user ratings for books
- **reviews** – text reviews written by users
