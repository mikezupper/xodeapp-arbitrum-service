# Overview

## What is the problem? 

Livepeer relies on the block data generated from Arbitrum. Up to the second, block data is essential for healthy Livepeer operatons. Reliable RPC access to Arbitrum WITHOUT limits is absolutely critical.

## Options For Reliable RPC

There are several options when deciding on which service providers to use.

The commons options:
    1. Public RPC Access
    2. General RPC Service Providers
    3. Self-Hosted
    4. LP Community Node

# Infrastructure

The high level architecture consists of multiple layers. Each layer is responsible for specific functions within the infrastructure : 

security, redundency, scalability, and high availability.  

As noted in the figure #1, Arbitrum is dependent on Etherium. Redundency is critical for each layer in the network /application stacks. 

The outermost layer - Cloudflare will be responsible for many aspects of this highly-available cluster. The major areas of focus are geo routing, proxying, and security.

The next layer consists of redundent Virtual Private Servers (VPS). For Arbitrum it is 3 strategicly geo-located VPS. For Etherium it is 2 European nodes (less of a concern for latency).  


## Figure #1 - Layered Architecture

![High Level Overview](assets/ArbitrumNodeOperations.jpg?raw=true)

[Deep Dive - Architecture Details](detailed-architecture/README.md)


# Benefits
    - 99.99% uptime
    - GEO Redundancy
    - Off hours support
    - 0 Down-time Maintenece
    - Operational Transparency

# Costs
    - fixed costs
    - support costs
    - R&D costs

## Value Proposition - Xodeapp RPC Access

    1. Specific to Livepeer Orchestrators - Only
    2. Highly Available - No down-time deployments, Geo Location for lowest latency
    3. Secure - Completly isolated behind Cloudflare Infrastructure.
    4. Monitored - Grafana Access to all members
        - Node Health
        - ARb Health
        - Cloudflare  Netowk health
    5. No Rate Limiting
    6. Flexible Pricing
    7. Completely Transparent - No "get rich scheme /fly-by-night scheme" 
    
## Transparency
    - Public Income / Expense Report
    - Dashboards and Reportings
    - 
## SLA - Service Level Agreements
    - 99.98% is the goal, but Arbitrum is beta. Unpredictable outages can occur. These items will b

# Support / Maintenece
    - 24/7 Monitoring (not in place as 7/10)
    - Research and Development:
        * faster hardware
        * better datacenters
        * closer geo location
        * reporting and filing defects with LP code. i.e. blocking watcher polling issues

# Roadmap
    - Prepare for Upcoming Arbitrum Nitro and ETH 2.0 upgrades
    - Get Automated backups in place
    - Hire first Support Rep
    - Finalize Member payment structure
    - Integrate Auth via FTK Cli approach
    