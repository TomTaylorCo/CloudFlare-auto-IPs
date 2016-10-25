CloudFlare-auto-IPs v0.2
===================

Automaticlly update your server's firewall to allow CloudFlare IPs

Features:
Works with CSF and IPtables
Runs each day checking for new CF IPs to add

How to install - one line copy, paste, execute (CPe):

```
wget -q https://raw.githubusercontent.com/TomTaylorCo/CloudFlare-auto-IPs/master/cf.sh -O cf.sh && chmod +x cf.sh && ./cf.sh
```

This will setup the script in your server for to run each day checking for new IPs to add.


Checkout the spawn of this script: StatusCake-auto-IPs: https://gist.github.com/t0mtaylor/d36d482be8284fb4cc4866eb05d53d97
