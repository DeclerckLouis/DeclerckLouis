# Louis Declerck

I build and run the infrastructure that production depends on: virtualization on Proxmox VE, monitoring with Zabbix, and the network and servers under SCADA and MES. I run [Packetflow](https://www.packetflow.be) and do most of this work as code.

## What I work on

- **VMware to Proxmox VE migrations.** 350+ VMs moved in my career so far, on existing hardware and outside working hours, with the old environment kept as the way back.
- **OT infrastructure.** Clusters, IEC 62443 zones, vendor access, backup with a tested restore. PLC programming stays with the integrator.
- **Monitoring.** Zabbix with a proxy per site, trigger dependencies so one failure gives one alert, everything in Ansible.

## Open source

| Project | What it does |
| --- | --- |
| [netbox-ot](https://github.com/Packetflow-be/netbox-ot) | NetBox plugin for OT: asset register, IEC 62443 zones and conduits, flows, risk and an access map. On PyPI, with a [public demo](https://netbox-ot.packetflow.be). |
| [netbox-access-paths](https://github.com/Packetflow-be/netbox-access-paths) | NetBox plugin that records who can reach which system, with review sign-off. |
| [ot-devicetypes](https://github.com/Packetflow-be/ot-devicetypes) | NetBox device and module types generated from PROFINET GSDML files. |
| [netbox_EDA_terraform](https://github.com/DeclerckLouis/netbox_EDA_terraform) | My 2024 graduation project: NetBox as source of truth, Event-Driven Ansible and Terraform building VMs on Proxmox. |

## Tools

- **Virtualization:** Proxmox VE, Proxmox Backup Server, VMware vSphere, Hyper-V
- **Automation:** Ansible, NetBox, Terraform, Packer, GitHub Actions, Python, Bash
- **Monitoring:** Zabbix, SNMP, Grafana
- **Network:** FortiGate, MikroTik, VLANs, IPv6, HAProxy, PowerDNS
- **Systems:** Debian and Ubuntu, Windows Server, Active Directory, Veeam

## Background

Electromechanics, then a graduate degree in Systems & Network Engineering at Howest (2024). Certified for Proxmox VE: Deployment and Management, and Clustering and Shared Storage (2026).

## Contact

- [packetflow.be](https://www.packetflow.be)
- [linkedin.com/in/declercklouis](https://www.linkedin.com/in/declercklouis)
- [louis@packetflow.be](mailto:louis@packetflow.be)
