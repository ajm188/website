---
title: ValidateVersionShard
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient ValidateVersionShard

Validates that the version on the primary matches all of the replicas.

```
vtctldclient ValidateVersionShard <keyspace/shard>
```

### Options

```
  -h, --help   help for ValidateVersionShard
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

