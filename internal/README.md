# Proto Generation
## Installing requirements
See: https://grpc.io/docs/languages/go/quickstart/
```
go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28                
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2            
```

## Generation
Navigate to the `internal` dir and execute the following command:
```
protoc --go_out=. ./checkin.proto
```