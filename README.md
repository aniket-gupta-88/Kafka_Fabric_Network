# BE_RESEARCH_HF_SOLO

This repository is a research project for Hyperledger Fabric using Kafka ordering system.

## Graph3 Branch

The `Graph3` branch is configured with the following parameters:

### Configurations Done
- Number of orderers: 3
- Number of peers: 5
- Batch timeout: 2
- Number of Caliper workers: 5
- Number of transactions in Caliper: 1000
- TPS (Transactions Per Second) of Caliper: 100

### Parameter to Be Changed
Test Batch Size with Different Values

For testing purposes, you can adjust the batch size parameter. Please refer to line 111 in the `artifacts/channel/configtx.yaml` file to make changes.

Note: File Location - `artifacts/channel/configtx.yaml` (line: 111)
