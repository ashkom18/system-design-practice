# Job Application Tracker

## Requirements

Users can:
- Create applications
- Update application status
- Record interviews
- Search applications
- View statistics

## Example architecture

```text
React Client
     |
Load Balancer
     |
Spring Boot API
   /     Cache   PostgreSQL
```

## Example entities

```text
User
Application
Company
Interview
Note
```

## Future scaling
- Redis caching
- Read replicas
- Background notifications
- Search service
- Object storage for documents
