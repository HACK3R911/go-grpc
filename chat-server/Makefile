LOCAL_BIN:=$(CURDIR)/bin

install-golangci-lint:
<<<<<<< HEAD
	GOBIN=$(LOCAL_BIN) go install github.com/golangci/golangci-lint/cmd/golangci-lint@v1.64.7
=======
	GOBIN=$(LOCAL_BIN) go install github.com/golangci/golangci-lint/cmd/golangci-lint@v1.61.0
>>>>>>> 3b05e48f8d6757471d3715ff772cec772f84d7f6

lint:
	$(LOCAL_BIN)/golangci-lint run ./... --config .golangci.pipeline.yaml