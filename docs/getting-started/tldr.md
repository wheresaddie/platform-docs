# hello world: 

Welcome to Frequency! Frequency is an open, decentralized protocol designed to power next-generation applications.

---

## Table of Contents

- [Prerequisites](#prerequisites)
  - [Hardware](#hardware)
- [Building Frequency](#building-frequency)
  - [Local Desktop](#local-desktop)
  - [Remote Instance (e.g., AWS EC2)](#remote-instance-eg-aws-ec2)
- [Running a Node](#running-a-node)
  - [Collator Node without Relay Chain](#collator-node-without-relay-chain)
  - [Collator Node with Local Relay Chain](#collator-node-with-local-relay-chain)
- [Design Documents](#design-documents)
- [Additional Resources](#additional-resources)
- [Miscellaneous Tips](#miscellaneous-tips)

---

## Prerequisites

Before you start, ensure you have the following:

### Hardware

- A computer with at least 8GB RAM and 50GB free disk space is recommended.

For a detailed environment setup, see [Prep Substrate environment for development](https://docs.substrate.io/install/) 

---

## Building Frequency

### Local Desktop

Clone the Frequency repository and follow the instructions to build locally. Frequency supports development environments like `XX and Y`. (not live yet lol)

### Remote Instance (e.g., AWS EC2)

Frequency can also be built and run on remote cloud instances. Ensure your instance meets the hardware requirements and has the necessary dependencies installed.

---

## Running a Node

You can run Frequency nodes in several configurations:

### Collator Node without Relay Chain

You can run a standalone collator node using different block sealing mechanisms:

- **Manual Sealing**
- **Instant Sealing**
- **Interval Sealing**

Refer to the documentation for specific command-line arguments and configuration details

### Collator Node with Local Relay Chain

You can also run a Frequency collator node connected to a local relay chain, using either a mixed Terminal/Docker setup for maximum flexibility 

---

## Design Documents

If you wish to contribute to Frequency's protocol or features, check out our design documents. These cover:

- Accounts
- On-Chain Message Storage
- Delegation
- Message Schemas
- Provider Permissions and Grants

New design docs should follow the template in the [Design Doc README](https://github.com/frequency-chain/meta/blob/main/DESIGN_DOCS.md). See the [meta repository](https://github.com/frequency-chain/meta) for details and contribution guidelines.

---

## Additional Resources

- [Cumulus Project](https://github.com/paritytech/cumulus)
- [Cumulus Tutorials](https://docs.substrate.io/tutorials/)
- [Prep Substrate environment for development](https://docs.substrate.io/install/) 

---

## Get Involved

Join our community, ask questions, and start building! For issues, feature requests, or to contribute, visit our [GitHub Issues](https://github.com/frequency-chain/frequency/issues) and tag (dev rel person here)

Welcome to the Frequency developer community!
