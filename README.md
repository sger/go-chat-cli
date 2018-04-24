# Go gRPC Chat CLI

Go gRPC Chat CLI is simple chat application written in Go programming language.It uses [gRPC](https://github.com/grpc/grpc-go) for network communication and [Protocol Buffers](https://github.com/golang/protobuf).

## Installation

 Via `go-get`:

 ```sh
$ go get github.com/andefined/go-chat-cli
$ cd go-chat-cli
$ make build
```
## Build the server

```sh
$ cd go-chat-cli
$ cd server
$ go run server.go
```
## Build the client

```sh
$ cd go-chat-cli
$ cd cli
$ go run cli.go
```
License
-----

Go gRPC Chat CLI is available under the MIT license. See the LICENSE file for more info.