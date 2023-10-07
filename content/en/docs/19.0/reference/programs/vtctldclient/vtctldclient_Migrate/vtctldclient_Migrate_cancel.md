---
title: Migrate cancel
series: vtctldclient
commit: f4b8361bc1e8c73cc17ec4663ee932677761f894
---
## vtctldclient Migrate cancel

Cancel a Migrate VReplication workflow.

```
vtctldclient Migrate cancel
```

### Examples

```
vtctldclient --server localhost:15999 Migrate --workflow import --target-keyspace customer cancel
```

### Options

```
  -h, --help   help for cancel
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --format string             The format of the output; supported formats are: text,json. (default "text")
      --server string             server to use for connection (required)
      --target-keyspace string    Target keyspace for this workflow.
  -w, --workflow string           The workflow you want to perform the command on.
```

### SEE ALSO

* [vtctldclient Migrate](../)	 - Migrate is used to import data from an external cluster into the current cluster.

