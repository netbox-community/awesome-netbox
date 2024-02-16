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
  - [Authentication](#authentication)
  - [General](#general)
  - [Integrations](#integrations)
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

### Authentication
- [jeremyschulman/netbox-plugin-auth-saml2](https://github.com/jeremyschulman/netbox-plugin-auth-saml2) - Netbox Plugin for SSO using SAML2.

### General
- [alsigna/netbox-software-manager](https://github.com/alsigna/netbox-software-manager) - Plugin to deal with Cisco IOS & XE software.
- [amyasnikov/validity](https://github.com/amyasnikov/validity) - Plugin for writing configuration compliance checks.
- [artyomovs/netbox-plugin-config-officer](https://github.com/artyomovs/netbox-plugin-config-officer) - A plugin for NetBox to work with running-configuration of Cisco devices.
- [peteeckel/netbox-plugin-dns](https://github.com/peteeckel/netbox-plugin-dns) - Plugin for managing DNS data.
- [DanSheps/netbox-config-backup](https://github.com/DanSheps/netbox-config-backup) - Plugin to backup configuration of devices.
- [DanSheps/netbox-lifecycle](https://github.com/DanSheps/netbox-lifecycle) - Plugin for managing Hardware EOS/EOL and Support Contracts.
- [DanSheps/netbox-routing](https://github.com/DanSheps/netbox-routing) - Plugin for managing routing (Static routing only currently).
- [drygdryg/netbox-plugin-interface-sync](https://github.com/drygdryg/netbox-plugin-interface-sync) - Compare and synchronize interfaces between devices and device types.
- [ffddorf/netbox-vault-secrets](https://github.com/ffddorf/netbox-vault-secrets) - Hashicorp Vault Plugin for Netbox.
- [FlxPeters/netbox-plugin-prometheus-sd](https://github.com/FlxPeters/netbox-plugin-prometheus-sd) - Provide Prometheus compatible API Endpoint with data from Netbox.
- [gardunha/netbox-routeros](https://github.com/gardunha/netbox-routeros) - Netbox plugin for auto-configuring Mikrotik RouterOS devices.
- [iDebugAll/nextbox-ui-plugin](https://github.com/iDebugAll/nextbox-ui-plugin) - A Topology visualization plugin.
- [iDebugAll/phonebox_plugin](https://github.com/iDebugAll/phonebox_plugin) - A Telephone Number Management Plugin for Netbox and more.
- [k01ek/netbox-bgp](https://github.com/k01ek/netbox-bgp) - Plugin for BGP related objects documentation.
- [k01ek/netbox-qrcode](https://github.com/k01ek/netbox-qrcode) - Plugin generating QR codes for objects: Rack, Device, Cable.
- [kkthxbye-code/netbox-old-search](https://github.com/kkthxbye-code/netbox-old-search) - Brings back the old global search method.
- [mattieserver/netbox-topology-views](https://github.com/mattieserver/netbox-topology-views) - Create topology views/maps from your devices in NetBox.
- [miaow2/netbox-config-diff](https://github.com/miaow2/netbox-config-diff) - Push rendered configs from NetBox to devices and show diff between the intended device config and actual.
- [minitriga/axians-netbox-plugin-pdu](https://github.com/minitriga/axians-netbox-plugin-pdu) - Plugin to get power distribution unit (PDU) Information.
- [networktocode/ntc-netbox-plugin-onboarding](https://github.com/networktocode/ntc-netbox-plugin-onboarding) - Plugin to easily onboard new devices.
- [Onemind-Services-LLC/netbox-metatype-importer](https://github.com/Onemind-Services-LLC/netbox-metatype-importer) - Easy import Device and Module types from GitHub repository.
- [Onemind-Services-LLC/netbox-secrets](https://github.com/Onemind-Services-LLC/netbox-secrets) - A Secret store for NetBox.
- [OpenSource-THG/netbox-vrf-context](https://github.com/OpenSource-THG/netbox-vrf-context) - Plugin for modeling VRF Contexts.
- [osism/netbox-plugin-osism](https://github.com/osism/netbox-plugin-osism) - Plugin for a better OSISM integration.
- [peteeckel/netbox-plugin-dns](https://github.com/peteeckel/netbox-plugin-dns) - Plugin for managing DNS data (maintained fork of netbox-dns).
- [PieterL75/netbox_ipcalculator](https://github.com/PieterL75/netbox_ipcalculator) - IP Calculator plugin for Netbox.
- [renatoalmeidaoliveira/nbservice](https://github.com/renatoalmeidaoliveira/nbservice) - Plugin for ITSM service mapping.
- [ryanmerolle/netbox-acls](https://github.com/ryanmerolle/netbox-acls) - Plugin for Access List management.
- [Solcon/netbox-gitlab](https://github.com/Solcon/netbox-gitlab) - NetBox GitLab export plugin.
- [tobiasge/netbox-initializers](https://github.com/tobiasge/netbox-initializers) - Plugin to load predefined data into Netbox.
- [vapor-ware/netbox-virtual-circuit-plugin](https://github.com/vapor-ware/netbox-virtual-circuit-plugin) - Plugin for NetBox that Supports Virtual Circuit management.

### Integrations
- [netdevopsbr/netbox-proxbox](https://github.com/netdevopsbr/netbox-proxbox) - Netbox Plugin for integration between Proxmox and Netbox.
- [SaaShup/netbox-docker-plugin](https://github.com/SaaShup/netbox-docker-plugin) - Netbox Plugin to manage docker with style.
- [oz123/coredns-netbox-plugin](https://github.com/oz123/coredns-netbox-plugin) - A CoreDNS plugin to get dns records from NetBox.
- [robertcsapo/ciscodnacnetbox](https://github.com/robertcsapo/ciscodnacnetbox) - Cisco DNA Center Integration with NetBox.
- [wvandeun/nornir_netbox](https://github.com/wvandeun/nornir_netbox) - NetBox plugin for Nornir.
- [netreplica/nrx](https://github.com/netreplica/nrx?source=awesome-netbox) - Netreplica `nrx` topology and configuration exporter for network emulation labs: Containerlab, Cisco Modeling Labs.

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
