FROM python:3.11

WORKDIR /great_expectations

# Install Great Expectations and any other required packages
RUN pip install great_expectations pandas sqlalchemy snowflake-sqlalchemy duckdb-engine

# Copy Great Expectations configuration
COPY great_expectations /great_expectations

# Command to run Great Expectations
CMD ["great_expectations", "docs", "build", "--view"]