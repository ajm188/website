---
title: Migrate
series: vtctldclient
commit: f4b8361bc1e8c73cc17ec4663ee932677761f894
---
## vtctldclient Migrate

Migrate is used to import data from an external cluster into the current cluster.

### Options

```
      --format string            The format of the output; supported formats are: text,json. (default "text")
  -h, --help                     help for Migrate
      --target-keyspace string   Target keyspace for this workflow.
  -w, --workflow string          The workflow you want to perform the command on.
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.
* [vtctldclient Migrate cancel](./vtctldclient_migrate_cancel/)	 - Cancel a Migrate VReplication workflow.
* [vtctldclient Migrate complete](./vtctldclient_migrate_complete/)	 - Complete a Migrate VReplication workflow.
* [vtctldclient Migrate create](./vtctldclient_migrate_create/)	 - Create and optionally run a Migrate VReplication workflow.
* [vtctldclient Migrate show](./vtctldclient_migrate_show/)	 - Show the details for a Migrate VReplication workflow.
* [vtctldclient Migrate status](./vtctldclient_migrate_status/)	 - Show the current status for a Migrate VReplication workflow.

