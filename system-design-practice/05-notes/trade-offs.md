# Common System Design Trade-offs

| Decision | Benefit | Cost |
|---|---|---|
| Cache | Lower latency | Stale data / complexity |
| SQL | Strong relational model | Horizontal scaling can be harder |
| NoSQL | Flexible/high-scale workloads | Query/consistency trade-offs |
| Queue | Decoupling | Asynchronous complexity |
| CDN | Faster global delivery | Cache invalidation |
| Read replicas | More read capacity | Replication lag |
| Microservices | Independent deployment/scaling | Operational complexity |
| Monolith | Simpler development/deployment | Tighter coupling at larger scale |

The goal of system design is not to find one universally correct architecture. Explain assumptions, constraints, and trade-offs.
