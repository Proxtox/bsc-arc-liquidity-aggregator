# bsc-arc-liquidity-aggregator

DEX aggregator example routing stablecoin trades between BSC and Arc using CCTP.

## Overview
Educational starter for building cross-chain liquidity aggregators focused on stablecoins between BNB Chain (BSC) and Circle's Arc L1.

## Tech Stack
- Solidity
- Hardhat
- CCTP (Circle Cross-Chain Transfer Protocol)

## Getting Started
```bash
git clone https://github.com/Proxtox/bsc-arc-liquidity-aggregator.git
cd bsc-arc-liquidity-aggregator
npm install
```

## Key Contract
`contracts/LiquidityAggregator.sol` - Basic routing and quote logic

## Next Steps
- Integrate real CCTP contracts
- Add PancakeSwap + Arc DEX quotes
- Build frontend with best-route display
- Add slippage protection

## License
MIT