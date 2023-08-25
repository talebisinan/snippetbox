# Snippetbox

#### Runnnig the application (default port 4000)
Pass -addr flag to change the port like `-addr=":80"`.
```bash
go run ./cmd/web
```

#### Viewing all flags
```bash
go run ./cmd/web -help
```

```bash
go run ./cmd/web -addr=":4000" -dsn="user:pass@/snippetbox?parseTime=true"
```

