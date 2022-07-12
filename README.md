# Overview
    - Whats the problem?
    - Why pay?
        ** Why not use Community Node?
    - Is this sustainable?

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
    