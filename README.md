# go-swagger-basic-auth-template
go-swagger bootstrap with basic auth

## Install Go-swagger

```bash
go get -u github.com/go-swagger/go-swagger/cmd/swagger
```

then execute `swagger -h`

```bash
Usage:
  swagger [OPTIONS] <command>

Swagger tries to support you as best as possible when building APIs.

It aims to represent the contract of your API with a language agnostic description of your application in json or yaml.


Application Options:
  -q, --quiet              silence logs
  -o, --output=LOG-FILE    redirect logs to file

Help Options:
  -h, --help               Show this help message

Available commands:
  expand    expand $ref fields in a swagger spec
  flatten   flattens a swagger document
  generate  generate go code
  init      initialize a spec document
  mixin     merge swagger documents
  serve     serve spec and docs
  validate  validate the swagger document
  version   print the version
```

if u see text above... the swagger is available~

## To Generate Ur Code?

```bash
swagger generate server -f swagger.yml
```