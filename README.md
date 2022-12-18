## Log daemon
1. put below lines in you .bashrc with proper directory configuration or execute it before using this branch 
```
    export GOROOT=/usr/lib/go/bin               // it depends on your OS system go installation & your choice
    export GOPATH=~/Code/golang                 // your go work space directory
    export GOBIN=$GOPATH/bin
    go env -w GO111MODULE=auto
    export PATH=$PATH:$GOROOT/bin


    Recoomend to clone this repo on $GOPATH/src/
```
To understand more about GOPATH/GOBIN refer this page : https://github.com/golang/vscode-go/blob/master/docs/gopath.md/usr/lib/go/bin