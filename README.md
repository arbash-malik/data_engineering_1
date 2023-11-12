# Data Engineering 1 - Term Project 1

This repository contains my materials for Term Project 1 for my Data Engineering 1 course.

# Introduction of the dataset
PKDD Financial is a relational dataset which has synthethic real world data of a banking institution in Czech Republic. The dataset has 8 tables;
  1. `ACCOUNTS`
  2. `CARDS`
  3. `CLIENTS`
  4. `DISPOSITIONS`
  5. `DISTRICS`
  6. `LOANS`
  7. `ORDERS`
  8. `TRANSACTIONS`

The dataset had .asc file types, and more than a million rows (five years of banking transactions data - `transactions` table), which I trimmed down to 50k


# 1. Operational Layer - Data Loading & Database creation
 1. An `Entity Relationship Digram` was made to make the data base structure and link the tables.
 2. Indexes of certain columns were also made for faster querying. (find the ERD and the indexes in the **ERD & Variable Description.PDF**. Using the ERD, an SQL script was generated using the forward-engineering tool in MySQL.
 3. The query was run to create the database and then the data was loaded through `in file` method.
 4. Exploratory data queries were done to ensure database is working fine. The data was trimmed down as well.
 5. Database was dumped with `table structure` & `data` to make it reproducible.




