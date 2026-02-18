# Docker Configuration

Docker and container orchestration files for the Self-Appraisal system.

## Files

- `docker-compose.yml` - Production Docker Compose configuration
- `docker-compose.dev.yml` - Development Docker Compose configuration
- `Backend.Dockerfile` - Backend container image
- `Frontend.Dockerfile` - Frontend container image
- `nginx.conf` - Nginx configuration for frontend

## Usage

### Development
```bash
docker-compose -f docker-compose.dev.yml up
```

### Production
```bash
docker-compose -f docker-compose.yml up -d
```
