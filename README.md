# timecrisis

## Usage

Start up and ssh into VM:

    vagrant up
    vagrant ssh

Start ipython notebook:

    scl enable python27 "ipython notebook --NotebookApp.ip='192.168.50.4' --NotebookApp.open_browser=False --NotebookApp.notebook_dir=/vagrant"

## TODO

- scl Ansible module
- init.d script for ipython notebook
- Ansible service management for ipython notebook
- Verify steps for work host
