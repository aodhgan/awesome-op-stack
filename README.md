# Awesome Op Stack [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Awesome Op Stack** is a list of Op Stack modifications.

### Op Stack Official Links

+ [Op Stack Codebase](https://github.com/ethereum-optimism/optimism)
+ [Introduction to OP Stack Hacks](https://stack.optimism.io/docs/build/hacks/): detailed guide on how to "mess around" with the OP Stack. 


### Modifications

- **[Op Stack Hooks](https://github.com/AlexBHarley/op-stack-hooks)**: An OP Stack Mod for adding customisable transaction hooks to your OP Stack chain. Hook registration is permissioned in this mod, meaning hook registration is priviledged and only rollup deployers can add these.

- **[Op Stack Hyperlane](https://github.com/AlexBHarley/op-stack-hyperlane)**: An OP Stack Mod that bundles a Hyperlane ⏩ deployment into your L2. With Hyperlane now a core part your L2 you benefit from:
    - opt in fast token withdrawals 🔥
    - predeployed Mailbox's and associated ISMs
        - L1 => L2 leverages an Optimism ISM that maintains the security of Ethereum
        - L2 => L1 configured with an M of N multisig
    - default relayer and validator infrastructure

- **[PBS on Optimism](https://github.com/NethermindEth/optimism/pull/5)**: Changes needed on OP stack to integrate mev-boost implementation of Proposer Builder Separation protocol. [More info](https://gov.optimism.io/t/optimism-pbs-proof-of-concept/6718).

- **[Op Craft](https://github.com/latticexyz/opcraft)**: OPCraft was an OP Stack chain that ran a modified EVM as the backend for a fully onchain 3D voxel game built with MUD.

- **[Ticking Optimism](https://github.com/therealbytes/ticking-optimism)**: Ticking Optimism is a proof-of-concept implementation of an OP Stack chain that calls a tick function every block. By using the OP Stack, Ticking Optimism avoids the need for off-chain infrastructure to execute a function on a regular basis. 

### Setup Tools
- **[Simple Op Stack Rollup](https://github.com/0xFableOrg/simple-op-stack-rollup)**: simple-op-stack rollup is open-source package that makes it trivial for any developer to spin up an OP stack rollup, both for development and production use.

### Monitoring Tools
- **[Pessimism](https://base-org.github.io/pessimism/heuristics)**: an open source monitoring system designed to enhance the security of Base (as well as the broader OP Stack and Ethereum ecosystems) by quickly detecting and responding to a myriad of protocol threats.

