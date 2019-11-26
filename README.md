# datacamp-dataeng
Datacamp Data Engineer course using python

## Query SQL using Pandas
```
sql = """
SELECT first_name, last_name FROM "Customer"
ORDER BY last_name, first_name
"""
data = pd.read_sql(sql, db_engine)

# Show the first 3 rows of the DataFrame
print(data.head(3))

# Show the info of the DataFrame
print(data.info())
``` 

