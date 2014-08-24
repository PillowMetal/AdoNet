AdoNet
======

Console application to demonstrate the countless methods of connecting to a database in C#.

Through a character based menu, this app calls functions to connect and retrieve data from SQL Server, Adaptive Server Anywhere, and SQL Anywhere using native client drivers as well as the more advanced LINQ and EF methods.

Although there is a mixture of private, AdventureWorks, and Northwind databases being used, you can edit the connection strings in the .config file, settings, class, or code itself to suit your needs.

The app also contains a small library of functions to get connection strings and providers, as well as encrypt them in the .config file.

Here are the functions implemented and called from the menu:

OleDb
Odbc
SqlClientEmbedded
SqlClientAttached
AseClient
SQLAnywhere
EntityClient
StoreQueryAnonymous
StoreQueryTyped
StoreQueryEntity
ObjectQueryAnonymous
ObjectQueryTyped
ObjectQueryBuilder
LinqToEntities
LinqToSql
GetProviderFactoryClasses
GetConnectionStrings
GetConnectionStringByProvider

Here are the lbrary functions called at some point in the code:

EncryptConnectionStrings
GetConnectionStringByName
GetConnectionStringByProvider
GetProviderByName
