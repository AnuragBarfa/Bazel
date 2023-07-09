# Run cmd "make gen" from proto directory
gen:
	protoc --proto_path=. ./*.proto --go-grpc_out=.

# Run cmd "make clean" from proto directory
clean:
	rm -f *.pb.go

# Run cmd "make run" from proto directory
run:
	go run ../service/hello.go