# SQL-Task6: Subqueries and Nested Queries

## 🎯 Objective
Practice advanced SQL concepts including:
- Scalar subqueries
- Correlated subqueries
- Subqueries in WHERE and FROM clauses
- Nested logic using IN, EXISTS, and derived tables

## 🛠 Tools Used
- MySQL Workbench
- Sample schema with Customers and Orders tables

## 🧪 Sample Data
### Customers Table
| CustomerID | CustomerName | City        |
|------------|---------------|-------------|
| 1          | Alice         | New York    |
| 2          | Bob           | Los Angeles |
| 3          | Charlie       | Chicago     |
| 4          | Diana         | Houston     |

### Orders Table
| OrderID | OrderDate  | CustomerID | Amount |
|---------|------------|------------|--------|
| 101     | 2024-05-01 | 1          | 250.00 |
| 102     | 2024-05-03 | 1          | 100.00 |
| 103     | 2024-05-04 | 2          | 150.00 |
| 104     | 2024-05-06 | NULL       | 100.00 |

## ✅ Queries Included
1. Scalar subquery to get average order amount
2. Correlated subquery to find high-paying customers
3. Subqueries with IN and EXISTS for filtering
4. Derived table (subquery in FROM) to get total order amount
5. Subquery to find customer with highest single order

## 🚀 Output
These queries demonstrate how nested subqueries and advanced filtering improve data retrieval and logic expression in SQL.


