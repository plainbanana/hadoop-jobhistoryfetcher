# olivine
A simple command to fetch hadoop mapreduce job histories.

## install

`make` or `go get "github.com/plainbanana/olivine"`

## usage

```
$ olivine --hostfile jobhistorynodes > olivine.csv
```

## help

```
$ olivine --help
A command to fetch hadoop job histories.

Usage:
  olivine [flags]
  olivine [command]

Available Commands:
  help        Help about any command
  plot        Visualize data.

Flags:
  -h, --help              help for olivine
      --hostfile string   Specify target hosts from a hostfile. default target is localhost.
      --log string        Specify olivine minimun log level. {trace, debug, info, warn, error, alert} (default "info")
  -p, --port string       Specify the port where target hadoop job history server running on hosts. (default "19888")

Use "olivine [command] --help" for more information about a command.
```
