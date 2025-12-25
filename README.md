# shliftotest
# Military Targets Server
A REST API for managing military targets using Node.js, Express, and File System.

## Endpoints:
- `GET /health` - Check server status.
- `GET /targets` - Get all targets (Supports filters: region, status, minPriority).
- `POST /targets` - Create a new target.
- `PUT /targets/:id` - Update an existing target.
- `DELETE /targets/:id` - Remove a target.