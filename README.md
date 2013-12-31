sqlapp
======

A repository of scripts to generate SQL statements

This script creates a screate table statement in SQL by feeding it  a CSV file.  

Usage:

sql = build_sql('/path/to/yourcsvfile.csv', tablename = 'yourtable', decimalplace= 2, padding =3)
print sql
