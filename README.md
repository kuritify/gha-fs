# gha-fs


## [acts](https://github.com/nektos/act)


``` shell
$ act --container-architecture=linux/amd64 --list
 ```


## with inputs
```
$ act --container-architecture=linux/amd64 -j hoge --eventpath act-events/dipatch.event
$ cat act-event/dipatch.event
{
  "inputs": {
    "isBuildPDF": true
  }
}
```
