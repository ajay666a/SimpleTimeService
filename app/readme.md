# SimpleTimeService

A minimalist Flask microservice that returns the current UTC timestamp and client IP.

## Build

```bash
docker build -t simple-time-service .
```

## Run

```bash
docker run -p 8080:8080 simple-time-service
```

Visit http://localhost:8080 to test.

## JSON Output Example

```json
{
  "timestamp": "2025-07-10T10:00:00Z",
  "ip": "127.0.0.1"
}
```
