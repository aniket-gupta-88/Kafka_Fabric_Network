# BE_RESEARCH_HF_SOLO

This repository is a research project for Hyperledger Fabric using the Kafka ordering system.

## Graph3 Branch

The `Graph3` branch is configured with the following parameters:

### Configurations Done
- Number of orderers: 3
- Number of peers: 5
- Block batch size: 10
- Number of Caliper workers: 5
- Number of transactions in Caliper: 1000
- TPS (Transactions Per Second) of Caliper: 100

### Parameter to Be Changed
#### Test Batch Timeout with Different Values

For testing purposes, you can adjust the batch timeout parameter. Please refer to line 110 in the `artifacts/channel/configtx.yaml` file to make changes.
