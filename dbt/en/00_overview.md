# dbt - Overview

## What is dbt?
- dbt (data build tool) is a data processing framework, based on Python, that allows to apply transformation on data inside a data warehouse like Snowflake, Redshift, BigQuery, but also PostgreSQL.
- dbt is the T in ELT. It takes your code, compiles it to SQL, and then runs against your database.
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

# dbt file types
- .md files: documentation files used for documenting the dbt models.
- .yml files: configuration files.
- .sql files: contains models and tests.

# dbt Cloud & dbt Core
dbt comes in 2 variants:
- dbt Cloud: a web based application along with an IDE (Integrated Development Environment)
- dbt Core: Command Line Interface, which is run by a terminal. Its an open-source package that can be installed into a Python environment.

# Notes
- dbt works best when modeling is clear from the beginning
- Naming conventions are critical
