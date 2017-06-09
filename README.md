# DHCP Client module

[**Package DB** (owner)](https://admin.fedoraproject.org/pkgdb/package/modules/dhcp/) |
[**F26 modulemd** (source)](http://pkgs.fedoraproject.org/cgit/modules/dhcp.git/tree/dhcp.yaml?h=f26) |
[**PDC** (result)](https://pdc.fedoraproject.org/rest_api/v1/unreleasedvariants/?active=True&variant_name=dhcp)


DHCP (Dynamic Host Configuration Protocol) is a protocol which allows
individual devices on an IP network to get their own network
configuration information (IP address, subnetmask, broadcast address,
etc.) from a DHCP server. The overall purpose of DHCP is to make it
easier to administer a large network.

This module provides the ISC DHCP client.

## Current state

| State | Description |
|-------|-------------|
| ✓ YES | **Build passes** in the infra (all build deps are ok) |
| ✓ YES | **Installs** on the Base Runtime (all runtime deps are ok) |
| ✓ YES | **No bootstrap** - uses only proper modules |
| ✗ NO | General **tests are in dist-git** |
| ✗ NO | General **tests pass** |
| ✓ YES | Meets the **Fedora Module Packaging Guidelines** |
<!--
| ✓ YES | yes! |
| ✗ NO  | no! |
-->

### Notes

No notes are good notes.
