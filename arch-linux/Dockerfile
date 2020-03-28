FROM archlinux 
LABEL "maintainer"="jacobmealey.maine@gmail.com"

ARG USER

run useradd -m -s /bin/bash $USER
run echo "root:kin" | chpasswd 
run echo $USER":kin" | chpasswd 


#Switch to user account
USER $USER
WORKDIR /home/$USER




