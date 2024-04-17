# LTRDCN-2765 - VXLAN EVPN Fabric and NetDevOpsautomation using Ansible  

- jinja2_fabric.yml: Deploy vxlan EVPN fabric using jinja2 templates. Standard leaf and spine architecture with OSPF as underlay protocol and iBGP for EVPN control plane.
- nxos_fabric.yml: Deply vxlan EVPN fabric using Ansible nxos modules.
- verify_fabric.yml: verify underlay and overlay operation
- code_upgrade.yml: Compare running version with standard code and upgrade if doesnt match.
- get_config.yml: Backup running config and compare with the previous standard config.
- vni_provision.yml: Day2 tasks to add new vni
