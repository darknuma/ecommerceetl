FROM apache/superset

# Install additional dependencies if needed
USER root
RUN pip install snowflake-sqlalchemy

# Switch back to using the `superset` user
USER superset

# You can add custom initialization scripts here if needed