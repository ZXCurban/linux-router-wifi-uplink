# Troubleshooting


The following issues were encountered during real usage
and were not obvious from documentation alone.

## Multiple subnets on a single interface
Leads to ambiguous routing and broken connectivity.

## NetworkManager interference
Automatic route and gateway injection can override
explicit configuration.

## Missing NAT after reboot
iptables rules are cleared by default and must be persisted.

## Silent failures
Most issues did not produce errors, only broken traffic flow.

