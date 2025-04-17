Keyword,What it does,Example

SELECT -  Specifies which columns to return,SELECT name
FROM -    Specifies which table to query,FROM countries
WHERE -   Filters rows based on a condition,WHERE region = 'Southern Europe'
AND / OR -    Combines multiple conditions,AND isofficial = true
ORDER BY -    Sorts the result rows,ORDER BY population ASC
LIMIT -   Limits the number of rows returned,LIMIT 1
GROUP BY -    Groups rows for aggregation,GROUP BY countrycode
HAVING -  Filters groups created by GROUP BY,HAVING COUNT(*) = 1
JOIN -    Combines rows from multiple tables,JOIN cities ON countries.code = cities.countrycode
AS -  Renames a column or table temporarily,SELECT name AS country_name
