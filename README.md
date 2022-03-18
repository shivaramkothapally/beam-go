# beam-go
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

go install github.com/apache/beam/sdks/v2/go/examples/wordcount@latest

wordcount --input sample.txt --output counts
