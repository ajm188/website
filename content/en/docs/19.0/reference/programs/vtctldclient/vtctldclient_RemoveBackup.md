---
title: RemoveBackup
series: vtctldclient
commit: f002d4b9a6b675a0a0c433270c64436f3abde529
---
## vtctldclient RemoveBackup

Removes the given backup from the BackupStorage used by vtctld. Plus another test change.

```
vtctldclient RemoveBackup <keyspace/shard> <backup name>
```

### Options

```
  -h, --help   help for RemoveBackup
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

