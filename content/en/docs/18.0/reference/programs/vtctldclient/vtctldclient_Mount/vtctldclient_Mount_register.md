---
title: Mount register
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient Mount register

Register an external Vitess Cluster.

```
vtctldclient Mount register
```

### Examples

```
vtctldclient --server localhost:15999 mount register --name ext1 --topo-type etcd2 --topo-server localhost:12379 --topo-root /vitess/global
```

### Options

```
  -h, --help                 help for register
      --name string          Name to use for the mount.
      --topo-root string     Topo server root path.
      --topo-server string   Topo server address.
      --topo-type string     Topo server implementation to use.
```

### Options inherited from parent commands

```
      --action_timeout duration              timeout to use for the command (default 1h0m0s)
      --andrew-is-testing                    nothing to see here
      --compact                              use compact format for otherwise verbose outputs
      --server string                        server to use for the connection (required)
      --topo-global-root string              the path of the global topology data in the global topology server
      --topo-global-server-address strings   the address of the global topology server(s)
      --topo-implementation string           the topology implementation to use
```

### SEE ALSO

* [vtctldclient Mount](../)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.

