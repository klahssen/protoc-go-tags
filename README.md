# protoc-go-tags

A fork from https://github.com/dkfbasel/protobuf.git that helps using custom go-tags on .proto files.
Need to prepend a comment to a message's field, then run protoc-gen-go and later protoc-go-tags on the output files (.pb.go)


#### Use-cases
This can be useful to specify database colomn names or other custom tags that would be used when marshaling/validating
