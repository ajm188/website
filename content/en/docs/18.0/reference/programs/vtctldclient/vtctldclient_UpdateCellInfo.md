---
title: UpdateCellInfo
series: vtctldclient
commit: 5d52c05cb8862dc415c13945502b9f00deb9bb8e
---
## vtctldclient UpdateCellInfo

Updates the content of a CellInfo with the provided parameters, creating the CellInfo if it does not exist.

### Synopsis

Updates the content of a CellInfo with the provided parameters, creating the CellInfo if it does not exist.

If a value is empty, it is ignored.

```
vtctldclient UpdateCellInfo [--root <root>] [--server-address <addr>] <cell>
```

### Options

```
  -h, --help                    help for UpdateCellInfo
  -r, --root string             The root path the topology server will use for this cell.
  -a, --server-address string   The address the topology server will connect to for this cell.
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

