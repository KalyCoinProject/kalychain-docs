---
description: KalyChain consensus protocols
---

# Consensus protocols

KalyChain supports [QBFT](qbft.md) (proof of authority) - The recommended
  enterprise-grade consensus protocol for private networks.


The `config` property in the genesis file specifies the consensus protocol for a chain.

!!! example

    === "QBFT"

        ```json
        {
          "config": {
            ...
            "qbft": {
              ...
            }
          },
          ...
        }
        ```
