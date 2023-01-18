# Ubuntu20-Node18-code-complexity

It contains the following:

- Ubuntu 20.04
- NodeJS v18
- pnpm
- code-complexity

### Docker

Docker Login:

```cmd
    docker login gitlab-master.nvidia.com:5005
```

Docker Build:

```cmd
    docker build -t stojadinovicp/ubuntu20-node18-code-complexity:latest .
    docker push stojadinovicp/ubuntu20-node18-code-complexity:latest
    docker image prune -f
```

Docker Cleanup:

```cmd
    docker builder prune
```

Docker Extreme cleanup:

```cmd
    docker system prune
```
