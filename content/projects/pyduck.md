---
title: "PyDuck — Pandas‑like API on DuckDB SQL"
date: 2025-08-20
tags: ["project"]
summary: "Python, DuckDB, Pandas, SQL, NumPy, Polars"
---

- Immutable, chainable 'Quack' views with lazy evaluation and SQL lineage (Spark RDD‑style).
- Compiler translates common Pandas ops to optimized DuckDB SQL; `.to_sql()` for transparency.
- >100× speedups over Pandas on typical aggregation/filtering at 10GB scales in benchmarks.
