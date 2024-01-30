---
title: ExecuteFetchAsDBA
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient ExecuteFetchAsDBA

Executes the given query as the DBA user on the remote tablet.

```
vtctldclient ExecuteFetchAsDBA [--max-rows <max-rows>] [--json|-j] [--disable-binlogs] [--reload-schema] <tablet alias> <query>
```

### Options

```
      --disable-binlogs   Disables binary logging during the query.
  -h, --help              help for ExecuteFetchAsDBA
  -j, --json              Output the results in JSON instead of a human-readable table.
      --max-rows int      The maximum number of rows to fetch from the remote tablet. (default 10000)
      --reload-schema     Instructs the tablet to reload its schema after executing the query.
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

