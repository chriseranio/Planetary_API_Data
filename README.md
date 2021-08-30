Planetary API data

This project extracts all statistical data on our solar system’s planets and moons and makes it available in SQL tables for analysis.  Through the API process data is extracted from System Solaire’s database. From there Python code converts the data into organized Panda’s DataFrames. The Panda’s DataFrames are then fine tuned and exported to SQL (PostgresSQL). 

Three tables are created into SQL:

- Statistical data on all 9 planets (planets)
- Statistical data on all the solar system moons (moons)
- A melted table with only two columns that aligns the planets with their respective moons (moons_melted)

How it works: 

1) Run each Jupyter notebook cell 
2) With PostgreSQL open, all data will be outputted and made available for analysis
3) It’s recommended the accompanying SQL script be run in Postgres so querying can be done

Future versions:

- Plotting and graphing to be added and DataFrame / SQL data sets to be expanded on 
