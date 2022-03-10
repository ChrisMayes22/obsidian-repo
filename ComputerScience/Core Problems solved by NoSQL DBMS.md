NoSQL DBM systems tend to highlight three features as setting them apart:

1) Scalability - RDBMS tend to be difficult to scale, since they favor [[scaling up]]. NoSQL tend to be built on clusters of servers, which makes it easier to instead favor [[scaling out]].
2) Flexibility - [[schema-less]] databases can more easily accept changed or upgraded functionality, improving their extendability.
3) Availability - Because NoSQL dbs tend to be built on clusters of servers, they can adjust with minimal IT intervention if a server goes down in a planned or unplanned way.

These each respond to a shortcoming to [[Core Problems Solved by RDBMS]]:

1) RDBMS's have difficulty with large read/write volume in contexts where
2) There is a low tolerance for response latency and 
3) High availability is required

RDBMS solutions tend to be expensive and limited (scaling up) or dangerous ([[denormalization]]).