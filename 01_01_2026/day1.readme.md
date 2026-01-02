### POSTGRESQL

- PostgreSQL (often called Postgres) is a powerful, open-source relational database management system (RDBMS) used to store, manage, and query data reliably and securely.

# What is PostgreSQL?

- PostgreSQL is a database server that:
- Stores data in tables (rows & columns)
- Uses SQL (Structured Query Language)
- Follows ACID rules (data safety & consistency)
- Is free, open-source, and enterprise-grade
- It is widely used for web apps, mobile apps, analytics, fintech, SaaS platforms, and large systems.

# Why PostgreSQL is Used

- PostgreSQL is chosen because it is:
- Very reliable
- Highly secure
- Extremely powerful for complex data
- Scales well (small → very large apps)

- **Companies like Instagram, Uber, Netflix, Spotify, Reddit use PostgreSQL.**

# Advanced SQL Support

- **Supports:**
- JOINs
- Subqueries
- Views
- Indexes
- Triggers
- Stored Procedures

```
  SELECT name, email FROM users WHERE is_active = true;
```

## for access the psql via command terminal use this

- psql -U postgres

## PostgreSQL is an open-source, advanced relational database system that supports SQL, transactions, and JSON data, providing high performance, security, and scalability.

## when using the **SQL Shell**

- to se the data batabses on postgreSQL

```
  \list

```

- to clean the terminal use

```
 \! cls
```

# using Queris in POSTGRESQL

- to create **database**
  ```
  CREATE DATABSE DATABASE_NAME;
  ```
