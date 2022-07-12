
Architecture Details

The entry point to the architecture is the DNS name hosted on Cloudflare. 

arb.xodeapp.xyz or eth.xodeapp.xyz - For RPC access to Arbitrum and Etherium respectively

1. Clouldflare Load Balancing (an enterprise feature) - High Availablility / Scalability
    * enabled zero-downtime deployments.  
    * reports and metrics on usage.  
    * DDos protection
    * and more...
2. Cloudflare Tunnel - Security
    * No external ports opened on VPS
    * Edge-based geo routing/proxying for lowest latency 



