# anaconda_vagrant

## Setup
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Install [Vagrant (1.9.1)](https://releases.hashicorp.com/vagrant/1.9.1/)
3. Install [Ansible (1.9.4)](http://docs.ansible.com/ansible/intro_installation.html#getting-ansible)
4. Clone this repo
5. Open your terminal and type `vagrant up` (from the repo directory). If this is the first time, it will take a bit for ansible to setup your vagrant machine.
6. Type `vagrant ssh` to log into your VM. Run `sh /etc/Anaconda3-5.3.0-Linux-x86_64.sh` and follow instructions to install anaconda.
7. Navigate to `/vagrant`, and to start jupyter run `jupyter notebook --ip=0.0.0.0`
8. Access jupyter from 192.168.33.10:8888