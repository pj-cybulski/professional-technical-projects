# Shared Media Storage Environment

## Project Overview

Supported and documented a Blackmagic Cloud Store shared-storage
environment used by multiple production and communications
workstations.

The system provided high-speed shared media access to primary production
workstations while also allowing additional users to access and transfer
media through a lower-bandwidth connection path.

The environment was designed so storage traffic and normal office
network traffic used separate workstation network interfaces.

## My Role

My responsibilities included supporting workstation access to the shared
storage environment, troubleshooting connectivity and performance
issues, maintaining system documentation, and helping staff understand
how the storage environment was intended to operate.

I also documented the physical and logical topology, workstation access
paths, port relationships, intended traffic flow, and support boundaries
between department-managed equipment and centrally managed network
infrastructure.

## System Design

The environment included:

- Blackmagic Cloud Store shared storage
- Four dedicated 10Gb workstation storage connections
- Two additional workstations using a shared 1Gb access path
- Dual-network-interface workstations
- Patch-bay infrastructure
- Local Ethernet switching
- Separate managed-network connectivity
- Shared media workflows across multiple users

The primary production workstations used dedicated 10Gb connections for
high-speed storage access.

Each workstation also maintained a separate network connection for
normal organizational network and internet traffic.

Two additional workstations accessed the Cloud Store through a 1Gb
extension path intended primarily for file transfer and collaborative
media access.

## Traffic Separation

A key part of the design was keeping shared-storage traffic separate
from normal office network traffic.

The high-speed media workstations were expected to communicate directly
with the Cloud Store using their dedicated storage interfaces, while
their second network interfaces handled normal organizational network
and internet access.

This separation reduced unnecessary dependence on the managed office
network for high-bandwidth media traffic.

## Troubleshooting and Support

Supporting the environment required determining whether an issue was
related to:

- Workstation network configuration
- Storage-interface selection
- Link speed
- Physical patching or cabling
- Network adapters
- Shared-storage access
- Local switching
- The centrally managed network uplink

The documentation was intended to make those relationships easier to
understand and to help future staff isolate problems without treating
the storage system as a single undifferentiated network connection.

## Support Boundaries

The environment included both department-supported equipment and
centrally managed network infrastructure.

Part of supporting the system was identifying where a problem could be
handled locally and when an issue crossed into infrastructure managed by
central IT.

That distinction helped avoid unnecessary changes to managed network
equipment while still allowing effective troubleshooting of workstation,
storage, patching, and local connectivity issues.

## Documentation

I created internal documentation covering:

- Physical topology
- Logical design
- Workstation and endpoint roles
- Port relationships
- Intended traffic flow
- Operating notes
- Troubleshooting guidance
- Support boundaries

For this public portfolio, organization-specific details are omitted and
the project is presented as a generalized example of the environment and
support work.

## Skills Demonstrated

- Shared storage support
- 10Gb Ethernet connectivity
- Workstation network configuration
- Dual-NIC systems
- TCP/IP troubleshooting
- Network-path analysis
- Physical connectivity and patching
- Performance troubleshooting
- Technical documentation
- Support-boundary recognition
- Escalation to central IT
- Multi-user production systems

## Project Context

This project represents a professional shared-storage environment I
supported and documented during my municipal government career.

The public portfolio version focuses on the technical architecture,
support responsibilities, troubleshooting approach, and documentation
skills while omitting organization-specific operational details.
