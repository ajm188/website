---
title: Mount show
series: vtctldclient
commit: f4b8361bc1e8c73cc17ec4663ee932677761f894
---
## vtctldclient Mount show

Show attributes of a previously mounted external Vitess Cluster.

```
vtctldclient Mount show
```

### Examples

```
vtctldclient --server localhost:15999 Mount Show ext1
```

### Options

```
  -h, --help   help for show
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient Mount](../)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.

