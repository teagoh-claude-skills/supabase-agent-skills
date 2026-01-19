# PostgreSQL Best Practices

**Version 0.1.0**
Supabase
January 2026

> This document is optimized for AI agents and LLMs. Rules are prioritized by performance impact.

---

## Abstract

Comprehensive PostgreSQL performance optimization guide for developers using Supabase and PostgreSQL. Contains performance rules across 8 categories, prioritized by impact from critical (query performance, connection management) to incremental (advanced features). Each rule includes detailed explanations, incorrect vs. correct SQL examples, query plan analysis, and specific performance metrics to guide automated optimization and code generation.

---

## Table of Contents

1. [Query Performance](#query-performance) - **CRITICAL**

2. [Connection Management](#connection-management) - **CRITICAL**

3. [Schema Design](#schema-design) - **HIGH**

4. [Concurrency & Locking](#concurrency-locking) - **MEDIUM-HIGH**

5. [Security & RLS](#security-rls) - **MEDIUM-HIGH**

6. [Data Access Patterns](#data-access-patterns) - **MEDIUM**

7. [Monitoring & Diagnostics](#monitoring-diagnostics) - **LOW-MEDIUM**

8. [Advanced Features](#advanced-features) - **LOW**

---

## 1. Query Performance

**Impact: CRITICAL**

Slow queries, missing indexes, inefficient query plans. The most common source of PostgreSQL performance issues.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 2. Connection Management

**Impact: CRITICAL**

Connection pooling, limits, and serverless strategies. Critical for applications with high concurrency or serverless deployments.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 3. Schema Design

**Impact: HIGH**

Table design, index strategies, partitioning, and data type selection. Foundation for long-term performance.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 4. Concurrency & Locking

**Impact: MEDIUM-HIGH**

Transaction management, isolation levels, deadlock prevention, and lock contention patterns.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 5. Security & RLS

**Impact: MEDIUM-HIGH**

Row-Level Security policies, privilege management, and authentication patterns.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 6. Data Access Patterns

**Impact: MEDIUM**

N+1 query elimination, batch operations, cursor-based pagination, and efficient data fetching.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 7. Monitoring & Diagnostics

**Impact: LOW-MEDIUM**

Using pg_stat_statements, EXPLAIN ANALYZE, metrics collection, and performance diagnostics.

*No rules defined yet. See rules/_template.md for creating new rules.*

## 8. Advanced Features

**Impact: LOW**

Full-text search, JSONB optimization, PostGIS, extensions, and advanced PostgreSQL features.

*No rules defined yet. See rules/_template.md for creating new rules.*

## References

- https://www.postgresql.org/docs/current/
- https://supabase.com/docs
- https://wiki.postgresql.org/wiki/Performance_Optimization
- https://supabase.com/docs/guides/database/overview
- https://supabase.com/docs/guides/auth/row-level-security
