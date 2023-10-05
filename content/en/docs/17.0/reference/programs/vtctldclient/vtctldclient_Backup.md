---
title: Backup
series: vtctldclient
commit: 91cfed1c1b6f7872f95f88484fd602061430d7bd
---
## vtctldclient Backup

Uses the BackupStorage service on the given tablet to create and store a new backup. This is going to change the generated docs I bet.

```
vtctldclient Backup [--concurrency <concurrency>] [--allow-primary] <tablet_alias>
```

### Options

```
      --allow-primary      Allow the primary of a shard to be used for the backup. WARNING: If using the builtin backup engine, this will shutdown mysqld on the primary and stop writes for the duration of the backup.
      --concurrency uint   Specifies the number of compression/checksum jobs to run simultaneously. (default 4)
  -h, --help               help for Backup
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.

