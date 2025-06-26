# Example: Running all models in your project
DBT_PROJECT_PATH=~/your_dbt_project docker compose run --rm dbt dbt run

# Example: Running a specific model
DBT_PROJECT_PATH=~/your_dbt_project docker compose run --rm dbt dbt run --select your_model_name