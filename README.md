# K8S-ansible
Configuring and provisioning a kubernetes cluster using Ansible in less than 10 minutes (depending on your network speed 😊)
kubernetes cluster composed of one master and 2 worker nodes
reproduced steps:
- Provisionning centos7 VMs using Vagrant
- Configuring ansible host inventory file within my vagrant VMs
- Playing my ansible playbook 📕 :
- Install and configure docker on the 3 nodes
- checking and applying kuberenetes requirements
- Install Kuberenets (Kubadm , Kubectl, kubeproxy)
- Initiating Master node and installing weavenet add-on network
- Joining worker Node
- testing the cluster by deploying an nginx app and accessing the app through the kubernetes cluster node.
