# Network Resource Modules Demo
[![Ansible Lint](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml)

## L3 Interfaces

```bash
ansible-navigator run l3_interface.yml
```

## Banner

```bash
ansible-navigator run banner.yml
```

## SNMP

```bash
ansible-navigator run snmp.yml
```

## BGP Global

```bash
ansible-navigator run bgp_global.yml
```

iosxr: `bgp.router_id` nxos: `router_id` ios: `bgp.router_id.address`

### Models

- [resource_module_models](https://github.com/ansible-network/resource_module_models/tree/master/models)

#### Issues

- [nxos snmp](https://github.com/ansible-collections/cisco.nxos/issues/433)
- [iosxr snmp](https://github.com/ansible-collections/cisco.iosxr/issues/215)
- [iosxr bgp](https://github.com/ansible-collections/cisco.iosxr/issues/216)