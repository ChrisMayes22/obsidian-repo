This type of NoSQL DBMS stores all data as a set of key-value pairs. Naming conventions can vary, but it is possible to implement data structures like [[tables]] by adopting the following convention:

\[table\]\[[[PrimaryKey]]\].\[column\]

e.g.

customer5141.address

Key-value DBs can also implement [[namespacing]] through the use of buckets, which can in turn be used to implement something functionally similar to a schema.

Of the NoSQL solutions, key-value DBs are the simplest and the poorest in features. They do not allow for columnar constraints, JOIN queries, etc.
