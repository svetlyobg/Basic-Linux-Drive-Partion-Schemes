# Basic-Linux-Drive-Partition-Schemes

[Source:](https://www.youtube.com/watch?v=71msHISl9kQ)

## Partion Scheme for SSD


## Partion Scheme for HDD

| Capacity in MiB | Mount Point | Partition | Starting Point | Filesystem | Extended Partition |
| --- | --- | --- | --- | --- | --- |
| 512 | /boot | Primary | Beginning | Ext2 | N/A |
| 61440 | / | Primary | Beginning | Ext4 | N/A | Logical |
| 16384 | /swap | Primary | Beginning | N/A | Logical |
| What's left | /home | Primary | Beginning | Ext4 | N/A |

![HDD Scheme](hdd.png)