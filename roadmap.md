# Xen Orchestra roadmap

Please consider it as an indicative roadmap, things can change.

Item are expressed in a (roughly) decreasing priority order.

## Features

- [Advanced user management](https://xen-orchestra.com/users-roles-in-xen-orchestra/) + ✓ ~~LDAP Backend~~
- [Backup management](https://github.com/vatesfr/xo-web/issues/176) directly in XOA
- ✓ ~~Graphs (RRD) showing CPU, RAM, IO load etc.~~
- ✓ ~~Console working behind a NAT (console proxy in xo-server)~~
- ✓ ~~PCI (and GPU) management in GUI (passthrough)~~
- Update/upgrade XOA directly in GUI (in progress)
- [D3js](http://d3js.org) data viz
- Infrastructure analysis and diag (through whole RRDs recorded)
- Load management (auto migrate if necessary, adapt VM sizing when needed)

## Fixes

- Better server scalability
- Solve client stability problems
- [Resolve known bugs](./known-bugs.md)

## Backlog

This is the non-ordered stuff to put in the roadmap:

- ✓ ~~VM import and export~~
- Have CPU per core view
- [Managing hotfixes directly in XO](https://github.com/vatesfr/xo-web/issues/174) (with auto search for new updates)
- ✓ ~~Autostart VM on a host~~
- ✓ ~~Handle live migration between pools even if there is different CPU types~~
- Add PV args and more details in VM creation GUI
- ✓ ~~Better error messages~~
- ✓ ~~Task progress~~
- ✓ ~~Ability to create storage repositories~~
- Ability to modify XenStore values
