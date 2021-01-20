# django_deploy
Django project deploy on Ubuntu 20.10
# install python
```sh
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt install python3.9
$ sudo apt update
$ sudo apt -y upgrade
$ python3 -V
```
# Install pip for Python
```sh
$ sudo apt update
$ sudo apt install python3-pip
pip3 --version
```
# install virtualenv
```sh
$ sudo apt install python3-virtualenv
```
#create virtualenv```sh

python3 -m virtualenv venv
./venv/bin/activate
# install Django web framework
pip install Django
