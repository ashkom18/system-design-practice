# Chat System

## Requirements
- One-to-one messaging
- Group conversations
- Message history
- Online status
- Delivery status

## High-level design

```text
Client
  |
WebSocket Gateway
  |
Chat Service
  |
  +---- Message Queue
  |
  +---- Message Database
  |
  +---- Presence Store
```

## Key questions
- WebSocket or polling?
- How are messages ordered?
- How are offline users handled?
- How do we scale WebSocket connections?
- How is message history stored?
