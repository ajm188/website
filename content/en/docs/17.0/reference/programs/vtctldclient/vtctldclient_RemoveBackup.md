---
title: RemoveBackup
series: vtctldclient
commit: 9a3d0f4a69a840cfa2cb86654abd4afa0be6e0aa
---
## vtctldclient RemoveBackup

Removes the given backup from the BackupStorage used by vtctld.

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

