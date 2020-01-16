# etcd-cluster
Install TLS etcd cluster 
## Installation
1. Clone the `etcd-cluster`repo
	```bash
	git clone https://github.com/luayalem/etcd-cluster.git
	```
2. Copy etcd certs to each node and place them under `/etc/etcd/certs`
3. Update `vars` with your certs name.
4. Update hosts file with your hosts IP
3. Install etcd cluster
	```bash
	cd etcd-cluster
    ansible-playbook -i hosts play.yaml
    ```
