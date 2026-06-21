Cara gunakan:
copy bagian cloud-init di idcloudhost:

#cloud-config
runcmd:
  - curl -fsSL https://raw.githubusercontent.com/hamidw/osimpu-cloudinit/main/install.sh | bash
