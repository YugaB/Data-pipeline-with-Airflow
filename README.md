## Data-pipeline-with-Airflow
Built data pipeline which extracts movie data from 3 csv files and process it by merging, aggregating movie ratings using Python and Apache Airflow.

### Datasets Used:
1. movie.csv
2. rating.csv
3. tag.csv

### Python Libraries used:
1. pandas
2. sqlalchemy
3. airflow
4. datetime

### Functionalities implemented:
1. Data extracted from csv files
2. Merged and aggregated movie ratings
3. Loaded data to Postgres database
4. Created data pipeline using DAGs workflow to carry out above three tasks
5. Learned task branching, DAG Chaining, Variables passing and Hooks
