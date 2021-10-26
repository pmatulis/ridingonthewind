---
layout: single
title: "OpenStack Charms 21.10"
excerpt: |
  Software features
tagline: |
  OpenStack on Ubuntu
date: 2021-10-22
last_modified_at: 2021-10-22
categories: cloud
tags: juju ubuntu openstack
permalink: /:categories/:title/
header:
  overlay_image: /assets/images/oc-2110-clouds-1.png
  overlay_filter: rgba(21, 10, 0, 0.2)   # https://rgbacolorpicker.com/
  caption: "Photo credit: [**Fatih**](https://unsplash.com/@gozlukluf?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)"
  og_image: /assets/images/oc-clouds-b.jpg
  teaser: /assets/images/oc-clouds-b.jpg
---

[Canonical][canonical] has just released its latest version of the OpenStack
Charms project. This project consists of a collection of (62) [Juju][juju]
charms that makes the deployment and management of an [OpenStack][openstack]
cloud way easier than using the base tooling.

This is a quick post to highlight the main changes in OpenStack Charms 21.10.
Check it out.

# OpenStack Xena

OpenStack Xena is now supported on Ubuntu 20.04 LTS (via [UCA][uca]) and Ubuntu
21.10 natively.

# Cinder storage backend charms

Two stable charms are now available that provide LVM and NetApp storage
backends for Cinder. The new charms are cinder-lvm and cinder-netapp
respectively. The cinder-lvm charm deprecates the LVM functionality of the
cinder charm. A migration path is available.

# Cloud operational improvements

Improvements have been implemented at the operational level through the
addition of many actions and configuration options to the current set of stable
charms.

# Tech-preview charms

Two tech-preview charms are now available. The ceph-dashboard charm deploys the
Ceph Dashboard and the openstack-loadbalancer charm deploys a load balancer for
OpenStack applications that support the charm.

# Documentation updates

Ongoing improvements to the OpenStack Charms Deployment Guide, the OpenStack
Charm Guide, and the charm READMEs.

<!-- LINKS -->

[canonical]: https://canonical.com
[juju]: https://juju.is
[openstack]: https://openstack.org
[uca]: https://wiki.ubuntu.com/OpenStack/CloudArchive
