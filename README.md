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

## NTP

```bash
ansible-navigator run ntp.yml
```

## BGP Global

```bash
ansible-navigator run bgp_global.yml
```

### Models

- [resource_module_models](https://github.com/ansible-network/resource_module_models/tree/master/models)

#### Issues

- [nxos snmp](https://github.com/ansible-collections/cisco.nxos/issues/433)
- [nxos ntp](https://github.com/ansible-collections/cisco.nxos/issues/450)
- iosxr: `bgp.router_id` nxos: `router_id` ios: `bgp.router_id.address`