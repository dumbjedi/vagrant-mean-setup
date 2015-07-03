### vagrant-mean-setup
A Basic project for setting up mean in a vagrant box

> This requires installation of vagrant and virtual box

#### Content

1. This is a setup using puppet for installation of various modules M(mongo)E(express)A(angular)N(node)
2. The operating system used on Precise64 (Ubuntu 12.04 64 bit)

#### Setup

1. clone the repo git@github.com:dumbjedi/vagrant-mean-setup.git
2. Launch machines with ```vagrant up``` in the cloned specific directory where the Vagrantfile is present
3. You can ssh to app server by doing ```ssh aapserver```
4. A basic app server can be started as ```node app.js``` from ```/usr/local/src/mean/mytestapp```
5. On the browser we can see express starting up

#### Details

