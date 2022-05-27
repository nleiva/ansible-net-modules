# Network Resource Modules Demo
[![Ansible Lint](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/nleiva/ansible-net-modules/actions/workflows/ansible-lint.yml)

## Dependencies

You need to install Ansible Navigator to run these examples. You can install it with `pip install ansible-navigator`. This way you can run the playbooks in an Execution Environment, which Ansible Navigator will pull for you. 

I use [podman](https://podman.io/) as my container engine (`container-engine`) to fire off the Execution Environment. You can change to another alternative (docker) in the [ansible navigator config file](ansible-navigator.yml).

The examples run against [DevNet always-on devices](https://developer.cisco.com/site/sandbox/). 

## Examples

You can run any example by specifying the resource module in the variable `rm`.

```bash
ansible-navigator run main.yml -e rm=acls
```

Alternatively, you can run them directly as follows.

### ACL

```bash
ansible-navigator run acls.yml
```

### Banner

```bash
ansible-navigator run banner.yml
```

### BGP Global

```bash
ansible-navigator run bgp_global.yml
```

## Hostname

```bash
ansible-navigator run hostname.yml
```

### L3 Interfaces

```bash
ansible-navigator run l3_interface.yml
```

### Logging

```bash
ansible-navigator run logging.yml
```

### NTP

```bash
ansible-navigator run ntp.yml
```

## OSPFv2

```bash
ansible-navigator run ospfv2.yml
```

### Prefix List

```bash
ansible-navigator run prefix_lists.yml
```

### SNMP

```bash
ansible-navigator run snmp.yml
```

### User

```bash
ansible-navigator run user.yml
```

## More information

- [Network Resource Modules](https://github.com/nleiva/ansible-links#network-resource-modules)

### Collections

- [Arista EOS](https://github.com/ansible-collections/arista.eos)
- [Cisco IOS](https://github.com/ansible-collections/cisco.ios)
- [Cisco IOS XR](https://github.com/ansible-collections/cisco.iosxr)
- [Cisco NX-OS](https://github.com/ansible-collections/cisco.nxos)

### Issues

- iosxr: `bgp.router_id` nxos: `router_id` ios: `bgp.router_id.address`