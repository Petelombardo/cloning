# Network-based Cloning Scripts
A pair of semi-automatic cloning scripts that allow you to clone drives over the network.

Run the scripts from any Linux system or live CD and you can clone any filesystem.  These scripts work at the block-level, so all filesystems are supported.

Requirements:  You must install pv and lz4.   
On Debian/Ubuntu systems, you can do this by running:
apt install liblz4-tool pv

Instructions
On the source system, run clone-source.   On the destination system, run clone-target.   The source server will automatically find the target as long as it is on the same subnet.  Once you confirm that the destination IP is correct, the cloning begins.

This takes the manual work out of cloning.  These scripts are great for P2P and V2V.  You can P2V and V2P as long as you have the right drivers enabled before cloning.



