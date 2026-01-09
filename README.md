# SQL Practice (Interview + Real-World)

A structured SQL practice repository focused on writing clean, readable queries and building real-world intuition for analytics and data work. Includes progressive exercises (beginner → advanced), datasets, solutions, and optional performance notes.

## What’s Inside

- **01_basics** — SELECT, WHERE, ORDER BY, LIMIT, DISTINCT  
- **02_joins** — INNER/LEFT/RIGHT joins, join pitfalls, many-to-many  
- **03_aggregation** — GROUP BY, HAVING, aggregates, percent-of-total  
- **04_subqueries_ctes** — subqueries, CTEs, recursive CTEs (optional)  
- **05_window_functions** — ROW_NUMBER, RANK, LAG/LEAD, rolling metrics  
- **06_case_and_strings** — CASE logic, string parsing, data cleanup  
- **07_dates_times** — date math, cohorts, retention windows  
- **08_data_quality** — duplicates, null handling, constraints checks  
- **09_optimization** — indexes, EXPLAIN, query shaping (optional)  
- **10_interview_sets** — classic interview-style problems (LeetCode-style)

Each folder typically contains:
- `README.md` (prompt + tables)
- `setup.sql` (schema + sample inserts) or a dataset link
- `solutions.sql` (my answers)
- `notes.md` (edge cases, alternative approaches)

## Getting Started

### Option A: Run locally with Docker (recommended)
1. Install Docker
2. From the repo root:

```bash
docker compose up -d
