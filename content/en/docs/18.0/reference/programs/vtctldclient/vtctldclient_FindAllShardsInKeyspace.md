---
title: FindAllShardsInKeyspace
series: vtctldclient
commit: f4d1487c72392cec566ed9ab39a00c7d027cc8ee
---
## vtctldclient FindAllShardsInKeyspace

Returns a map of shard names to shard references for a given keyspace.

```
vtctldclient FindAllShardsInKeyspace <keyspace>
```

### Options

```
  -h, --help   help for FindAllShardsInKeyspace
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

