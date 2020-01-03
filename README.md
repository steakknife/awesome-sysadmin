<!--
  Title: Awesome Sysadmin
  Description: A curated list of amazingly awesome open source sysadmin resources.
  Author: n1trux
  -->

# Awesome Sysadmin [![certified awesome!](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**A curated list of amazingly awesome open source sysadmin resources.** Please read [CONTRIBUTING](./.github/CONTRIBUTING.md) if you wish to add software and consider [donating](https://github.com/steakknife/awesome-donations) to the FLOSS projects you use regularly.

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Automation](#automation)
  * [Backups](#backups)
  * [Build and software organization tools](#build-and-software-organization-tools)
  * [ChatOps](#chatops)
  * [Client Management](#client-management)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Orchestration](#cloud-orchestration)
  * Cloud Storage: [see awesome-selfhosted#file-transfersynchronization](https://github.com/Kickball/awesome-selfhosted#file-transfersynchronization)
  * [Code Review](#code-review)
  * Collaborative Software: [see awesome-selfhosted#groupware](https://github.com/Kickball/awesome-selfhosted#groupware)
  * [Configuration Management Database](#configuration-management-database)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Control Panels](#control-panels)
  * [Deployment Automation](#deployment-automation)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS](#dns)
  * [Domains](#domains)
  * [Editors](#editors)
  * [Identity Management](#identity-management)
  * [IT Asset Management](#it-asset-management)
  * [Log Management](#log-management)
  * [Mail Clients](#mail-clients)
  * Mail servers/webmail: [see awesome-selfhosted#email](https://github.com/kickball/awesome-selfhosted#email)
  * [Monitoring](#monitoring)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Network Configuration Management](#network-configuration-management)
  * [Newsletter](#newsletters)
  * [NoSQL](#nosql)
  * [Packaging](#packaging)
  * [Project Management](#project-management)
  * [Queuing](#queuing)
  * [RDBMS](#rdbms)
  * [Remote Management](#remote-management)
  * Security: [see awesome-security](https://github.com/sbilly/awesome-security)
  * [Service Discovery](#service-discovery)
  * [Software Containers](#software-containers)
  * SSH: [see awesome-ssh](https://github.com/moul/awesome-ssh)
  * Statistics: [see awesome-selfhosted#analytics](https://github.com/Kickball/awesome-selfhosted#analytics)
  * [Status Pages](#status-pages)
  * Ticketing systems: [see awesome-selfhosted#ticketing](https://github.com/Kickball/awesome-selfhosted#ticketing)
  * [Troubleshooting](#troubleshooting)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * XMPP: [see awesome-selfhosted#xmpp](https://github.com/Kickball/awesome-selfhosted#xmpp)
  * [Web](#web)
  * Wiki Software: [see awesome-selfhosted#wikis](https://github.com/Kickball/awesome-selfhosted#wikis), Sysadmin Wikis: [see #wikis](#wikis)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Communities/Forums](#communities--forums)
  * [Newsletters](#newsletters)
  * [Repositories](#repositories)
  * [Websites](#websites)
  * [Wikis](#wikis)

## Automation

*Automation build.*

* [Apache Ant](https://ant.apache.org/) - Automation build tool, similar to make, written in Java.
* [Apache Maven](https://maven.apache.org/) - Build automation tool mainly for Java.
* [Bazel](https://www.bazel.io/) - Google's build system.
* [Bolt](https://puppet.com/products/bolt) - You can use Bolt to run one-off tasks, scripts to automate the provisioning and management of some nodes, you can use Bolt to move a step beyond scripts, and make them shareable.
* Cabal.
* Cargo.
* CMake.
* Conan.
* [GNU Make](https://www.gnu.org/software/make/) - The most popular automation build tool for many purposes.
* [Gradle](https://gradle.org/) - Another build automation system.
* Knife.
* Lein.
* Mix.
* Ninja.
* Pip.
* [Rake](https://github.com/ruby/rake) - Build automation tool similar to Make, written in and extensible in Ruby.
* SBT.
* Scons.

## Backups

*Backup software.*

- There is no good backup software. Build your own with tar, gpg, rsync &| zfs send/receive.

## Build and software organization tools

*Build and software organization tools.*

* [Hab (habitat)](https://habitat.sh)

## ChatOps

*Conversation-driven development and management. See https://www.reddit.com/r/chatops for more information.*

* [CloudBot](https://github.com/CloudBotIRC/CloudBot) - The simple, fast, expandable Python IRC bot.
* [Eggdrop](http://www.eggheads.org/) - the world's most popular IRC bot, designed for flexibility and ease of use, and is freely distributable under the GNU GPL.
* [Err](http://errbot.io/) - a plugin based chatbot designed to be easily deployable, extensible and maintainable.
* [Hubot](https://hubot.github.com/) - A customizable, life embetterment robot.
* [Lazlo](https://github.com/djosephsen/lazlo) - A chatops automation framework in Go.
* [Lita](https://www.lita.io/) - A robot companion for your company's chat room.
* [Abot](https://github.com/itsabot/abot) - A digital assistant framework in Go.

## Client management

*Managing software on desktop computers.*

* [Chocolatey](https://chocolatey.org/) – Windows CLI package manager written in .NET/PS, based on [NuGet](https://www.nuget.org/).
* [just-install](http://just-install.it/) – Python script for downloading and silently installing MSI files.
* [OCS Inventory NG](https://ocsinventory-ng.org/?lang=en) - Inventory, deployment and network scan.
* [Opsi](http://www.opsi.org) (open PC server integration) - Client Management for Windows based on Debian.
* [WAPT](https://dev.tranquil.it/wiki/WAPT_-_apt-get_pour_Windows/en) - Network-wide (un)installation, configuration and upgrades of Windows based software.
* [WPKG](http://wpkg.org/) - Software deployment, upgrade and removal program for Windows.

## Cloning

*Cloning software.*

* [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program.
* [Fog](https://www.fogproject.org/) - Another computer cloning solution.

## Cloud Computing

* [OpenStack](https://www.openstack.org/) - Build private and public clouds.

## Cloud Orchestration

* [The Foreman](http://theforeman.org/) - Complete lifecycle management tool for physical and virtual servers. FOSS.
* [MCollective](https://puppet.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
* [Terraform](https://www.terraform.io/) - Terraform works with many cloud providers and creates infrastructure from code.


## Code Review

*Web Based collaborative code review system.*

* [Gerrit](https://www.gerritcodereview.com/) - Based on the Git version control, it facilitates software developers to review modifications to the source code and approve or reject those changes.
* [Phabricator](http://phabricator.org/) - Code review tool build by facebook and used by WikiMedia, FB, dropbox etc. Comes with an integrated wiki, bug tracker, VC integration and a CLI tool called arcanist.
* [Review Board](https://www.reviewboard.org/) - Available as free software under the MIT License.


## Configuration Management Database

*Configuration management database (CMDB) software.*

* [hiera](https://puppet.com/docs/hiera/) - Hierarchal configuration database.
* [i-doit](http://www.i-doit.org/) - IT Documentation and CMDB.
* [iTop](http://www.combodo.com/itop-193) - Complete ITIL web based service management tool.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Clusto](https://github.com/clusto/clusto) - Helps you keep track of your inventory, where it is, how it's connected, and provides an abstracted interface for interacting with the elements of the infrastructure.
* [Collins](http://tumblr.github.io/collins/) - At Tumblr, it's the infrastructure source of truth and knowledge.
* [netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool

## Configuration Management

*Configuration management tools.*

* [CFEngine](https://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
* [Chef](https://www.chef.io/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
* [Puppet](https://puppet.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.

## Continuous Integration & Continuous Deployment

*Continuous integration/deployment software.*

- [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration. ([Source Code](https://github.com/buildbot/buildbot)) `GPL-2.0` `Python`
- [GitLab CI](https://about.gitlab.com/gitlab-ci/) - Gitlab's built-in, full-featured CI/CD solution. ([Source Code](https://gitlab.com/gitlab-org/gitlab-ce) `MIT` `Ruby`
- [Jenkins](https://jenkins-ci.org/) - Continuous Integration Server. ([Source Code](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`

## Control Panels

*Web hosting and server or service control panels.*

* Web hosting
  * [Froxlor](https://froxlor.org/) - Easy to use panel for Linux with Nginx and PHP-FPM support.
  * [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
  * [Sentora](http://sentora.org/) - Control panel for Linux, BSD, and Windows based on ZPanel.
  * [VestaCP](http://vestacp.com/) - Hosting panel for Linux but with Nginx.
  * [Virtualmin](http://www.virtualmin.com/) - Hosting panel for Linux based on webmin.
* DNS
  * [Atomia DNS](http://atomiadns.com/) - DNS management system.
  * [nsedit](https://github.com/tuxis-ie/nsedit) - nsedit is a DNS editor for PowerDNS, working with PowerDNS's new API.
  * [PDNS Gui](https://github.com/odoucet/pdns-gui) - WebGUI which aids in administering domains and records for PowerDNS with MySQL.
  * [Pi-hole](https://pi-hole.net/) - A blackhole for Internet Advertisements with a gui for managing and monitoring
  * [Poweradmin](http://www.poweradmin.org/) - Friendly web-based DNS administration tool for PowerDNS server.
* Revision Control: see [awesome-selfhosted#project-management](https://github.com/Kickball/awesome-selfhosted#project-management)
* Virtualization
  * [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
  * [OpenVZ Web Panel](https://github.com/sibprogrammer/owp) - Web panel to control OpenVZ virtual machines.
  * [WebVirtMgr](https://retspen.github.io) - libvirt-based Web interface for managing virtual machines.
* Server
  * [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
  * [Cockpit](http://cockpit-project.org/) - New multi-server web interface for Linux servers written in C.
  * [Webmin](http://www.webmin.com/) - Linux server control panel.

## Deployment Automation

*Tools and scripts to support deployments to your servers.*

* [Capistrano](http://capistranorb.com/) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based).
* [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.

## Distributed Filesystems

*Network distributed filesystems.*

* [DRBD](http://drbd.linbit.com/) - Distributed Replicated Block Device.
* [Go IPFS](https://github.com/ipfs/go-ipfs) - Implementation of [IPFS](http://ipfs.io/), a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files.
* [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
* [Lustre](http://lustre.org/) - Parallel distributed file system, generally used for large-scale cluster computing.
* [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DNS

*DNS servers.*

* [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
* [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
* [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.

## Domains

*Domain management.*

* [DnsControl](https://stackexchange.github.io/dnscontrol/) - Opinionated platform for seamlessly managing your DNS configuration across any number of DNS hosts, both in the cloud or in your own infrastructure.
* [DomainMOD](https://domainmod.org) - Manage your domains and other internet assets in a central location.
* [octoDNS](https://github.com/github/octodns) - Set of tools and patterns that make it easy to manage your DNS records across multiple providers.

## Editors

*Open source code editors.*

* [GNU Emacs](http://www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more.
* [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
* [Notepad++](https://notepad-plus-plus.org/) - GPLv2 multi-language editor with syntax highlighting for Windows.
* [TextMate](https://github.com/textmate/textmate/) - A graphical text editor for OS X.
* [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.
* [Visual Studio Code](https://code.visualstudio.com/) - An open source cross-platform extensible code editor from Microsoft
* [Nano](http://nano-editor.org) - Easy to use, customizable text editor.

## Identity Management

*LDAP servers and other tools to manage accounts and identities.*

### RADIUS

* [FreeRADIUS](http://freeradius.org/) - High performance and highly configurable multi-protocol policy/authentication server, supporting RADIUS, DHCPv4 and VMPS.

### LDAP

* [389 Directory Server](http://www.port389.org/) - Developed by Red Hat.
* [Apache Directory Server](http://directory.apache.org/) - Apache Software Foundation project written in Java.
* [OpenLDAP](http://www.OpenLDAP.org/) - Developed by the OpenLDAP Project.

### Tools and web interfaces

* [FreeIPA](http://www.freeipa.org/) - 389-DS + Kerberos + BIND DNS + DogTag CA.
* [Fusion Directory](https://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
* [Indieauth](https://indieauth.com/) - Sign in with your domain name (using the rel-me-auth protocol).
* [Libravatar](https://www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites.
* [LDAP Account Manager (LAM)](https://www.ldap-account-manager.org/lamcms/) - Web frontend for managing entries (e.g. users, groups, DHCP settings) stored in an LDAP directory.
* [OpenID Connect](http://openid.net/developers/libraries/) - A Simple Identity layer on top of OAuth 2.0.
* [OSIAM](http://osiam.github.io/) - Secure identity management solution providing REST based services for authentication and authorization.
* [Pomerium](https://www.pomerium.io/) - An identity and context aware access-proxy inspired by BeyondCorp.
* [Samba](https://www.samba.org/) – Active Directory and CIFS protocol implementation.
* [BounCA](https://bounca.org/) - A personal SSL Key / Certificate Authority web-based tool for creating self-signed certificates.
* [easy-rsa](https://github.com/OpenVPN/easy-rsa) - bash script to build and manage a PKI CA.
* [Smallstep Certificates](https://smallstep.com/certificates/) - A private certificate authority (X.509 & SSH) and related tools for secure automated certificate management.

## IT Asset Management

*IT Assets Management software.*

* [GLPI](https://www.glpi-project.org/) - Information Resource-Manager with an additional Administration Interface.
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
* [OPSI](http://www.opsi.org) - Hardware and software inventory, deployment, and patching for Linux and Windows.
* [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Snipe IT](https://snipeitapp.com/) - Asset & license management software.

## Log Management

*Log management tools: collect, parse, visualize ...*

* [Elasticsearch](https://www.elastic.co/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
* [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
* [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
* [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal or through the browser. ([Source Code](https://github.com/allinurl/goaccess)) `MIT` `C`
* [Hindsight](http://mozilla-services.github.io/hindsight/) - Stream processing system which may be used for log aggregation (Replaces Heka).
* [Kibana](https://www.elastic.co/products/kibana) - Visualize logs and time-stamped data.
* [Logstash](https://www.elastic.co/products/logstash) - Tool for managing events and logs.

## Mail Clients

* [Claws Mail](http://www.claws-mail.org/) - Old school email client (and news reader), based on GTK+.
* [ImapSync](http://imapsync.lamiral.info/) – Simple IMAP migration tool for copying mailboxes to other servers.
* [Mutt](http://www.mutt.org/) - Small but very powerful text-based mail client.
* [Nylas Mail](https://www.nylas.com/nylas-mail/) - Extensible mail client.
* [Sylpheed](http://sylpheed.sraoss.jp/en/) – Still developed predecessor to Claws Mail, lightweight mail client.
* [Thunderbird](https://www.mozilla.org/de/thunderbird/) - Free email application that's easy to set up and customize.

## Monitoring

*Monitoring software.*

* [Adagios](http://adagios.org/) - Web based Nagios interface for configuration and monitoring (replacement to the standard interface), and a REST interface, [SourceCode](https://github.com/opinkerfi/adagios), [Documentation](https://github.com/opinkerfi/adagios/wiki))
* [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
* [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
* [cadvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers ([Source Code](https://github.com/google/cadvisor)) `Apache` `Go`
* [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
* [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
* [EdMon](https://github.com/Edraens/EdMon) - A command-line monitoring application helping you to check that your hosts and services are available, with notifications support. `MIT` `Java`
* [ElastiFlow](https://github.com/robcowart/elastiflow) - Network flow Monitoring (Netflow, sFlow and IPFIX) with the Elastic Stack.
* [eZ Server Monitor](http://www.ezservermonitor.com) - A lightweight and simple dashboard monitor for Linux, available in Web and Bash application.
* [Flapjack](http://flapjack.io/) - Monitoring notification routing & event processing system.
* [Healthchecks](https://healthchecks.io/) - Monitoring for cron jobs, background services and scheduled tasks.
* [Icinga](https://www.icinga.org/) - Nagios fork that has since lapped nagios several times. Comes with the possibility of clustered monitoring - ([Source Code](https://github.com/Icinga)) - `GPLv2`
* [LibreNMS](http://www.librenms.org) - Fully featured network monitoring system that provides a wealth of features and device support.
* [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
* [Nagios](https://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
* [Netdata](https://www.netdata.cloud/) - Distributed, real-time, performance and health monitoring for systems and applications. Runs on Linux, FreeBSD, and MacOS.
* [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
* [OMD](http://omdistro.org/) - The Open Monitoring Distribution.
* [Performance Co-Pilot](http://pcp.io) - Lightweight, distributed system performance and analysis framework.
* [psdash](https://github.com/Jahaja/psdash) - A linux system information web dashboard using psut ils and flask.
* [pyDash](https://k3oni.github.io/pydash/) - Small web-based monitoring dashboard for linux.
* [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
* [rtop](https://github.com/rapidloop/rtop) - an interactive, remote system monitoring tool based on SSH.
* [Sensu](https://sensuapp.org/) - Monitoring framework.
* [ServerStatus BotoX](https://github.com/BotoX/ServerStatus) - Display and monitor your servers statistics in a beatiful way.
* [ServerStatus moejda](https://github.com/mojeda/ServerStatus) - Server Status website script, displays uptime (days), free RAM, free HDD
* [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
* [SWMP - Server Web Monitor Page](https://swmp.ml/) - A responsive, eye-pleasing Linux server statistics dashboard.([Source Code](https://github.com/fuzzymannerz/swmp))
* [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken.
* [Uchiwa](https://uchiwa.io/) - Simple dashboard for sensu.
* [Vector](https://github.com/Netflix/vector/) - An on-host performance monitoring framework.
* [Xymon](https://www.xymon.com/) - Network monitoring inspired by Big Brother.
* [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.
* [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.

## Metric & Metric Collection

*Metric gathering and display software.*

* Collectors only
  * [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
  * [Collectd](http://collectd.org/) - System statistic collection daemon.
  * [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
  * [PGObserver](https://github.com/zalando/PGObserver) - Monitoring solution for PostgreSQL databases that also works with AWS RDS.
  * [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.
  * [tcollector](http://opentsdb.net/docs/build/html/user_guide/utilities/tcollector.html) - System statistic collection daemon written in Python for OpenTSDB
  * [Telegraf](https://github.com/influxdata/telegraf) - The plugin-driven server agent for collecting & reporting metrics.

* Dashboards
  * [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
  * [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
  * [RRDtool](http://oss.oetiker.ch/rrdtool/) - Industry standard, high performance data logging and graphing system for time series data.
  * [Dashing](http://dashing.io/) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
  * [Facette](http://facette.io) - Time series data visualization and graphing software written in Go.
  * [Freeboard](https://github.com/Freeboard/freeboard) - A damn-sexy front-end real-time dashboard for the internet of things. Transforms raw JSON into delicious UI.

* Storage
  * [InfluxDB](https://influxdb.com/) - Distributed time series database with no external dependencies.

* Packages
  * [Prometheus](http://prometheus.io/) - Service monitoring system and time-series database.
  * [Packetbeat](https://www.elastic.co/products/beats) - Captures network traffic and displays it in a custom Kibana dashboard for easy viewing.
  * [Graphite](http://graphite.readthedocs.org/en/latest/) - Scalable graphing server and time-series database.

## Network Configuration Management

*Network configuration management tools.*

* [GestióIP](http://www.gestioip.net/) - An automated web based IPv4/IPv6 IP Address Management tool.
* [GNS3](https://www.gns3.com/) - Graphical network simulator that provides a variety of virtual appliances - ([Source Code](https://github.com/GNS3/gns3-gui/), [Documentation](https://docs.gns3.com/)) - `GPLv3`
* [Oxidized](https://github.com/ytti/oxidized) - A modern take on network device configuration monitoring with web interface and GIT storage.
* [phpIPAM](http://phpipam.net/) - Open source IP address management with [PowerDNS](https://www.powerdns.com/) integration.
* [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configuration and maintain history of changes.
* [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.
* [trigger](https://github.com/trigger/trigger) - Robust network automation toolkit written in Python.

## Newsletters

*Newsletter software.*

* [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
* [phpList](https://www.phplist.com/) - Newsletter manager written in PHP.
* [LibreMailer](https://github.com/averna-syd/LibreMailer) - Libre Mailer is a modest and simple web based email marketing application.
* [Lewsnetter](https://github.com/bborn/lewsnetter) - E-mail marketing application (create and send e-mail newsletter via SES). Includes subscription management, delivery, bounce and complaint notification, templates, and some stats.

## NoSQL

*NoSQL databases.*

* Column-Family
  * [Apache HBase](http://hbase.apache.org/) - Hadoop database, a distributed, big data store.
  * [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
* Document Store
  * [CouchBase](https://www.couchbase.com) - NoSQL Key-value store and document database.
  * [ElasticSearch](https://www.elastic.co/) - Text search database.
  * [FlockDB](https://github.com/twitter/flockdb) - Twitter's distributed, fault-tolerant graph database.
  * [Neo4j](http://neo4j.com/) - Graph database.
* Key-Value
  * [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
  * [CouchBase](https://www.couchbase.com) - NoSQL Key-value store and document database.

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

* [habitat (hab)](https://habitat.sh) - Portable Linux packages.
* [omnibus-ruby](https://github.com/chef/omnibus) - Full stack, cross distro packaging software (Ruby).
* [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
* [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.

## Project Management

*Web-based project management and bug tracking systems*: see https://github.com/Kickball/awesome-selfhosted#project-management

## Messaging

### AMPQ

* [ActiveMQ](https://activemq.apache.org/) - Java AMPQ broker.
* [Qpid](https://qpid.apache.org) - Java/C++ AMPQ broker.
* [RabbitMQ](http://www.rabbitmq.com/) - Erlang AMPQ broker. Robust, fully featured, cross distro queuing system.

### MQTT

* [Ejabberd](https://www.ejabberd.im) - XMPP & MQTT broker.
* [Mosquitto](https://mosquitto.org) - MQTT broker.

### Brokerless messaging

* [ZeroMQ](http://zeromq.org/) - Lightweight distributed messaging.
* [Nanomsg](https://nanomsg.org) - Lighterweight distributed messaging.
* [NNG](https://nng.nanomsg.org) - Rearchitected Nanomsg.

### Others

* [Kafka](http://kafka.apache.org) - Extremely high performance publish/subscribe message system.

## Work queues

* [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
* [Celery](http://www.celeryproject.org) - Python work queue.
* [Sidekiq](https://sidekiq.org) - Ruby work queue.

## RDBMSes

*Relational DBMS.*

### MySQL-based

* [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
* [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
  * [adminer](https://www.adminer.org/) -  Database management in a single PHP file ([Source code](https://github.com/vrana/adminer))
* [Percona Server](https://www.percona.com/software) - Enhanced, drop-in MySQL replacement.

### Postgres-/Oracle-based

* [Greenplum](https://greenplum.org) - OLAP Postgres.
* [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable PostgreSQL-based database cluster.

### Local, non-networked RDMSes
* [BDB](https://www.oracle.com/database/technologies/related/berkeleydb.html) - Berkeley DB.
* [CDB](http://cr.yp.to/cdb.html) - CDB.
* [GNU dbm (GDBM)](https://www.gnu.org/software/gdbm/) - GNU db and ndb replacement.
* LDBM.
* NDBM.
* [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional, SQL DBMS.

## Remote Management

* [Tiger VNC](http://tigervnc.org/) - TigerVNC is a high-performance, platform-neutral implementation of VNC (Virtual Network Computing), a client/server application that allows users to launch and interact with graphical applications on remote machines.
* [Remmina](http://www.remmina.org/wp/) - A Feature rich remote desktop application for linux  and other unixes.
* [X2go](http://wiki.x2go.org/doku.php) - X2Go is an open source remote desktop software for Linux that uses the NX technology protocol.
* [rdpwrap](https://github.com/stascorp/rdpwrap) - RDP wrapper library allowing Remote Desktop Host support and concurrent RDP sessions on reduced functionality systems for home usage.

## Service Discovery

* [Consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [etcd](https://github.com/coreos/etcd) - distributed K/V-Store, authenticating via SSL PKI and a REST HTTP Api for shared configuration and service discovery.
* [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Software Containers

*Operating system–level virtualization.*

* [Docker](https://www.docker.com) - Platform for developers and sysadmins to build, ship, and run distributed applications.
  * [Docker Compose](https://docs.docker.com/compose/) - Define and run multi-container Docker applications.
  * [Docker Swarm](https://docs.docker.com/engine/swarm/) - Manage cluster of Docker Engines.
  * [Portainer](https://portainer.io/) - Simple management UI for Docker.
* [rkt](https://coreos.com/rkt/) - Secure containers similar to Docker.
* jails - FreeBSD.

## Status Pages

* [Cachet](https://cachethq.io) - Status page system written in PHP.
* [Stashboard](http://www.stashboard.org) - Status page for cloud services and APIs.
* [Statusfy](https://statusfy.co/) - A modern status page for presenting critical service updates.
* [System Status Dashboard (SSD)](http://www.system-status-dashboard.com/) - Overview about an organization's infrastructure health status.
* [Staytus](http://staytus.co/) - Staytus is a complete solution for publishing the latest information about any issues with your web applications, networks or services.
* [vigil](https://github.com/valeriansaliou/vigil) -  Microservices Status Page. Monitors a distributed infrastructure and sends alerts to Slack. Written in Rust.
* [Statping](https://github.com/hunterlong/statping) - Status page system written in Go.

## Troubleshooting

*Troubleshooting Tools.*

* [genet](https://github.com/genet-app/genet) - Caffeinated Packet Analyzer.
* [grml](https://grml.org) – bootable Debian Live CD with powerful CLI tools.
* [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
* [mtr](https://www.bitwizard.nl/mtr/) - Network utility that combines traceroute and ping.
* [perf-tools](https://github.com/brendangregg/perf-tools) - Performance analysis tools based on Linux perf_events (aka perf) and ftrace.
* [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
* [Wireshark](https://www.wireshark.org/) - The world's foremost network protocol analyzer.

## Version control

*Software versioning and revision control.*

### Distributed Version Control Systems (DVCSes)

* [CVS](https://nongnu.org/cvs/) - Concurrent Version System.
* [Git](https://git-scm.com) - Distributed revision control and source code management (SCM) with an emphasis on speed.
* [Mercurial](https://www.mercurial-scm.org) - Another distributed revision control.
* [Subversion](http://subversion.apache.org) - Client-server revision control system.

### (Local) Version Control Systemes

* [RCS](https://www.gnu.org/software/rcs) - Revision Control System.

## Virtualization

*Virtualization software.*

### Hypervisors
* [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
* [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
* [XCP-ng](http://www.xcp-ng.org/) - Based on Citrix XenServer (based on Xen), XCP-ng is a fully open source virtualization platform.
* [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

### Emulators

* [QEMU](http://www.qemu.org/) - QEMU is a generic machine emulator and virtualizer. It is often used in/with hypervisors such as Xen and KVM.

### Other

* [Archipel](http://archipelproject.org/) - XMPP based virtualization management platform.
* [ConVirt](http://www.convirture.com/products_opensource.php) - Provides the core functionality for centrally managing your KVM or Xen virtualized environment.
* [Ganeti](http://www.ganeti.org/) - Cluster virtual server management software tool built on top of KVM and Xen.
* [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
* [Packer](https://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
* [LibVirt](https://libvirt.org) - Virtualization API.

## VPN

*VPN software.*

* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [strongSwan](https://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [WireGuard](https://www.wireguard.com) - Simple VPN.

## Web

*Web servers.*

* [Apache HTTPD](https://httpd.apache.org) - Less popular web server swiss-army knife.
* [Nginx](https://nginx.org) - Most popular web server, reverse proxy, load balancer and HTTP cache.
* [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance.*

* [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
* [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.

# Resources

Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [Code as Craft](https://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
* [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
* [Rackspace Developers](https://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.
* [RoseHosting Blog](https://www.rosehosting.com/blog/) - Linux tutorials for installing and configuring various software through the Linux command line. Guides and introductions to different Linux technologies and applications. Tips and tricks you can do via the Linux command line and more.

## Books

*Sysadmin related books.*

* [Codex](http://www.starkandwayne.com/codex/) - How to deploy Cloud Foundry PaaS on infrastructures like AWS, OpenStack, Azure by Stark & Wayne, LLC.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
* UNIX and Linux System Administration Handbook (ISBN-13: 978-0131480056) - Approaches system administration from a practical perspective.

## Communities / Forums

*For the social people.*

* [ArsTechnica OpenForum](http://arstechnica.com/civis/) – IT Forum which is attached to a large news site.
* [Reddit](https://www.reddit.com) - Really, really large bulletin board system.
  * [/r/Linux](https://www.reddit.com/r/linux) - News and information about Linux.
  * [/r/LinuxQuestions](https://www.reddit.com/r/linuxquestions)
  * [/r/SysAdmin](https://www.reddit.com/r/sysadmin/)
* [Spiceworks Community](https://community.spiceworks.com/start) – General enterprise IT news and small articles.
* [StackExchange Network](https://stackexchange.com/sites#technology) – Q&A communities.
  * [Server Fault](https://serverfault.com/) – StackExchange community for system and network administrators.

## Newsletters

* [Servers for Hackers](https://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.
* [Web Operations Weekly](http://webopsweekly.com/) - A weekly newsletter on Web operations, infrastructure, performance, and tooling, from the browser down to the metal.

## Repositories

*Software package repositories.*

* [AlternativeTo](http://alternativeto.net) - Find alternatives to software you know and discover new software.

### Debian-based distributions

* [deb.sury.org](https://deb.sury.org/) - Repository with LAMP updated packages for Debian and Ubuntu.

### RPM-based distributions

* [ElRepo](http://elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
* [EPEL](https://fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
* [IUS](https://ius.io/) - Community project that provides RPM packages for newer versions of select software for Enterprise Linux distributions.
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.
* [Software Collections](https://www.softwarecollections.org) - Community Release of [Red Hat Software Collections](https://access.redhat.com/documentation/en/red-hat-software-collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.

## Websites

*Useful sysadmin related websites.*

* [Awesome SysAdmin @ LibHunt](https://sysadmin.libhunt.com) - Your go-to SysAdmin Toolbox. Based on the list here.
* [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics.

## Wikis

*Useful Wikis for Sysadmins – not to be confused with Wiki software.*

* [ArchWiki](https://wiki.archlinux.org/) – Arch Linux Wiki which has really nice written articles valid for other distros.
* [Gentoo Wiki](https://wiki.gentoo.org/) - Gentoo Linux Wiki with a lot in-detail description of Linux components.

## License

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license.
