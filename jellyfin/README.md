# JellyFin

## Installation

### Ubuntu installation

Follow instructions in https://jellyfin.org/docs/general/installation/linux#repository-automatic


### Enable DLNA server

DLNA server must be enabled to allow UPnP devices on your network to browse and play content.

Go to "DLNA Settings" and click on "Enable DLNA server"


## TO-DO

- Create Ansible Role to automatically configure installation
- Activate HTTPS
  - Creation TLS certificate (Let's encrypt?)
  - Behind a NGINX proxy?
- Centralized Storage?
  - NFS?


## References

- [Jellyfin docs](https://jellyfin.org/docs/)

- [How to handle tutorials/trainings videos in Jellyfin](https://www.reddit.com/r/jellyfin/comments/m06boh/plugin_for_managing_tutorialscourses/)