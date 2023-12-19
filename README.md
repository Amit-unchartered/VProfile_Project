# VProfile
## Description - Multi Tier Web Application Stack Setup Locally(VM)

![Overview](https://miro.medium.com/v2/resize:fit:875/0*BdJL_FTFzciqZRLf.png "Multi Tier Web Application Stack Diagram")

### Prerequisite
1. Oracle VM Virtualbox
2. Vagrant
3. Vagrant plugins
Execute below command in your computer to install hostmanager plugin
```
$ vagrant plugin install vagrant-hostmanager
```
5. Git bash or equivalent editor

## Manual Provisioning

### VM SETUP
1. Clone source code.
2. Cd into the repository.
3. Switch to the main branch.
4. cd into Manual_provisioning
Bring up vm’s
```
$ vagrant up
```
**NOTE**: Bringing up all the vm’s may take a long time based on various factors.
If vm setup stops in the middle run **_“vagrant up”_** command again.
**INFO**: All the vm’s hostname and /etc/hosts file entries will be automatically updated
