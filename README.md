# supersonic-core
High-frequency perpetuals engine on Arbitrum. (Audit in progress)
# Velox Protocol Core (v0.1.0-alpha)

![License](https://img.shields.io/badge/license-Proprietary-red)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Audit](https://img.shields.io/badge/audit-scheduled-orange)

**Velox Protocol** is a high-frequency, oracle-dependent perpetual exchange engine built for Arbitrum One.

## 🚧 访问受限通知 (Access Restricted)

> **SECURITY NOTICE:**
> The core smart contracts (`Velox-Vault`, `OrderRouter`, `LiquidationEngine`) have been moved to a **private repository** for the duration of the pre-launch security audit.
>
> We are currently undergoing formal verification with **Trail of Bits**. Public source code access will be restored in **Q3 2026** upon Mainnet launch.

## Architecture Overview

The protocol consists of three primary modules:
1.  **Vault Diamond:** Manages collateral custody and PnL settlements.
2.  **Oracle Guard:** Consumes sub-second price updates (Chainlink Data Streams) to filter toxic flow.
3.  **Position Manager:** Handles leverage calculation and liquidation triggers.

## Integration Requirements

To run the local testnet environment, you must hold valid credentials for:
*   Arbitrum Sepolia RPC
*   Chainlink Data Streams (Verifier Proxy)

## Contact

For partnership inquiries or early access to the SDK:
📧 **founder@supersonic-fi.com**
