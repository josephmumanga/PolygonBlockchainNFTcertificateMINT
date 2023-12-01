# NFT Minting Application

This project comprises a simple web application for minting NFTs (Non-Fungible Tokens) using the MetaMask wallet and a corresponding Ethereum smart contract. Users can mint NFTs by connecting their MetaMask wallet to the application, and the smart contract facilitates the minting process on the Ethereum blockchain.

## Table of Contents
1. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
2. [Usage](#usage)
3. [Dependencies](#dependencies)
4. [Contributing](#contributing)
5. [License](#license)

## Getting Started

### Prerequisites
Before starting, ensure you have the following requirements installed and configured:

- [MetaMask](https://metamask.io/): MetaMask extension installed in your browser.
- [Node.js](https://nodejs.org/): Ensure Node.js is installed on your machine.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```
## Usage

### Backend (Smart Contract)
Upload MyNFT.sol into Remix IDE, complile and deploy the contract to your blockchain network of choice, ensuring proper configuration and network connection within Remix IDE or your preferred blockchain development environment.

### Frontend (HTML)
1. Open `index.html` in a web browser.

2. Ensure MetaMask is installed and connected to your blockchain network wallet.

3. Update your ABI, contract Address, recipient Adress and tokenURI accordingly.

4. Click on the "Mint NFT" button to mint a new NFT.

5. Check the browser console for status messages.

## Dependencies
- [Web3.js](https://web3js.readthedocs.io/): Ethereum JavaScript API for interaction with smart contracts.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## License
This project is licensed under the MIT License.
