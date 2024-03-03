# gha-fs


## [acts](https://github.com/nektos/act)


``` shell
$ act --container-architecture=linux/amd64 --list
 ```


## with inputs
```
$ act  --container-architecture=linux/amd64 -j hoge --input-file act-events/dispath.input
$ cat act-event/dipatch.event
{
  "inputs": {
    "isBuildPDF": true
  }
}
```

## action lint
```
$ go install github.com/rhysd/actionlint/cmd/actionlint@latest
$ /Users/shintaro.kurihara/go/bin/actionlint
```


