# pytools
Useful tools in python

## TableFormatter
Often times, data lists need to be output in tabular format. Here is a sample that allows specifying table heading and data rows.
Command line tools (for example, queries from db) typically present output as tabular data. This script assumes a table heading and rows of data. Sometimes the rows may not be complete, so there is ability to pad remaining columns. There is also the ability to left, center or right align the text within the column.

The output looks like the example below:
```
+----------------+----------------+----------------+----------------+----------------+----------------+
|    column_1    |    column_2    |    column_3    |    column_4    |    column_5    |    column_6    |
+----------------+----------------+----------------+----------------+----------------+----------------+
|val1            |value2          |value 3         |-               |-               |-               |
|one is alone    |two is a company|three is a crowd|-               |-               |-               |
|test            |-               |-               |-               |-               |-               |
|1               |two             |False           |(3, 4, True)    |-               |-               |
|test            |value2          |value 3         |value2          |value 3         |-               |
+----------------+----------------+----------------+----------------+----------------+----------------+
```
