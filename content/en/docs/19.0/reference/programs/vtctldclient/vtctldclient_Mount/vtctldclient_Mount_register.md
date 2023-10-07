---
title: Mount register
series: vtctldclient
commit: f4b8361bc1e8c73cc17ec4663ee932677761f894
---
## vtctldclient Mount register

Register an external Vitess Cluster.

```
vtctldclient Mount register
```

### Examples

```
vtctldclient --server localhost:15999 mount register --topo-type etcd2 --topo-server localhost:12379 --topo-root /vitess/global ext1
```

### Options

```
  -h, --help                 help for register
      --topo-root string     Topo server root path.
      --topo-server string   Topo server address.
      --topo-type string     Topo server implementation to use.
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient Mount](../)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.

