# EC3 examples

* kubernetes.radl: Template to install a Kubernetes cluster.
* openports.radl: Helper template to open ports in firewalls.
* im.radl: Template To install the Infrastructure Manager.
* ubuntu-ost.radl: Template to specify the image base to use in an OpenStack site.
* ubuntu-egi.radl: Template to specify the image base to use in an EGI Cloud Compute site that supports AppDB images.


```sh
$ ec3 launch mycluster kubernetes [ubuntu-ost|ubuntu-egi] -a auth.txt
```