btrfs and zfs tools have no build-in option for batch-deleting of snapshots and setting restrictions.

This script is intended for deleting multiple specific snapshots from a greater amount of snapshots. For example delete all daily snapshots and keep the weekly. Or delete snapshots from a specific day.

### usage

**delete-subvolumes -m** btrfs | zfs **-p** $PATH | $DATASET | **-r** $RESTRICTION **-d** (only show output, not actually delete it)
