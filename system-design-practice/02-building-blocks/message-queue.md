# Message Queues

Queues decouple producers from consumers.

```text
Producer --> Queue --> Consumer
```

Useful for:
- Email processing
- Notifications
- Background jobs
- Event processing

Benefits:
- Traffic buffering
- Asynchronous processing
- Retry mechanisms
- Independent scaling

Trade-off:
The system becomes more complex and processing may become asynchronous.
