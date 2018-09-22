
# go-web-assembly

[Go 1.11 WebAssembly](https://github.com/golang/go/wiki/WebAssembly)

### example

```
$ open https://arakawamoriyuki.github.io/go-web-assembly/index.html
```

1. console開いてrunボタンを押す。
2. consoleに `Hello Go WebAssembly` が出る (`src/main/main.go` がブラウザで動作)

## ENV

```
$ sw_vers
ProductName: Mac OS X
ProductVersion:	10.12.6
BuildVersion: 16G29

$ go version
go version go1.11 darwin/amd64
```

## Go 1.11 WebAssembly

### WebAssemblyについて

TODO:

### Hello Go WebAssembly

[サクッと Go → WebAssembly を試す](https://qiita.com/cia_rana/items/bbb4112b480636ab9d87)

```
$ curl -o public/index.html https://raw.githubusercontent.com/golang/go/master/misc/wasm/wasm_exec.html
$ curl -o public/wasm_exec.js https://raw.githubusercontent.com/golang/go/master/misc/wasm/wasm_exec.js
$ GOOS=js GOARCH=wasm go build -o public/test.wasm src/main/main.go
$ go run src/server/server.go
$ open http://localhost:5555/
```

### できる事

TODO:
