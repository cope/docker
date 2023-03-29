# Ubuntu20-Node18-code-complexity

It contains the following:

- Ubuntu 20.04
- NodeJS v18
- pnpm
- code-complexity

### Docker

#### Docker Login: ```docker login docker.com```

#### Docker Build and push:
```cmd
    docker build -t stojadinovicp/ubuntu20-node18-code-complexity:latest .
    docker push stojadinovicp/ubuntu20-node18-code-complexity:latest
    docker image prune -f
```

#### Docker Cleanup: ```docker builder prune```
#### Docker Extreme cleanup: ```docker system prune```
