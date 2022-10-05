# JH Server 
The Jump Host (bastion server) is a server with the purpose of offering security to the internal network, agility in the connection to a large inventory of servers, complete management of connection logs, oriented to agile teams (squads), segmentation by permissions , share inventories with different teams, etc.

- Prerequisites:
  - RHEL installed and updated.
  - RHEL with a valid subscription.
  - Network conectivity in order to be able to install with *yum* or *dnf*
  - Network conectivity in order to be able to install python packages with *pip3* 
  - Got a VG called "datavg" with at least XX GB
  - 
  
- Preinstall Steps
  - Create a dir for the install "/tmp/jh"
  - Copy files to "/tmp/jh" 
```     JH-Server-Install.sh
        JH-install-prerequisites.sh
        JHServerFiles.tar.gz
        JH-environment.xml
``` 
- Preinstall Steps _(execute as root)_
``` 
        cd /tmp/jh
        ./JH-install-prerequisites.sh
        ./JH-Server-Install.sh
``` 
