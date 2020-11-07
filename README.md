# Serving React App with Nginx through Docker

# Build Image

```bash
docker build -t cra-nginx .
```

# Start a Container

```bash
docker run --rm -it -p 8080:80 cra-nginx
```
