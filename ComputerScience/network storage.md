![[Pasted image 20220310110135.png]]

Network systems for data persistence store information in nodes (records) related by edges (links), creating a graph of data. This allows for [[one-to-one]], [[one-to-many]], and [[many-to-many]] relationships, with the caveat that *cycles are note allowed*. In short, this model utilizes **directed, acyclic graphs.**

The principal challenge for networked data persistence is complexity: it is hard to design and maintain, and changes are complex and expensive. 

RDBMS systems create an interface to abstract over much of this complexity while robustly ensuring certain guarantees about data integrity, etc. 