# Network Resource Modules Demo
[![Ansible Lint](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml)

## ACL

```bash
ansible-navigator run acls.yml
```

## Banner

```bash
ansible-navigator run banner.yml
```

## BGP Global

```bash
ansible-navigator run bgp_global.yml
```

## Hostname

```bash
ansible-navigator run hostname.yml
```

## L3 Interfaces

```bash
ansible-navigator run l3_interface.yml
```

## Logging

```bash
ansible-navigator run logging.yml
```

## NTP

```bash
ansible-navigator run ntp.yml
```

## OSPFv2

```bash
ansible-navigator run ospfv2.yml
```

## Prefix List

```bash
ansible-navigator run prefix_lists.yml
```

## SNMP

```bash
ansible-navigator run snmp.yml
```

## User

```bash
ansible-navigator run user.yml
```

### More information

- [Network Resource Modules](https://github.com/nleiva/ansible-links#network-resource-modules)

#### Collections

- [Arista EOS](https://github.com/ansible-collections/arista.eos)
- [Cisco IOS](https://github.com/ansible-collections/cisco.ios)
- [Cisco IOS XR](https://github.com/ansible-collections/cisco.iosxr)
- [Cisco NX-OS](https://github.com/ansible-collections/cisco.nxos)

#### Issues

- [nxos snmp](https://github.com/ansible-collections/cisco.nxos/issues/454)
- [nxos ntp](https://github.com/ansible-collections/cisco.nxos/issues/450)
- [iosxr ospfv2](https://github.com/ansible-collections/cisco.iosxr/issues/227)
- [iosxr prefix_lists](https://github.com/ansible-collections/cisco.iosxr/issues/229)
- [ios logging](https://github.com/ansible-collections/cisco.ios/issues/545)
- iosxr: `bgp.router_id` nxos: `router_id` ios: `bgp.router_id.address`