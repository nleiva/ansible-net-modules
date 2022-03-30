# Network Resource Modules Demo
[![Ansible Lint](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml)

## ACL

```bash
ansible-navigator run acl.yml
```

## Banner

```bash
ansible-navigator run banner.yml
```

## BGP Global

```bash
ansible-navigator run bgp_global.yml
```

## L3 Interfaces

```bash
ansible-navigator run l3_interface.yml
```

## NTP

```bash
ansible-navigator run ntp.yml
```

## SNMP

```bash
ansible-navigator run snmp.yml
```

### Models

- [resource_module_models](https://github.com/ansible-network/resource_module_models/tree/master/models)

### Collections

- [Arista EOS](https://github.com/ansible-collections/arista.eos)
- [Cisco IOS](https://github.com/ansible-collections/cisco.ios)
- [Cisco IOS XR](https://github.com/ansible-collections/cisco.iosxr)
- [Cisco NX-OS](https://github.com/ansible-collections/cisco.nxos)

#### Issues

- [nxos snmp](https://github.com/ansible-collections/cisco.nxos/issues/433)
- [nxos ntp](https://github.com/ansible-collections/cisco.nxos/issues/450)
- iosxr: `bgp.router_id` nxos: `router_id` ios: `bgp.router_id.address`