# Secure Hybrid Datacenter Network

## Overview

A Cisco Packet Tracer-based secure hybrid datacenter network designed
with VLAN segmentation, inter-VLAN routing, ACL-based access control,
SSH administration, and switch port security.

## Network Components

- Cisco 1941 Routers
- Cisco 2960 Switches
- Admin PC
- Faculty PC
- Application Server
- Database Server

## VLAN Design

| VLAN | Name | Purpose |
|------|------|---------|
| 10 | MANAGEMENT | Network management |
| 20 | FACULTY | Faculty users |
| 30 | APP1 | Application services |
| 40 | APP2 | Reserved application segment |
| 50 | DATABASE | Database services |

## Security Features

- VLAN-based network segmentation
- 802.1Q trunking
- Router-on-a-Stick inter-VLAN routing
- Extended ACLs
- SSH version 2
- Switch port security
- Sticky MAC address learning
- Restricted unauthorized-device access

## Security Validation

The implementation was tested using controlled connectivity tests.

- Faculty → Application: Allowed
- Faculty → Database: Blocked
- Faculty → Management: Blocked
- Application → Database: Allowed
- Application → Management: Blocked

## Project Files

The Packet Tracer `.pkt` file and configuration/evidence files
are included in this repository.