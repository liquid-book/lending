# LiquidBook Lending Protocol

A lending protocol implementation designed specifically for LiquidBook's orderbook to enable rehypothecation capabilities. This protocol allows traders to reuse their active orders as collateral, enhancing capital efficiency within the LiquidBook ecosystem.

## 📋 Overview

This lending protocol is tightly integrated with LiquidBook's orderbook to:
- Enable traders to use their active orders as collateral
- Allow borrowing against orderbook positions
- Implement rehypothecation for increased capital efficiency
- Manage lending operations while orders are still active in the orderbook

## 🔄 Integration with LiquidBook

### Rehypothecation Flow
1. Trader places order in LiquidBook orderbook
2. Order can be used as collateral in lending protocol
3. Borrowed assets can be used to place new orders
4. New orders can again be used as collateral


## 💡 Features

### Order-Based Lending
- Use active orders as collateral
- Dynamic collateral valuation based on order prices
- Automatic collateral management with order execution
- Integration with LiquidBook's order matching

## 🛠️ Technical Stack

- **Language**: Solidity
- **Framework**: Foundry
- **Testing**: Forge
- **Deployment**: Foundry Cast
- **Network**: Arbitrum

## 🚀 Getting Started

### Prerequisites

1. Install Foundry:
```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

2. Install dependencies:
```bash
forge install
```

### Building

1. Clone the repository:
```bash
git clone [[repository-url]](https://github.com/liquid-book/lending)
cd lending
```

2. Build the project:
```bash
forge build
```

3. Run tests:
```bash
forge test
```

Run the test suite:
```bash
forge


## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
