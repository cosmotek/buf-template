# buf-template

## Tools

- `buf`: This is a tool used to handle gRPC code-gen, break detection and linting. Install it using `brew install bufbuild/buf/buf`
- `protoc-gen-gotemplate`:
This is a protoc plugin used to execute Go templates using the contents of a protobuf/gRPC schema. This can be used to generate almost anything, but in this project it is used to generate API documentation `protoc-gen-gotemplate` may be installed by executing `go install moul.io/protoc-gen-gotemplate@latest`
- `protoc-gen-go-grpc`: `go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.2`
- `protoc-gen-go`: `go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.28`