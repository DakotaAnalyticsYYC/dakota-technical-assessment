# Orchestration

Implement workflow orchestration for the data pipeline.

## Requirements

Choose and implement an orchestration tool to manage:
- Data ingestion from public data source or EIA (daily batch?)
- Data ingestion from FastAPI service (frequent/streaming?)
- dbt transformations
- Data quality checks
- Report generation
- Error handling and retries

## Tool Options

Research and choose from modern orchestration frameworks:
- Dagster
- Apache Airflow
- Prefect
- Mage AI
- Others

Document your choice and why

## What We're Looking For

- Clear rationale for your tool choice
- Well-structured workflows/DAGs/assets
- Appropriate scheduling
- Error handling and monitoring
- Testing

Document your decision and trade-offs in `/docs/decisions.md`
