## Laptop/Dessktop Setup Ansible Playbook

I tend to reinstall somewhat frequently. This ansible playbook automates the boring parts.


Some recent changes in Linux Mint 19.2 (or ansible??) made me change the way I do this.

The laptop role has been updated. I removed the linrunner/tlp ppa because I was getting apt cache update failures. The packages are installed via regular ubuntu package repos, so I don't really need them. I was having a lot of trouble resuming from suspend, so I'm leaving one of the test tasks in there commented out as an example of what I troubleshot through. 