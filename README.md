# opencast-ansible-demo

This is a simple ansible script to install Opencast in the local machine.

Also modifies the fast workflow to encode using an Nvidia GPU.

This script is for use in Ubuntu 18.04 maybe can work in Ubuntu 20.04

## How to run
Install Prerequisites
` ansible-playbook -v -i inv_local.yml play_prerequisites.yml -Kk `

Install Opencast
` ansible-playbook -v -i inv_local.yml play_community.yml -Kk `


## Important

Install first the nvidia driver galaxy role

`ansible-galaxy install nvidia.nvidia_driver`