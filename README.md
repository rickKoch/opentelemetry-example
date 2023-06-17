# OpenTelemetry example in Golang

install dependencies
```
go mod tidy
```

# run the application

```
docker-compose up --build --detach
go run ./

curl -I http://127.0.0.1:8081/serviceA
```

You can see the traces in Jaeger UI at http://localhost:16686/search
You can see metrics in Prometheus UI at http://localhost:9090/graph
