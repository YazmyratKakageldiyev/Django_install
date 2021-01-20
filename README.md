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
# install pip for python
```sh
$ sudo apt update
$ sudo apt install python3-pip
pip3 --version
```
# install virtualenv
```sh
$ sudo apt install python3-virtualenv
```
# create virtualenv
```sh
python3 -m virtualenv venv
```
# activate virtual environment
```sh
./venv/bin/activate
```
# install django web framework
```sh
pip install Django
```
# make django project
```sh
django-admin startproject projectname
cd projectname
```
# runserver django web framework
```sh
python manage.py runserver 0.0.0.0:8000
```
# eldeme
