# nosql-challenge
Repository for Monash University Bootcamp Module 12

## File structure
- `NoSQL_setup_starter.ipynb`: Jupyter notebook used to setup the database and add new restaurant
- `NoSQL_analysis_starter.ipynb`: Jupyter notebook used for the analysis
- `Resources`: Directory containing the JSON file used to set up the database

## Importing database from the JSON file
Use the following command line from the root directory:
```
mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json
```