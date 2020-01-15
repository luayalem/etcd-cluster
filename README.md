# etcd-cluster
Install TLS etcd cluster
## Bosh Lite Installation
1. Checkout the `etcd-cluster`
	```bash
	git clone https://github.com/luayalem/etcd-cluster.git
	```
2. copy etcd certs to `~/etcd-certs` on each of the nodes
3. updat hosts file with your hosts IP
3. install etcd cluster
	```bash
	cd etcd-cluster
  ansible-playbook -i hosts play.yaml
	```
