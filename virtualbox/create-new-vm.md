# Create New Ubuntu VM

1. Download ubuntu: https://ubuntu.com/download/desktop
2. Download virtualbox: https://www.virtualbox.org/wiki/Downloads
3. Create the VirtualBox VM - gave it 10GB disk and 4GB RAM
4. Open it, select the ubuntu iso, install ubuntu (minimal)
5. Install guest additions: Devices -> insert guest additions
6. Enable bi-directional clipboard: Devices -> Shared Clipboard -> Bidirectional
7. Share folder from host:
..* Devices -> Shared Folders. Add the folder - automount and permanent.
..* Add user to group: sudo adduser $USER vboxsf


