---
title: SetShardIsPrimaryServing
series: vtctldclient
commit: f4d1487c72392cec566ed9ab39a00c7d027cc8ee
---
## vtctldclient SetShardIsPrimaryServing

Add or remove a shard from serving. This is meant as an emergency function. It does not rebuild any serving graphs; i.e. it does not run `RebuildKeyspaceGraph`.

```
vtctldclient SetShardIsPrimaryServing <keyspace/shard> <true/false>
```

### Options

```
  -h, --help   help for SetShardIsPrimaryServing
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

