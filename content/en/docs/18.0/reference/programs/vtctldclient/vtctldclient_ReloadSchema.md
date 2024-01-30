---
title: ReloadSchema
series: vtctldclient
commit: f4d1487c72392cec566ed9ab39a00c7d027cc8ee
---
## vtctldclient ReloadSchema

Reloads the schema on a remote tablet.

```
vtctldclient ReloadSchema <tablet_alias>
```

### Options

```
  -h, --help   help for ReloadSchema
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

