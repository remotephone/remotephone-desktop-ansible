## Ansible Desktop Setup - Various Ubuntus 18.04 and Linux Mint 18.03/19

This will configure your desktop and install a few things. If you're on a laptop, enable the laptop role and it'll handle power management better. 

```
sudo apt install ansible git
git clone https://github.com/remotephone/remotephone-desktop-ansible.git
cd remotephone-desktop-ansible
sudo ansible-playbook -i HOSTS setup.yml 
```