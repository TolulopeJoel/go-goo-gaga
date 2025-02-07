
# HNG Stage 0 API

A simple Go API that returns basic information for HNG internship.

## API Documentation

### Endpoint
`GET /`

### Response Format
```json
{
  "email": "dotolulope2@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/tolulopejoel/go-goo-gaga"
}
```

### Example Usage
```bash
curl https://your-deployed-url.xyz/
```

## Local Setup

1. Clone repository:
```bash
git clone https://github.com/tolulopejoel/go-goo-gaga.git
```

2. Build and run:
```bash
go run stage1.go
```

3. Test endpoint:
```bash
curl http://localhost:8000
```

## Deployment
Deployed using [Render](https://render.com/). The API automatically scales and typically responds in <100ms.


[Looking for Go developers? Hire through HNG](https://hng.tech/hire/golang-developers)


4. **GitHub Repository**:
- Create a public repository on GitHub
- Push your code
- Ensure the repository contains:
  - stage1.go
  - README.md
  - go.mod

**Response Time**: Go's native HTTP server typically responds in <50ms for simple endpoints like this.

**CORS Handling**: The middleware properly handles CORS for all origins and preflight requests.
