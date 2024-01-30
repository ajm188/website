---
title: Materialize start
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient Materialize start

Start a Materialize workflow.

```
vtctldclient Materialize start
```

### Examples

```
vtctldclient --server localhost:15999 Materialize --workflow product_sales --target-keyspace customer start
```

### Options

```
  -h, --help   help for start
```

### Options inherited from parent commands

```
      --action_timeout duration              timeout to use for the command (default 1h0m0s)
      --andrew-is-testing                    nothing to see here
      --compact                              use compact format for otherwise verbose outputs
      --format string                        The format of the output; supported formats are: text,json. (default "text")
      --server string                        server to use for the connection (required)
      --target-keyspace string               Target keyspace for this workflow.
      --topo-global-root string              the path of the global topology data in the global topology server
      --topo-global-server-address strings   the address of the global topology server(s)
      --topo-implementation string           the topology implementation to use
  -w, --workflow string                      The workflow you want to perform the command on.
```

### SEE ALSO

* [vtctldclient Materialize](../)	 - Perform commands related to materializing query results from the source keyspace into tables in the target keyspace.

