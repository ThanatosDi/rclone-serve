# rclone-serve
Setup rclone serve via Docker.    
Upload to RClone Supported Cloud Storage via Webdav using Synology Cloud Sync or Synology Hyper Backup on Synology DSM.  
You can refer to this implementation for detailed instructions.  
[Using Docker to connect Synology Hyper Backup to pCloud (and all 5x Rclone-supported remotes)](https://www.reddit.com/r/pcloud/comments/117oloh/using_docker_to_connect_synology_hyper_backup_to/)  

透過 Docker 建立 rclone serve  
在 Synology DSM 上可以使用 Synology Cloud Sync 或 Synology Hyper Backup 透過 Webdav 上傳至 RClone 所支援的雲端空間  
詳細的內容可以查看這邊實作  
[Using Docker to connect Synology Hyper Backup to pCloud (and all 5x Rclone-supported remotes)](https://www.reddit.com/r/pcloud/comments/117oloh/using_docker_to_connect_synology_hyper_backup_to/)  

# How to use this template (如何使用此範本)

If remote control is not needed, you can remove the following parameters.  

如果沒有需要進行遠端控制(Remote Control)  
可將下方參數移除  
https://github.com/ThanatosDi/rclone-serve/blob/561955e6cbe01d8969eafff1e3d1798a80080d67/docker-compose.yml#L16
https://github.com/ThanatosDi/rclone-serve/blob/561955e6cbe01d8969eafff1e3d1798a80080d67/docker-compose.yml#L27-L29

Set the port for the rclone serve service, defaults to 8080.  

設定 rclone serve 服務的 port，預設為 8080  
https://github.com/ThanatosDi/rclone-serve/blob/561955e6cbe01d8969eafff1e3d1798a80080d67/docker-compose.yml#L26
