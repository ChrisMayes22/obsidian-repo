![[Pasted image 20220310110522.png]]

Relational Databases seek to improve on the limitations [[flat file storage]], [[hierarchical storage]], and [[network storage]]. On a broad theoretical level, it uses [[relational algebra]] as a model to eliminate certain categories of errors, often with the goal of achieving [[ACID]] compliance.

RDBM systems consist of four main functions:

## Storage Management
A challenge for any data storage system is fast [[random access]], potentially across large physical storage systems. RDBMS's store data on disks or flash drives but use [[indexes]] to enable rapid access to individual pieces of data. 


## Memory Management
An RDBMS should provide for garbage disposal in a way that handles the fact that write operations are much slower and more resource-intensive than read operations, **but** write operations (in many systems) put a lock on the db and so block other operations (so as to maintain atomicity between operations and consistency between views).


## Data Dictionary
The data dictionary tracks the structure of data to be stored, generally in terms of [[schemas]], [[tables]], [[indexes]], [[views]] and [[constraints]].


## Query Language
The query language (which is almost always some variation on [[SQL]]) defines data structures and manipulates data to enable ACID-compliant CRUD operations. 