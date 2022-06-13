
* System Design Basics
  * Scalability 
    * Vertical scaling 
      * Advantages and disadvantages 
    * Horizontal scaling
      * Advantages and disadvantages 
    * When to use vertical vs horizontal scaling
    * Caching
    * Load balancing
    * Database replication
    * Database partitioning  
  * Performance vs Scalability
    * When do you have a performance problem? 
    * When do you have a scalability problem?
  * Latency vs Throughput
    * Define latency
    * Define Throughput
  * CAP theorem 
    * What is the CAP theorem ?
    * Types of the systems?
    * What kind of data stores belong to
      * CA
      * CP
      * AP
    * Can you 'get around' or 'beat' the CAP Theorem?
    * What is a Partition in CAP Theorem?
    * How to choose between CP (consistency) and AP (availability)?
    * Explain what is PACELC Theorem?
      * PA/EL
      * PC/EC
      * PA/EC
  * Consistency patterns
     * Types of consistency?
       * Weak 
       * Eventual 
       * Strong
  * Availability patterns
    * Patterns to support high availability? 
    * Fail over ?
      * Active passive (2)
      * Active Active 
      * Disadvantages of failover 
  * Replication?
    * Primary- secondary  
    * Primary - Primary 
    * Disadvantages of replication?
  * What Do You Mean By High Availability (HA)?
    * 99.9%
    * 99.99%
  * Availability in parallel vs sequence
 * Domain name system 
   * What is DNS?
   * How does DNS work ?
   * How does DNS route traffic?
   * Parts of a URL(Domain)?
   * Different types of internet domains?
     * Com vs org vs edu etc
  * CDN
    * What is a CDN?
    * Types of CDN ?
    * Example of a CDN?
    * How does a CDN work?
    * Why are CDN needed?
    * Who uses CDN?
    * What are the benefits of using CDN?
    * What are the disadvantages of using CDN?
  * Load balancers 
    * What are load balancers?
    * Why do we need load balancers?
    * Where are load balancers typically placed?
    * How can we achieve load balancing?
    * What are different categories of load balancers?
      * L4
      * L7
      * GSLB
    * Load balancing algorithms 
      * RR
      * WRR
      * Least connections
      * Least response time 
      * IPHash
    * What additional tasks can load balancers do?
      * SSL termination
      * DDOS
    * How to avoid SPOF ?
  * Proxy 
    * What is a proxy?
    * What is a forward proxy?
    * What is a reverse proxy?
    * Advantages and disadvantages for proxy?
  * API Gateway /Application layer 
  * What is an API gateway?
  * Why use API gateway?
  * Core functionalities ?
  * While designing APIS
    * Naming 
    * URI definition 
    * Single responsibility principle
    * number of params
    * Type of request GET/POST/PUT/PATCH/DELETE
    * Authentication 
    * Return status - 200, 201, 400,401, 403,404, 429, 500, 503
  * Additional items to discuss
    * Rate limiting 
    * API versioning 
    * Error handling 
    * Caching 
  * Listviews (special operations)
    * Pagination 
    * Sorting 
    * Searching 
    * GET/POST
  * Alias
  * Documentation 
  * Cheat sheet for each API(s)
    * Objects 
    * Each object - kind of CRUDL
      * URI
      * Request 
        * Type
        * params
      * Response 
        * Response code 
        * Happy 
        * Error
  * Microservices 
    * What are microservices?
      * Define ?
      * Components of microservices architecture ?
         * API gateway
         * Microservices
           * Management 
           * Service discovery
       * Benefits of microservice architecture?
         * Independent development
         * Independent deployment 
         * Fault isolation
         * Granular scaling 
         * Mix and match
       * Monolithic vs Microservives?
       * Features of micro services 
         * Decoupling 
         * Componentization
         * Business capabilities
         * Autonomy
         * CD
         * Responsibility 
         * Decentralized governance
         * Agility 
       * Challenges of microservice architecture?
Decentralization
Distributed transactions
Types of approach ?
Hybrid vs purist
Testing in micro services 
Unit testing 
Integration/contract testing 
End to end test (workflow)
User testing 
Microservices communication?
Sync 
HTTP
gRPC
Async 
Kafka
Distributed transactions?
2PC
TC/C
Saga
Microservice deployment  
Service discovery (Zookeeper) 
Database (RDBMS)
ACID 
Scaling relational database
Replication 
Federation 
Sharding 
Denormalization
Replication
Types 
Primary - secondary
Primary - primary
Strategies 
Log based data replication
Statement based log
Row based log 
Full table data replication 
Snapshot replication
Transactional replication
Key based incremental database replication
DB sharding 
Horizontal or range based sharing 
Vertical sharing 
Hash based sharding 
Consistent hashing
Directory based sharding (Look up service)
No Sql 
What is no SQL database? (Lose ACID, eventual consistency)
Key value (EC, D, M)
Document store
Column db 
Graph 
Time series 
BASE 
Basically available
Soft state
Eventual consistency
Sql Vs no Sql
Caching 
Kinds of caching 
Client side caching 
CDN caching
Web server caching 
Database caching 
Application caching 
Cache invalidation 
Write thru cache
Write around cache
Write back cache 
Cache eviction policy 
FIFO
LIFO
LRU
MRU
LFU
RR
Async methodology 
Message queue 
One to one
Pub-sub model
One to many
Kafka vs Active Mq
Security /Authentication
JWT
oAuth 2
Long-polling vs websockets vs server sent
Ajax polling 
Http long polling 
Websockets
Server sent events 
Leader election 
Concept 
Leader election 
Heart beat /id
Zookeeper based on host recent data
Rate limiting 
What is rate limiting?
What are the different kinds of rate limiting?
Client side 
Server side 
What are the advantages of rate limiting?
Prevention of resource starving
Managing policy and quota
Controlling flow 
Cost
Strategies for rate limiting?
No rate limiting
Pass through
Enforce rate limiting
Delay response
Algorithms for rate limiting?
Token 
Leaky bucket
Fixed window
Sliding window
Rate limiting headers?
Limit
Remaining 
Retry after
Performance optimization
Geo Based 
Logging and monitoring 
Why log 
Eros
Access logs 
Why monitor
Map reduce 
Map step - map function <key, value>
Shuffle - Same key to same machine 
Reduce - Transform the data into meaningful data 

