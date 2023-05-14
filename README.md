# deck
# The start to a steam deck script to set settings the way I want them post-update

# Un-read-only the filesystem

sudo su -
steamos-readonly disable

# Sync OneDrive

/home/deck/onedrive_synch.sh (contains: Downloads/rclone-v1.61.1-linux-amd64/rclone --vfs-cache-mode writes mount onedrive: ~/OneDrive
)
