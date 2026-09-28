# Load Balancer

A load balancer distributes requests across multiple application servers.

```text
             +--> App Server 1
Client --> LB+--> App Server 2
             +--> App Server 3
```

Common responsibilities:
- Traffic distribution
- Health checks
- TLS termination
- Connection management

Questions to consider:
- What happens when an instance fails?
- Is the application stateless?
- Where is session state stored?
