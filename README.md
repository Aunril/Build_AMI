# Build_AMI

## Présentation

Le Build_AMI utilise Packer en utilant Ansible en tant que "provisioner" pour déployer une image sur AWS (AMI).
Cette image embarque un serveur web apache2 hébergeant un site web statique.


## Prerequisites
  - Jenkins + Config pipeline
  - Persistent Iptables & Iptable to redirect 80 -> 8080
  - JQ
  - AWS CLI for next steps
