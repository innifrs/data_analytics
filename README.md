# data_analytics
SQL PARTITION BY Examples
This repository contains examples of using the PARTITION BY clause in SQL to perform various analytical functions. These examples demonstrate how to leverage PARTITION BY to group data within partitions and perform calculations or rankings over those partitions.

What is PARTITION BY?

The PARTITION BY clause in SQL is used to divide the result set into partitions and perform computations on each partition independently. It is commonly used with window functions to calculate aggregations, rankings, and other operations across partitions of data.

Key Points:

Partitioning: The data is divided into segments (partitions) based on one or more columns.
Window Functions: Functions like ROW_NUMBER(), RANK(), DENSE_RANK(), SUM(), AVG(), COUNT(), LAG(), LEAD(), FIRST_VALUE(), and LAST_VALUE() can be used with PARTITION BY.
