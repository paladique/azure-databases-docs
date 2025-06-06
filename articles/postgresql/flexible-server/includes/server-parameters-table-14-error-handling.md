---
author: nachoalonsoportillo
ms.author: ialonso
ms.reviewer: maghan
ms.date: 05/05/2025
ms.service: azure-database-postgresql
ms.subservice: flexible-server
ms.topic: include
ms.custom: automatically generated
---
### data_sync_retry

| Attribute | Value |
| --- | --- |
| Category | Error Handling |
| Description | Whether to continue running after a failure to sync data files. |
| Data type | boolean |
| Default value | `off` |
| Allowed values | `off` |
| Parameter type | read-only |
| Documentation | [data_sync_retry](https://www.postgresql.org/docs/14/runtime-config-error-handling.html#GUC-DATA-SYNC-RETRY) |


[!INCLUDE [server-parameters-azure-notes-void](./server-parameters-azure-notes-void.md)]



### exit_on_error

| Attribute | Value |
| --- | --- |
| Category | Error Handling |
| Description | Terminates session on any error. |
| Data type | boolean |
| Default value | `off` |
| Allowed values | `on,off` |
| Parameter type | dynamic |
| Documentation | [exit_on_error](https://www.postgresql.org/docs/14/runtime-config-error-handling.html#GUC-EXIT-ON-ERROR) |


[!INCLUDE [server-parameters-azure-notes-void](./server-parameters-azure-notes-void.md)]



### recovery_init_sync_method

| Attribute | Value |
| --- | --- |
| Category | Error Handling |
| Description | Sets the method for synchronizing the data directory before crash recovery. |
| Data type | enumeration |
| Default value | `fsync` |
| Allowed values | `fsync` |
| Parameter type | read-only |
| Documentation | [recovery_init_sync_method](https://www.postgresql.org/docs/14/runtime-config-error-handling.html#GUC-RECOVERY-INIT-SYNC-METHOD) |


[!INCLUDE [server-parameters-azure-notes-void](./server-parameters-azure-notes-void.md)]



### restart_after_crash

| Attribute | Value |
| --- | --- |
| Category | Error Handling |
| Description | Reinitialize server after backend crash. |
| Data type | boolean |
| Default value | `on` |
| Allowed values | `on` |
| Parameter type | read-only |
| Documentation | [restart_after_crash](https://www.postgresql.org/docs/14/runtime-config-error-handling.html#GUC-RESTART-AFTER-CRASH) |


[!INCLUDE [server-parameters-azure-notes-void](./server-parameters-azure-notes-void.md)]



