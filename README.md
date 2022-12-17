## Log daemon
1. put below lines in you .bashrc with proper directory configuration or execute it before using this branch 
```
    export GOROOT=/usr/lib/go/bin
    export GOPATH=~/Code/golang                  // your go work space directory
    export GOBIN=$GOPATH/bin
    go env -w GO111MODULE=on
```
To understand more about GOPATH/GOBIN refer this page : https://github.com/golang/vscode-go/blob/master/docs/gopath.md/usr/lib/go/bin