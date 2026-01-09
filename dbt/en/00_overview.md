# dbt - Overview

## What is dbt?
- dbt (data build tool) is use to transform data in the warehouse using SQL.
- Focuses on transformation, testing and documentation.

## Why I use dbt in projects
- Version control for SQL logic
- Modular and reusable models
- Built-in testing
- Clear separation between raw, staging, and mart layers

# Typical dbt project structure
- 'staging': clean & standardize source data
- 'intermediate': complex joins & transformations
- 'marts': business-level tables for analytics

# Key concepts focus on
- Models
- Materializations
- Tests
- Sources
- Macros

# Notes
- dbt works best when modeling is clear from the beginning
- Naming conventions are critical
