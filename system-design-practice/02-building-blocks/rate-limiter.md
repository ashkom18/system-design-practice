# Rate Limiter

A rate limiter protects an API from excessive requests.

Example policy:

```text
100 requests / minute / user
```

Common algorithms:
- Token bucket
- Leaky bucket
- Fixed window
- Sliding window

Example:

```text
Client
  |
Rate Limiter
  |---- allowed ----> API
  |
  +---- rejected ---> HTTP 429
```
