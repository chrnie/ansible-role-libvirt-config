# Ansible Role: libvirt-config

An Ansible role for managing a libvirtd on a root server with public IPs.
All VMs will be accessible through a NAT and get optional public IPs.
VMs will be generated through chrnie.libvirt-control-vm

Tested on a Hetzner root server


## Requirements

None.


## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):



## Dependencies

chrnie.libvirt-install


## Example Playbook

    - hosts: all
      roles:
        - chrnie.libvirt-config


## License

Apache License 2.0

## Author Information

Created in 2017 by Christoph Niemann, https://github.com/chrnie
