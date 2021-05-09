###
will generate pb.go file
```
protoc -I. --go_out=plugins=grpc:. proto/consignment/consignment.proto
