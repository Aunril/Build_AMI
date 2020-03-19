# Build_AMI

## Présentation

Le Build_AMI utilise Packer associé à Ansible pour déployer une image AMI complète.
Elle embarque apache2 ainsi qu'un site web.


## Prerequisites
  - Jenkins + Config pipeline
  - Persistent Iptables & Iptable to redirect 80 -> 8080
  - JQ
  - AWS CLI for next steps
