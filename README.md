# skind - Simple Kubernetes in Docker

skind is a simple CLI tool built on top of [kind](https://kind.sigs.k8s.io/)

kind is allows to provision local kubernetes clusters useful for testing purposes.

skind just makes easier and straightforward to deploy kind clusters.

## Installation
Download the script and place it in your PATH
```
curl https://raw.githubusercontent.com/famartinrh/skind/master/skind --output $HOME/bin/skind && chmod +x $HOME/bin/skind
```

## Usage
```
$ skind

skind [Simple Kubernetes In Docker]
Version: 0.0.1
https://github.com/famartinrh/skind
Usage: skind [command]
Commands:
  start    Starts an opinionated Kind cluster
  stop     Stops the Kind cluster
  status   Prints information about the current running cluster
  *        Help

$ skind start
...
$ skind status
...
$ skind stop
...
```