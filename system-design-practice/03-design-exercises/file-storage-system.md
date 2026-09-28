# File Storage System

## Requirements
- Upload files
- Download files
- Delete files
- Share files
- Large file support

## Architecture

```text
Client
  |
API
  |
Metadata DB
  |
Object Storage
```

For large files, consider multipart upload and direct client-to-object-storage uploads using temporary signed URLs.

## Questions
- Maximum file size?
- Access control?
- Virus scanning?
- Replication?
- CDN?
- Retention policy?
