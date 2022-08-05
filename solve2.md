### Share folder from VMWare

  - Install VM Desktop

        sudo apt -y install open-vm-tools-desktop
        
        sudo apt -y install open-vm-tools-desktop fuse
        or 
        sudo apt -y install open-vm-tools-desktop fuse3
        
        sudo reboot
  
  - Create Folder
        
        cd /mnt/
 
        if you didn't have folder, let's create:
        sudo mkdir hgfs

  - Allow Access

        sudo mount -t fuse.vmhgfs-fuse .host:/ /mnt/hgfs -o allow_other


