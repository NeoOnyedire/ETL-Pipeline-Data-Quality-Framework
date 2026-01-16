# SalesFlow – Reliable ETL Pipeline with Data Quality Framework

A modern **Java Spring Boot** ETL (Extract, Transform, Load) system with strong emphasis on **automated data quality validation**, monitoring, and REST API control.

Built from scratch as a personal initiative to explore real-world data engineering patterns and quality assurance in data pipelines.

## ✨ Highlights

- Full ETL flow: CSV ingestion → staging → transformation → quality gates → dimensional warehouse
- Multiple **data quality rules** (completeness, uniqueness, referential integrity, business logic…)
- REST API to trigger runs, check status & view quality reports
- Testcontainers + comprehensive automated testing (unit + integration + data quality assertions)
- Clean architecture, proper error handling & logging
- Easy local dev with H2 + production-like PostgreSQL setup

## Architecture Overview
