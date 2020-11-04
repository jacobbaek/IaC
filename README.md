# Infrastructure for HANU CICD 

# Components
* hanu-deploy: automate to ready hanu deploy server
  * 1-ansible-playbook
  * 2-docker-services
  * 3-openstack : with openstack cli
* infra-k8s
  * 1-terraform-libvirt
  * 2-ansible-playbook
  * 3-kubespray
  * 4-ceph-csi
  * 5-helm-charts
* infra-dmz
  * 1-terraform-libvirt
  * 2-wireguard
  * 3-pfsense(unfortunatly, using iptables instead of pfsense)
