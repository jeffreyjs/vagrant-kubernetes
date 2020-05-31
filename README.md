# vagrant-kubernetes

Vagrant machines running [Kubernetes](https://kubernetes.io/).

This repo follows the setup at the kubernetes blog here: [Kubernetes Setup Using Ansible and Vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/) and provisions three VMs (One Master / Two Nodes)

## Setup

* vagrant[https://www.vagrantup.com/downloads.html] 2.2.9
* virtualbox[https://www.virtualbox.org/wiki/Downloads] 6.1.6
* ansible[https://www.ansible.com/] 2.9.9
* python[https://www.python.org/downloads/] 3.8.2
* ubuntu 20.04

## Start

```sh
git clone git@github.com:jeffreyjs/vagrant-kubernetes.git
vagrant up
```

## Stop Environment

```sh
vagrant halt
```

## Destroy

```sh
vagrant destroy -f
```
