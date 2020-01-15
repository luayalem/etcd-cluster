# etcd-cluster
Install TLS etcd cluster
## Bosh Lite Installation
1. Checkout the `etcd-cluster`
	```bash
	git clone https://github.com/luayalem/etcd-cluster.git
	```
2. copy etcd certs to each node and place them under `~/etcd-certs`
3. update hosts file with your hosts IP
3. install etcd cluster
	```bash
	cd etcd-cluster
        ansible-playbook -i hosts play.yaml
	```
