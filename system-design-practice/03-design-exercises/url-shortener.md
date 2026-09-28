# URL Shortener

## Requirements

### Functional
- Create a short URL
- Redirect to the original URL
- Optional expiration
- Basic click analytics

### Non-functional
- Low redirect latency
- Highly available
- Horizontally scalable

## High-level design

```text
Client
  |
API Gateway / Load Balancer
  |
URL Service
  |
  +---- Cache
  |
  +---- Database
```

## API

```http
POST /api/shorten
GET  /{shortCode}
```

## Questions to explore
- How are short codes generated?
- How do we avoid collisions?
- Should redirects be cached?
- How do we handle expired URLs?
- How would the database scale?
