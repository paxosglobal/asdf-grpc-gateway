# asdf-grpc-gateway

[![Build Status](https://travis-ci.com/paxosglobal/asdf-grpc-gateway.svg?branch=master)](https://travis-ci.com/paxosglobal/asdf-grpc-gateway)

[grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) code generation tool
plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

This plugin adds two binaries intended for use with `protoc`:

- `protoc-gen-grpc-gateway` generates RESTful JSON API -> grpc reverse-proxy Go code.
- `protoc-gen-swagger` generates Swagger definitions for the RESTful API.

See https://github.com/paxosglobal/asdf-protoc to install protoc with asdf.

## Install

```
asdf plugin-add grpc-gateway https://github.com/paxosglobal/asdf-grpc-gateway.git
```

## Use

See [asdf](https://github.com/asdf-vm/asdf) for how to use asdf.
