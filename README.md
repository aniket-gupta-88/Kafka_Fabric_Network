# BE_RESEARCH_HF_SOLO

This repository is a research project for Hyperledger Fabric using the Kafka ordering system.

## Graph7 Branch

The `Graph7` branch is configured with the following parameters:

### Configurations Done
- Number of orderers: 3
- Number of peers: 5
- Block batch size: 10
- Block batch timeout: 2
- Number of caliper workers: 5
- Number of transactions in caliper: 1000

### Parameter to Be Changed
#### Test TPS (Transactions Per Second) of Caliper with Different Values

For convenience, a variable called `tps` has been created to easily adjust the TPS of caliper. If any errors occur, the correct code is provided below the variable for quick reference.

Note: File Location - `caliper/caliper-benchmarks-local/config.yaml`
