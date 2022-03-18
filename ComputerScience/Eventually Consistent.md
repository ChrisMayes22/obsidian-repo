Eventually Consistent is one of the BASE standards that NoSQL DBMS often adhere to. It means that there might be small windows of time where different DB servers on a cluster are inconsistent with each other. 

Transaction [[Atomicity]] comes at a cost when multiple servers involved: for a transaction to truly be atomic and guarantee consistency, then it would have to be fail-close for a set of write operations across the entire cluster of servers. This can be unacceptably slow.

Instead, NoSQL DBMS will often accept a change from a query for some servers, notify the user of the change (completing a transaction and thus creating inconsistency within the cluster), and then finish updating the remaining servers. This is often implemented using a [[quorum]] system.