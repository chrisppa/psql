# PostgreSQL Learning Guide 🐘

**Source:** [PostgreSQL 18 Official Documentation](https://www.postgresql.org/docs/current/index.html)
**Total Topics:** 50
**Progress:** 0/50 ✓

---

## Preface & Introduction

- [ ] P.1 What is PostgreSQL? (https://www.postgresql.org/docs/current/intro-whatis.html)
- [ ] P.2 Brief History of PostgreSQL (https://www.postgresql.org/docs/current/history.html)
- [ ] P.3 Conventions & Further Information (https://www.postgresql.org/docs/current/notation.html)

---

## Part I — Tutorial

- [ ] #1 ⭐ Getting Started — installation & first steps (https://www.postgresql.org/docs/current/tutorial-start.html)
- [ ] #2 ⭐ The SQL Language — querying, joins, aggregates (https://www.postgresql.org/docs/current/tutorial-sql.html)
- [ ] #3 ⭐ Advanced Features — views, foreign keys, transactions, window functions (https://www.postgresql.org/docs/current/tutorial-advanced.html)

---

## Part II — The SQL Language

- [ ] #4 SQL Syntax — lexical structure, value expressions, operators (https://www.postgresql.org/docs/current/sql-syntax.html)
- [ ] #5 ⭐ Data Definition — tables, schemas, constraints, inheritance (https://www.postgresql.org/docs/current/ddl.html)
- [ ] #6 ⭐ Data Manipulation — INSERT, UPDATE, DELETE, RETURNING (https://www.postgresql.org/docs/current/dml.html)
- [ ] #7 ⭐ Queries — SELECT, joins, subqueries, CTEs, UNION (https://www.postgresql.org/docs/current/queries.html)
- [ ] #8 ⭐ Data Types — numeric, text, JSON, arrays, ranges, UUID (https://www.postgresql.org/docs/current/datatype.html)
- [ ] #9 ⭐ Functions and Operators — string, math, date/time, JSON, window (https://www.postgresql.org/docs/current/functions.html)
- [ ] #10 Type Conversion — implicit & explicit casting rules (https://www.postgresql.org/docs/current/typeconv.html)
- [ ] #11 ⭐ Indexes — B-tree, Hash, GIN, GiST, BRIN, partial indexes (https://www.postgresql.org/docs/current/indexes.html)
- [ ] #12 Full Text Search — tsvector, tsquery, ranking, dictionaries (https://www.postgresql.org/docs/current/textsearch.html)
- [ ] #13 ⭐ Concurrency Control — MVCC, transactions, isolation levels, locking (https://www.postgresql.org/docs/current/mvcc.html)
- [ ] #14 ⭐ Performance Tips — EXPLAIN, ANALYZE, query planning, vacuuming (https://www.postgresql.org/docs/current/performance-tips.html)
- [ ] #15 Parallel Query — how Postgres parallelizes queries (https://www.postgresql.org/docs/current/parallel-query.html)

---

## Part III — Server Administration

- [ ] #16 Installation from Binaries — packages, OS setup (https://www.postgresql.org/docs/current/install-binaries.html)
- [ ] #17 Installation from Source Code — build & compile (https://www.postgresql.org/docs/current/installation.html)
- [ ] #18 ⭐ Server Setup and Operation — initdb, pg_ctl, logging (https://www.postgresql.org/docs/current/runtime.html)
- [ ] #19 ⭐ Server Configuration — postgresql.conf, GUC parameters (https://www.postgresql.org/docs/current/runtime-config.html)
- [ ] #20 ⭐ Client Authentication — pg_hba.conf, methods, SSL (https://www.postgresql.org/docs/current/client-authentication.html)
- [ ] #21 ⭐ Database Roles — CREATE ROLE, privileges, row security (h- [ ]ttps://www.postgresql.org/docs/current/user-manag.html)
- [ ] #22 Managing Databases — CREATE DATABASE, tablespaces (https://www.postgresql.org/docs/current/managing-databases.html)
- [ ] #23 Localization — collation, encoding, locale (https://www.postgresql.org/docs/current/charset.html)
- [ ] #24 ⭐ Routine Maintenance — VACUUM, ANALYZE, reindex, log rotation (https://www.postgresql.org/docs/current/maintenance.html)
- [ ] #25 ⭐ Backup and Restore — pg_dump, pg_basebackup, PITR (https://www.postgresql.org/docs/current/backup.html)
- [ ] #26 ⭐ High Availability & Replication — streaming, failover, load balancing (https://www.postgresql.org/docs/current/high-availability.html)
- [ ] #27 ⭐ Monitoring Database Activity — pg_stat_* views, activity reports (https://www.postgresql.org/docs/current/monitoring.html)
- [ ] #28 Reliability & the Write-Ahead Log — WAL mechanics, checkpoints (https://www.postgresql.org/docs/current/wal.html)
- [ ] #29 Logical Replication — publication, subscription, conflict handling (https://www.postgresql.org/docs/current/logical-replication.html)
- [ ] #30 Just-in-Time Compilation (JIT) (https://www.postgresql.org/docs/current/jit.html)

---

## Part IV — Client Interfaces

- [ ] #31 libpq — C library for connecting to PostgreSQL (https://www.postgresql.org/docs/current/libpq.html)
- [ ] #32 Large Objects — lo_read, lo_write, streaming blobs (https://www.postgresql.org/docs/current/largeobjects.html)
- [ ] #33 ECPG — Embedded SQL in C (https://www.postgresql.org/docs/current/ecpg.html)
- [ ] #34 The Information Schema — standard catalog views (https://www.postgresql.org/docs/current/information-schema.html)

---

## Part V — Server Programming

- [ ] #35 Extending SQL — custom types, operators, functions in C (https://www.postgresql.org/docs/current/extend.html)
- [ ] #36 ⭐ Triggers — row & statement triggers, when/how to use them (https://www.postgresql.org/docs/current/triggers.html)
- [ ] #37 Event Triggers — DDL-level triggers (https://www.postgresql.org/docs/current/event-triggers.html)
- [ ] #38 The Rule System — query rewrite rules (https://www.postgresql.org/docs/current/rules.html)
- [ ] #39 Procedural Languages — overview of PL support (https://www.postgresql.org/docs/current/xplang.html)
- [ ] #40 ⭐ PL/pgSQL — variables, control flow, exception handling, cursors (https://www.postgresql.org/docs/current/plpgsql.html)
- [ ] #41 PL/Python — writing functions in Python (https://www.postgresql.org/docs/current/plpython.html)
- [ ] #42 Logical Decoding — CDC, change data capture (https://www.postgresql.org/docs/current/logicaldecoding.html)

---

## Part VI — Reference

- [ ] #43 ⭐ SQL Commands — CREATE, ALTER, DROP, GRANT, REVOKE, etc. (https://www.postgresql.org/docs/current/sql-commands.html)
- [ ] #44 ⭐ Client Applications — psql, pg_dump, pg_restore, pgbench (https://www.postgresql.org/docs/current/reference-client.html)
- [ ] #45 Server Applications — postgres, pg_ctl, initdb, pg_upgrade (https://www.postgresql.org/docs/current/reference-server.html)

---

## Part VII — Internals

- [ ] #46 Overview of PostgreSQL Internals — query lifecycle, process model (https://www.postgresql.org/docs/current/overview.html)
- [ ] #47 System Catalogs & Views — pg_class, pg_attribute, system views (https://www.postgresql.org/docs/current/catalogs.html)
- [ ] #48 Frontend/Backend Protocol (https://www.postgresql.org/docs/current/protocol.html)
- [ ] #49 Database Physical Storage (https://www.postgresql.org/docs/current/storage.html)
- [ ] #50 Transaction Processing (https://www.postgresql.org/docs/current/transactions.html)

---

## Key Topics Summary

⭐ **Starred Key Topics (20 total — prioritize these!)**

1. Getting Started
2. The SQL Language (Tutorial)
3. Advanced Features (Tutorial)
4. Data Definition
5. Data Manipulation
6. Queries
7. Data Types
8. Functions and Operators
9. Indexes
10. Concurrency Control
11. Performance Tips
12. Server Setup and Operation
13. Server Configuration
14. Client Authentication
15. Database Roles
16. Routine Maintenance
17. Backup and Restore
18. High Availability & Replication
19. Monitoring Database Activity
20. Triggers
21. PL/pgSQL
22. SQL Commands Reference
23. Client Applications Reference

---

## Resources

* **Official Docs:** https://www.postgresql.org/docs/current/index.html
* **Download:** https://www.postgresql.org/download/
* **psql cheat sheet:** https://www.postgresql.org/docs/current/app-psql.html
* **Release Notes:** https://www.postgresql.org/docs/current/release.html

---

## Notes

Use this checklist to track your progress through the PostgreSQL documentation. The ⭐ starred topics are the most practical chapters for everyday database work — start there if you're learning for real-world use.

**Suggested learning order:**
1. Complete Part I (Tutorial) first — it gives you a working mental model
2. Work through Part II (SQL Language) chapter by chapter
3. Pick up Part III (Server Administration) as you start managing databases
4. Dip into Part VI (Reference) on demand as you encounter specific commands
5. Return to Part V (Server Programming) when you need stored procedures or triggers

Happy Learning! 🚀
