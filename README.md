```
cd server
swagger generate server -a factory -A factory -t gen -f ../swagger/swagger.yaml
go run gen/cmd/factory-server/main.go --host 0.0.0.0 --port 3000
```