---
title: PlannedReparentShard
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient PlannedReparentShard

Reparents the shard to a new primary, or away from an old primary. Both the old and new primaries must be up and running.

```
vtctldclient PlannedReparentShard <keyspace/shard>
```

### Options

```
      --avoid-primary string             Alias of a tablet that should not be the primary; i.e. "reparent to any other tablet if this one is the primary".
  -h, --help                             help for PlannedReparentShard
      --new-primary string               Alias of a tablet that should be the new primary.
      --wait-replicas-timeout duration   Time to wait for replicas to catch up on replication both before and after reparenting. (default 15s)
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

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

