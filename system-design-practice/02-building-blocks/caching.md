# Caching

Caching stores frequently accessed data closer to the application.

```text
Client -> API -> Cache
                 |
                 +-- hit --> return data
                 |
                 +-- miss -> Database
```

Important concepts:
- Cache-aside
- TTL
- Eviction policies
- Cache invalidation
- Hot keys

Trade-off:

**Faster reads** versus **stale data and cache complexity**.
