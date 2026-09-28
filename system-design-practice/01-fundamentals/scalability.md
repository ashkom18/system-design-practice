# Scalability Fundamentals

## Vertical scaling
Increase CPU, RAM, or storage on a single machine.

**Pros:** simple to implement.

**Cons:** hardware limits and a single-machine failure domain.

## Horizontal scaling
Add more application instances behind a load balancer.

```text
Client
  |
Load Balancer
  |
  +---- App 1
  +---- App 2
  +---- App 3
```

## Important concepts
- Stateless services
- Load balancing
- Database replication
- Caching
- Partitioning
- Asynchronous processing

## Interview reminder
Always explain what bottleneck appears first and how your design addresses it.
