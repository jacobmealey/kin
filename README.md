# kin
We are all of the same roots.


Kin is a project that harnesses the power of Docker to give developers access to other distros without having to dual boot or run a virtual machine! 

**Getting Started**

create a new container:

`./kin create ubuntu newcontainer`

run said container:

`./kin run newcontainer`


Kin [ mode ]:
- create [ distro base ] [ container name ]
- run [ container name ]
  


The default password for the root user and the user is `kin`.

(Its only been tested on ubuntu systems)

**Whats Been Done**
- Creates an a ubuntu docker image
- Makes a user with sudo priviliges 
- A permenent filesystem 
- Ability to access the filesystem of the container from the host machine
- Ability to give the container a host name
- Running multiple instances of the same container

**What Needs to Be Done**
- Ability to acess host machine filesystem from within the container
- On the fly portforwarding from container ports to host ports
- Create more distros 
  - Alpine
  - Fedora
  - Arch (??)

**What Needs to Be Done Way Down the Road**
- GUI
