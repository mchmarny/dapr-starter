# dapr-http-event-subscriber-template

[![Test](https://github.com/dapr-templates/dapr-http-event-subscriber-template/workflows/Test/badge.svg)](https://github.com/dapr-templates/dapr-http-event-subscriber-template/actions?query=workflow%3ATest) ![Release](https://github.com/dapr-templates/dapr-http-event-subscriber-template/workflows/Release/badge.svg?query=workflow%3ARelease) ![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/dapr-templates/dapr-http-event-subscriber-template) [![Go Report Card](https://goreportcard.com/badge/github.com/dapr-templates/dapr-http-event-subscriber-template)](https://goreportcard.com/report/github.com/dapr-templates/dapr-http-event-subscriber-template)

## template usage 

* Click "Use this template" above and follow the wizard to select owner and name your new repo
* Clone and navigate to your new repo (`git clone git@github.com:<USERNAME>/<REPO-NAME>.git && cd <REPO-NAME>`)
* Initialize your project to set the package names and update imports (`make init`)
* Write your subscription event handling logic 


### common operations

Common operations to help you bootstrap a Dapr HTTP services development in `go`:

```shell
$ make
tidy                           Updates the go modules and vendors all dependencies
test                           Tests the entire project
run                            Runs uncompiled code in Dapr
build                          Builds local release binary
event                          Publishes sample JSON message to Dapr pubsub API
image                          Builds and publish docker image
lint                           Lints the entire project
tag                            Creates release tag
clean                          Cleans up generated files
init                           Resets go modules
help                           Display available commands
```

This project also includes GitHub actions in [.github/workflows](.github/workflows) that test on each `push` and build images and mark release on each `tag`. Other Dapr GitHub templates to accelerate Dapr development available [here](https://github.com/dapr/go-sdk/tree/master/service).

## License

This software is released under the [MIT](./LICENSE)
