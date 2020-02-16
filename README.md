Ansible CIS Benchmark
=====================

Ansible roles that setup CIS Security Benchmark to a system running :

* **CentOS 7**
* **Debian 10**
* **Ubuntu 18.04**

The implementation has been converted from CIS Benchmark document to ansible roles.

CIS Benchmark security version :

| OS Version | CIS Benchmark Version |
| ---------- | :---: |
| CentOS 7 | v2.2.0 |
| Debian 10 | v1.0.0 |
| Ubuntu 18.04 | v1.0.0 |

This role was developed and tested against all related operating system.

## Why Would I Use This Role ?

If you are attempting to obtain compliance against an industry-accepted security standard, like PCI DSS, APRA or ISO 27001, then you need to demonstrate that you have applied documented hardening standards against all systems within scope of assessment.

If you are running those mentioned above Linux distribution, then this role attempts to provide one piece of the solution to the compliance puzzle.

## Special Consideration

**[ ===== DANGER !!! ===== ]**

Please do not run this ansible roles blindly on an active system.

This roles will make a serious modification to your system that could affect its availability.

The safest step is to run this roles on a new and fresh machine, and then you will have time to inspect what could be wrong after running this roles.

You don't want to debugging something you didn't know in production system right ? :D

## Example Playbook

WIP

## Role Variables

WIP

## Role Options

WIP

## Limitations

WIP

## Compatibility

WIP

## Testing

WIP

## License

WIP

## Author Information

This role was developed by [https://www.linkedin.com/in/fredy-samuel-b-tarigan-72a527111/] (Fredy Tarigan)