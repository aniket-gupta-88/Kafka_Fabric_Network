# BE_RESEARCH_HF_SOLO

This repository contains a research project for Hyperledger Fabric using the Kafka ordering system.

## Graph3 Branch

The `Graph3` branch is configured with the following parameters:

### Configurations Done
- Number of orderers: 3
- Number of peers: 5
- Block batch size: 10
- Block batch timeout: 2
- Number of caliper workers: 5
- TPS (Transactions Per Second) of caliper: 100

### Parameter to Be Changed
For convenience, a variable called `txNumber` has been created to easily adjust the test transaction count. If any errors occur, the correct code is provided below the variable for quick reference.

Note: File Location - `caliper/caliper-benchmarks-local/config.yaml`
