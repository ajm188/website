---
title: Mount unregister
series: vtctldclient
commit: f4b8361bc1e8c73cc17ec4663ee932677761f894
---
## vtctldclient Mount unregister

Unregister a previously mounted external Vitess Cluster.

```
vtctldclient Mount unregister
```

### Examples

```
vtctldclient --server localhost:15999 mount unregister ext1
```

### Options

```
  -h, --help   help for unregister
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient Mount](../)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.

