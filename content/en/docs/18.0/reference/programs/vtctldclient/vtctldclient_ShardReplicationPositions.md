---
title: ShardReplicationPositions
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient ShardReplicationPositions



### Synopsis

Shows the replication status of each tablet in the shard graph.
Output is sorted by tablet type, then replication position.
Use ctrl-C to interrupt the command and see partial results if needed.

```
vtctldclient ShardReplicationPositions <keyspace/shard>
```

### Options

```
  -h, --help   help for ShardReplicationPositions
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

