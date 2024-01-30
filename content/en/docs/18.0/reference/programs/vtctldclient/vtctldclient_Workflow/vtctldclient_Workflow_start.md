---
title: Workflow start
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient Workflow start

Start a VReplication workflow.

```
vtctldclient Workflow start
```

### Examples

```
vtctldclient --server localhost:15999 workflow --keyspace customer start --workflow commerce2customer
```

### Options

```
  -h, --help              help for start
  -w, --workflow string   The workflow you want to start.
```

### Options inherited from parent commands

```
      --action_timeout duration              timeout to use for the command (default 1h0m0s)
      --andrew-is-testing                    nothing to see here
      --compact                              use compact format for otherwise verbose outputs
  -k, --keyspace string                      Keyspace context for the workflow.
      --server string                        server to use for the connection (required)
      --topo-global-root string              the path of the global topology data in the global topology server
      --topo-global-server-address strings   the address of the global topology server(s)
      --topo-implementation string           the topology implementation to use
```

### SEE ALSO

* [vtctldclient Workflow](../)	 - Administer VReplication workflows (Reshard, MoveTables, etc) in the given keyspace.

