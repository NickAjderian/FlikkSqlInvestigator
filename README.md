# FlikkSqlInvestigator
Extracts object information from a SQL database to help you work with a legacy system
# Motivation
You've got a SQL database, maybe created by someone else. You need to work on it.
How do you easily find where the data for a view comes from, when it may come from tables, other views, functions or stored procs?
The FlikkSqlInvestigator gives you a searchable list of objects, the text that defines them and the objects they depend on.
# Has it been done before, better?
[Similar Systems](https://github.com/NickAjderian/FlikkSqlInvestigator/wiki/Similar-Systems)
# How It Works
Investigator.Sql.flikk.net is a C# DLL that opens the database and uses the SQL sys objects to extract dependency information. Where this is not enough it also gets the SQL text definitions of the objects (so you can also search in comments). It does this for tables, views, stored procs, user defined functions and trigggers.
# How to Use It
There will be a simple UI and a more advanced object browser and modeller or you can write your own.
