# misp-install-centos-7
script(s) info for automating installing MISP to CentOS 7

### Usage
Either run as root or edit the file and add `sudo` everywhere

During the install process copy the database admin password echoed out and then use it during the mysql installation stage to set root password

##### Source `misp.variables.sh`
    . misp.variables.sh

##### Run `misp.install.sh`
    bash misp.install.sh
