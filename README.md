 ![pks-prep](https://github.com/bdereims/pks-prep/blob/master/pks-prep.png)


> [How to Use "pks-prep"](https://github.com/bdereims/pks-prep/tree/master/documentation)

> [The excellent diagram from Stephen](https://github.com/stephendotcarter/diagrams)

( [PKS Documentation](https://docs.vmware.com/en/VMware-Pivotal-Container-Service/) )

- Tested for PKS 1.4 + NSX-T 2.3 and NSX-T 2.4 but not fully automated way
- New feature for deployiong multiple NSX Controllers and NSX Edges
- Add overlay_host with VLAN_ID and overlay_edgevm in the case of VLAN for TEP
- Add VCSA automaticaly within MSX Manager as compute manager

It's not an official PKS installer. It's my own work for installation automation.
Don't use it to deploy a pruction environment.

Check out the [LICENSE](https://github.com/bdereims/pks-prep/blob/master/LICENSE).
