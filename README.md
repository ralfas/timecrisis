# timecrisis

## Usage

Export this git repo.

    git clone https://github.com/ralfas/timecrisis.git

Start up and ssh into VM:

    cd timecrisis
    vagrant up
    vagrant ssh

Start ipython notebook:

    scl enable python27 "ipython notebook --NotebookApp.ip='192.168.50.4' --NotebookApp.open_browser=False --NotebookApp.notebook_dir=/vagrant/notebooks"

Open iPython Notebook in your browser it should be available at the following IP address:

    192.168.50.4

## TODO

- scl Ansible module
- init.d script for ipython notebook
- Ansible service management for ipython notebook
