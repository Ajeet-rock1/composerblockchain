# Develop in a cloud sandbox

There is a single script install available as well as full documentation on individual commands for custom installations.

You will need to clone this repository to get the relevant bash scripts and YAML files.

# Privacy Notice
For serviceability needs regarding the number of network activity, added a mechanism in the ordering service to collect a "pulse" from the networks. The UUID of a network is collected periodically and sent to a monitoring service, there is no blockchain or transaction information or data gathered or accessed. The only purpose is to provide information on activity passing through the ordering service.

The UUID is generated by the network randomly when the orderer comes up and is not attached to any further network information. The UUID is re-generated and old UUID lost whenever the ordering service is restarted.
