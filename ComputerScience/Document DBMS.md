Document DBs are similar to [[Key-Value DBMS]], except they store collections of attributes under keys rather than individual values. This allows them to next documents inside other documents in data structures similar to arrays or hash tables (which is also an important difference from RDBMS, where tables embedded in tables is discouraged).

Document DBMS tend to be [[schema-less]], which means it is particularly important for developers to validate data on the level of the client / API.

In many ways, Document DBMS look similar to hierarchical flat files or data contracts like JSON or XML. A big different from the user's point of view, however, is that most DBMS support a richer [[query language]] that allow for more efficient and more powerful data manipulation.