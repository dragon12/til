Download ubuntu: https://ubuntu.com/download/desktop
Download virtualbox: https://www.virtualbox.org/wiki/Downloads

Create the VirtualBox VM - gave it 10GB disk and 4GB RAM

Open it, select the ubuntu iso, install ubuntu (minimal)

Install guest additions: Devices -> insert guest additions
Enable bi-directional clipboard: Devices -> Shared Clipboard -> Bidirectional
Share folder from host:
* Devices -> Shared Folders. Add the folder - automount and permanent.
* Add user to group: sudo adduser $USER vboxsf

