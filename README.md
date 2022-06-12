# static-files
A dead simple static file server with nginx.

```bash
docker run -p 8080:80 -v /path/to/static:/app/static ghcr.io/woooferz/static-files:main
```

That will serve your static content on port 8080.