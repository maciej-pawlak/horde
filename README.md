# Why? 

The updated delta_crdt in Horde v0.8.4 broke the distributed registry functionality.
The issue was described [here](https://github.com/derekkraan/horde/issues/258)
As a temporary quick fix, Horde was reverted to version v0.8.3, the last known working version.
Additionally, the :auto membership fix from v0.8.6 has been included.

# TODO

Find and fix the bug in delta_crdt 
