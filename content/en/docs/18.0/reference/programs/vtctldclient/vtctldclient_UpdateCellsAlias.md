---
title: UpdateCellsAlias
series: vtctldclient
commit: f4d1487c72392cec566ed9ab39a00c7d027cc8ee
---
## vtctldclient UpdateCellsAlias

Updates the content of a CellsAlias with the provided parameters, creating the CellsAlias if it does not exist.

### Synopsis

Updates the content of a CellsAlias with the provided parameters, creating the CellsAlias if it does not exist.

```
vtctldclient UpdateCellsAlias [--cells <cell1,cell2,...> [--cells <cell4> ...]] <alias>
```

### Options

```
  -c, --cells strings   The list of cell names that are members of this alias.
  -h, --help            help for UpdateCellsAlias
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

