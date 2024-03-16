# BE_RESEARCH_HF_SOLO

This repository is a research project for Hyperledger Fabric using the Kafka ordering system.

## Graph5 Branch

The `Graph5` branch is configured with the following parameters:

### Configurations Done
- Number of orderers: 3
- Number of peers: 5
- Block batch size: 10
- Block batch timeout: 2
- Number of transactions in Caliper: 1000
- TPS (Transactions Per Second) of Caliper: 100

### Parameter to Be Changed
#### Test Caliper worker with Different Values

Note: File Location - `caliper/caliper-benchmarks-local/config.yaml` (line: 4)
