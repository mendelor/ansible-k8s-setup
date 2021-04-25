This will setup a kubernetes cluster on Centos7 machines using ansible. You need these machines:

Ansible controller - controller.example.com - 10.0.0.99 - 1 vcpu / 2 gib ram
Kubernetes Master - master.example.com - 10.0.0.100 - 2 vcpu / 4 gib ram
Kubernetes Node1 - nodeone.example.com - 10.0.0.1 - 1 vcpu / 4 gib ram
Kubernetes Node2 - nodetwo.example.com - 10.0.0.2 - 1 vcpu / 4 gib ram
If you can allocate more compute resources, its better If you change your machine IP's then you have to change those whereever those were referred.
