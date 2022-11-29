# system-design
study about system-design
Step 1
Review the scalability
-Vertical scaling: Vertical scaling refers to adding more resources (CPU/RAM/DISK) to your server (database or application server is still remains one) as on demand.
-Horizontal scaling: Scaling horizontally involves adding more processing units or phyiscal machines to your server or database.
-Caching: Caching allows you to efficiently reuse previously retrieved or computed data
-Load balancing: Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool. in Horizontal
-Database replication is the frequent electronic copying of data from a database in one computer or server to a database in another -- so that all users share the same level of information.
-Partitioning is the database process where very large tables are divided into multiple smaller parts
-clone
-database
-cach
 Cached Database Queries
 Cached Objects
-Asynchronism 2ways
Step 2
trade-offs:
-Performance vs scalability
 ??????????
-Latency vs throughput
 Generally, you should aim for maximal throughput with acceptable latency.
-Availability vs consistency
 cp, ap but c? a?


Step 3
DNS
pc(name)-ISP DNS SERVER(name)-ROOT DNS SERVER(name)-ISP DNS SERVER(url)-pc(url)-website(url)
Load ballancing
-Round Robin
-Weighted Round Robin
-Least Connections
-Weighted Least Connections
-Random

Step 4
CDN(Content Delivery Network)
-Pull CDN client-server-cdn
-Push CDN client-cdn-server

 Step 5
 Load Balance