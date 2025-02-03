# Uniswap V3 Liquidity & Swap Contracts

## Overview
This project implements Uniswap V3 functionalities for USDT/ETH trading pair, including:
- Swapping USDT and ETH
- Minting liquidity positions
- Increasing liquidity in an existing position
- Decreasing liquidity from a position

The project is built using Foundry, and all test cases are executed on a mainnet fork.

## Smart Contracts
1. **Swap Contract**: Handles token swaps within Uniswap V3.
2. **Liquidity Contract**: Manages liquidity operations like minting, increasing, and decreasing liquidity.

## Installation & Setup
### Prerequisites
- Install [Foundry](https://book.getfoundry.sh/getting-started/installation)

### Clone the Repository
```sh
git clone https://github.com/iamNickDev/uniswapV3.git
cd uniswapV3
```

### Install Dependencies
```sh
forge install
```

## Running Tests
All test cases are executed on a mainnet fork. Use the following command to run the tests:
```sh
forge test --fork-url https://eth-mainnet.g.alchemy.com/v2/APIKEY --fork-block-number 21764284 -vvvv
```
Replace `APIKEY` with your Alchemy API key.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to reach out at [nandkishore.dev@gmail.com].

