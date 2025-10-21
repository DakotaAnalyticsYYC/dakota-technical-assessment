# dbt Transformation Layer

Build dbt models to transform raw data into analytics-ready tables.

## Requirements

- Initialize a dbt project: `dbt init` (docs: https://docs.getdbt.com/)
- Organize models in a layered architecture (your choice of pattern)
- Include data quality tests
- Document your models
- Configure profiles for PostgreSQL connection

## What We're Looking For

- Thoughtful model organization
- Appropriate use of incremental models where needed
- Data quality tests on critical assertions
- Documentation in schema.yml files
- Your rationale for architecture choices (medallion, Kimball, other?)

## Setup

Use `uv` for dependency management:

```bash
uv pip install dbt-postgres
dbt init
```

Show us how you structure a transformation pipeline. The architecture choices are yours to make and justify.
