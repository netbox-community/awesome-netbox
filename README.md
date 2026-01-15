<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome NetBox [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

A curated list of awesome resources related to NetBox!

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="images/netbox_logo.svg" width="300" alt="NetBox logo" />
</a>

<!-- description -->

[NetBox](https://github.com/netbox-community/netbox) is an infrastructure resource modeling (IRM) tool providing the ideal <strong>"source of truth"</strong> to power network automation.

</div>

<!-- TOC -->

## Contents

- [Featured (new releases)](#featured-new-releases)
- [Official Docs & Quickstarts](#official-docs--quickstarts)
- [Plugins](#plugins)
- [Ansible](#ansible)
- [Deployment](#deployment)
- [Utilities](#utilities)
- [Synchronization](#synchronization)
- [SDKs](#sdks)
- [Terraform](#terraform)
- [Resources](#resources)
  - [Educational](#educational)
  - [Blogs](#blogs)
  - [Community](#community)
  - [Videos](#videos)

<!-- CONTENT -->

## Featured (new releases)

<!--lint ignore double-link-->
- [Zero to Hero Course](https://zerotohero.netbox.dev/) - A short course designed to take new NetBox users from ‘Zero to Hero’.

## Official Docs & Quickstarts

<!--lint disable double-link-->
- 📖 [NetBox Documentation](https://docs.netbox.dev/en/stable/) - Official NetBox Documentation.
- 🔧 [NetBox Demo Instance](https://demo.netbox.dev/) - Demo instance of NetBox (restarted daily).
- 📖 [NetBox Plugin Tutorial](https://github.com/netbox-community/netbox-plugin-tutorial) - NetBox Plugin Development Tutorial.
<!--lint enable double-link-->

## Plugins

- [netboxlabs.com/netbox-plugins/](https://netboxlabs.com/netbox-plugins/) - NetBox Community Plugins

## Ansible

- [lae/ansible-role-netbox](https://github.com/lae/ansible-role-netbox) - Cross-platform Ansible role for deploying NetBox.
- [netbox-community/ansible_modules](https://github.com/netbox-community/ansible_modules) - NetBox modules for Ansible using Ansible Collections.
- [osism/ansible-collection-services](https://github.com/osism/ansible-collection-services) - Ansible collection with service roles.

## Deployment

- [bootc/netbox-chart](https://github.com/bootc/netbox-chart) - A Helm chart for NetBox.
- [netbox-community/netbox-docker](https://github.com/netbox-community/netbox-docker) - Docker Image of NetBox.

## Utilities

- [den-it/ntmap](https://github.com/den-it/ntmap) - Network topology map using Netbox as a data source.
- [kosimovsky/nbcli](https://github.com/kosimovsky/nbcli) - CLI tool for Netbox API.
- [lopes/netbox-scanner](https://github.com/lopes/netbox-scanner) - A scanner util for NetBox.
- [minitriga/Netbox-Device-Type-Library-Import](https://github.com/minitriga/Netbox-Device-Type-Library-Import) - The library is intended to be your friend and help you import all the device-types defined within the the NetBox Device Type Library Repository.
- [netbox-community/devicetype-library](https://github.com/netbox-community/devicetype-library) - A collection of community-sourced DeviceType definitions.
- [Solvik/netbox-agent](https://github.com/Solvik/netbox-agent) - Project aims to create hardware automatically into Netbox based on standard tools (dmidecode, lldpd, parsing /sys/, etc).
- [netreplica/graphite](https://github.com/netreplica/graphite?source=awesome-netbox) - Standalone topology visualizer Netreplica `graphite`.
- [NCCloud/netbox-resources-operator](https://github.com/NCCloud/netbox-resources-operator) - A Kubernetes operator to manage NetBox resources.

## Synchronization

- [bb-Ricardo/netbox-sync](https://github.com/bb-Ricardo/netbox-sync) - Sync objects from VMware or redfish sources to NetBox.
- [scaleway/netbox2netshot](https://github.com/scaleway/netbox2netshot) - Inventory synchronization tool between Netbox and Netshot.
- [TheNetworkGuy/netbox-zabbix-sync](https://github.com/TheNetworkGuy/netbox-zabbix-sync) - Python script to syncronise Netbox devices to Zabbix.

## SDKs

- [benclaussen/NetboxPS](https://github.com/benclaussen/NetboxPS) - Powershell module for Netbox.
- [hexa2k9/netbox-php](https://github.com/hexa2k9/netbox-php) - PHP API client library.
- [KashinYaS/NetBoxPowerShell](https://github.com/KashinYaS/NetBoxPowerShell) - PowerShell wrapper to NetBox API.
- [netbox-community/go-netbox](https://github.com/netbox-community/go-netbox) - Go API client library.
- [netbox-community/pynetbox](https://github.com/netbox-community/pynetbox) - Python API client library.
- [ninech/netbox-client-ruby](https://github.com/ninech/netbox-client-ruby) - Ruby API client library (NetBox v2).
- [timeforplanb123/anac](https://github.com/timeforplanb123/anac) - Python Async NetBox API Client, based on httpx and pydantic.

## Terraform

- [e-breuninger/terraform-provider-netbox](https://github.com/e-breuninger/terraform-provider-netbox) - Terraform provider to interact with Netbox.
- [smutel/terraform-provider-netbox](https://github.com/smutel/terraform-provider-netbox) - Terraform provider for Netbox.

## Resources

### Educational

<!--lint disable double-link-->
- [NetBox Plugin Tutorial](https://github.com/netbox-community/netbox-plugin-tutorial) - NetBox Plugin Development Tutorial.
- [Zero to Hero Course](https://zerotohero.netbox.dev/) - A short course designed to take new NetBox users from ‘Zero to Hero’.
<!--lint enable double-link-->

### Blogs

- [Integrating Okta SSO with NetBox](https://www.oasys.net/posts/okta-sso-with-netbox/) - Instructions for configuring NetBox and Okta for native SSO authentication.
- [Netbox Active Directory/LDAP Integration](https://www.thierolf.org/blog/2021/netbox-active-directoryldap-integration/) - How to setup Netbox with Active Directory as backend for users and groups.
- [NetBox NAPALM automation with bastion host](https://www.oasys.net/posts/netbox-napalm-automation-with-bastion-host/) - Configuring the NAPALM integration to use a SSH proxy.
- [NetBox: How to run it on your Synology](https://kevenaar.name/netbox-how-to-run-it-on-your-synology/) - Installing Netbox on your Synology NAS.

### Community

- [GitHub Discussions](https://github.com/netbox-community/netbox/discussions) - Discussion forum hosted by GitHub; ideal for Q&A and other structured discussions.
- [Slack](https://netdev.chat/) - Real-time chat hosted by the NetDev Community; best for unstructured discussion or just hanging out.

### Videos

- [Itential](https://www.youtube.com/watch?v=1DTlDF05LH4) - Integrating NetBox as a Source of Truth for Network Automation.
- [Viatto NetBox](https://www.youtube.com/c/KeepingITSimple/search?query=netbox) - Full NetBox course videos.
- [NS1 Labs](https://www.youtube.com/c/NS1Labs/search?query=netbox) - Community calls, Zero-to-Hero, NetBox feature video from the creator of NetBox.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!
