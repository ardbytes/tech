# Six-Week Schedule for MySQL for Developers Course

The "MySQL for Developers" course from PlanetScale is a free, intermediate-level course spanning ~7 hours across 64 videos. This schedule assumes a commitment of ~1-1.5 hours per week, split into 1-2 sessions, covering Schema, Indexing, Querying, and Real-World Examples. Use a MySQL database (e.g., PlanetScale or Docker) and a client like TablePlus for practice.

## Week 1: Schema Basics (1 hour)
- **Objective**: Understand schema design, data types, and table creation.
- **Tasks**:
  - Watch videos on schema introduction (~15-20 min, ~3-4 videos):
    - Importance of compact, simple, accurate schemas.
    - Common data types (INT, VARCHAR, BINARY, JSON).
  - Practice (30-40 min):
    - Set up a MySQL database (PlanetScale or Docker).
    - Create a table (e.g., `users` with `id`, `name`, `email`).
    - Experiment with data types (e.g., INT vs. VARCHAR).
- **Resources**: Schema videos, [PlanetScale CLI setup guide](https://planetscale.com/docs), MySQL documentation.

## Week 2: Advanced Schema and Primary Keys (1 hour)
- **Objective**: Deepen schema knowledge and learn about primary keys.
- **Tasks**:
  - Watch videos on advanced schema and primary keys (~20-25 min, ~4-5 videos):
    - Primary key selection (e.g., BIGINT for `id`).
    - Generated columns for automated calculations.
  - Practice (35-40 min):
    - Create a table with a primary key (e.g., `users` with `id` as BIGINT) and a generated column.
    - Use `SHOW CREATE TABLE` and `SHOW INDEXES` to verify.
    - Insert sample data and test constraints.
- **Resources**: Primary keys videos, MySQL `SHOW` command documentation.

## Week 3: Indexing Fundamentals (1.5 hours)
- **Objective**: Learn indexing principles to improve query performance.
- **Tasks**:
  - Watch videos on indexing (~25-30 min, ~5-6 videos):
    - Index characteristics, B-trees, primary vs. secondary keys.
    - Where to add indexes based on query patterns.
  - Practice (60 min):
    - Create a table (e.g., `people` with `id`, `birthday`) and add an index (e.g., `birthday_index`).
    - Run queries (e.g., `SELECT * FROM people WHERE birthday = '1989-02-14'`) and compare performance.
    - Use `SHOW INDEXES` to verify.
- **Resources**: Indexing videos, MySQL index documentation.

## Week 4: Querying Basics (1.5 hours)
- **Objective**: Master writing efficient MySQL queries.
- **Tasks**:
  - Watch videos on querying introduction (~30-35 min, ~6-7 videos):
    - Writing queries using indexes.
    - Counting rows/values (e.g., `COUNT()`, `SUM()`).
  - Practice (55-60 min):
    - Write queries on a sample table (e.g., `rental` for counting rentals).
    - Experiment with `IF()` and `SUM()` for conditional counting.
    - Test query performance with indexes.
- **Resources**: Querying videos, MySQL `COUNT()` and `SUM()` documentation.

## Week 5: Advanced Querying and Optimization (1.5 hours)
- **Objective**: Optimize queries using EXPLAIN and summary tables.
- **Tasks**:
  - Watch videos on advanced querying (~30-35 min, ~6-7 videos):
    - Using `EXPLAIN` to analyze query performance.
    - Summary tables for historical data calculations.
  - Practice (55-60 min):
    - Run `EXPLAIN` on a query (e.g., `SELECT * FROM people WHERE birthday BETWEEN '2006-01-01' AND '2006-12-31'`) and interpret output.
    - Create a summary table (e.g., `payment_summary` for monthly totals) and use `UNION ALL` or CTEs.
- **Resources**: EXPLAIN and summary tables videos, MySQL `EXPLAIN` and CTE documentation.

## Week 6: Real-World Examples and Review (1-1.5 hours)
- **Objective**: Apply knowledge to practical scenarios and consolidate learning.
- **Tasks**:
  - Watch videos on real-world examples (~20-25 min, ~4-5 videos):
    - Combining schema, indexing, and querying for developer scenarios.
  - Practice (40-60 min):
    - Work on a practical example (e.g., `payments` table with schema, indexes, queries).
    - Optimize one query or schema from previous weeks.
    - (Optional) Explore JSON columns for flexible data storage.
  - Review (10-15 min):
    - Revisit key concepts (schema, indexing, querying).
    - Check [PlanetScale’s GitHub repo](https://github.com/planetscale) for exercises.
- **Resources**: Real-world examples videos, course GitHub repo.

## Notes
- **Flexibility**: Combine weeks (e.g., Weeks 1-2) if you have more time, or spread tasks if less.
- **Environment**: Set up a MySQL database in Week 1 (PlanetScale free tier or Docker). Use TablePlus or any MySQL client.
- **Support**: Contact [education@planetscale.com](mailto:education@planetscale.com) for questions.
- **Progress**: Track completed videos/exercises on the course platform. Aim to finish all 64 videos by Week 6.
- **Next Steps**: Explore “MySQL for Python Developers” for Python integration.
