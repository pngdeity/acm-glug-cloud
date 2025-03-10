- [x] Inventory our devices.
  - See [inventory](https://docs.google.com/spreadsheets/d/1Mex7f6qN9uSypg3oOCucHvvdE0HO6KnUJdlAhtJ2QbY).
- [ ] Figure out how to add our devices to the University network.
  - [ ] Find MAC address for managed switch?
- [ ] See if [this](https://landscape.cncf.io) is a useful way to categorize tools.
- [ ] Install RockyLinux on the host, on one drive.
- [ ] Test harddrives (partially complete).
- [ ] Research filesystems
  - Ceph on native vs Ceph on ZFS?
  - Can we use ZFS for root partition? Should we?
  - This should be compatible with the performance limitations of our current NICs.
  - They should be optimal for the storage controllers built in to the servers.
- [ ] Research OpenStack, Proxmox, and vSphere.
  - <https://www.reddit.com/r/Proxmox/comments/lca6cv/proxmox_vs_openstack/>
  - Will they support cloud services like container-as-a-service and object storage?
  - How hard are they to maintain?
- [ ] Do all servers have the same or compatible iDRAC version?
- [ ] Advice on cable management and other physical things
  - What do we need to buy, if anything?
- [ ] Research networking
  - Do we need VLANs? How to set up?
  - How to set up NAT?
  - OPNsense vs pfSense vs pure iptables?
- [ ] Research HDD capacity and speed
  - What SSDs should we buy? How many? How big?
  - Does the storage driver support mixed SSD and HDDs?
  - Should there be a specialized storage vs compute node?
