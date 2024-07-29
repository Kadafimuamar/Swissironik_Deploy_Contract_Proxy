# Swisstronik Deploy Proxy

This project sets up a Hardhat environment to deploy and interact with an proxy contract on the Swisstronik testnet. Follow the steps below to get started.

## Prerequisites

Ensure you have the following installed:
- Node.js
- npm

## Faucet

https://faucet.testnet.swisstronik.com/

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/Kadafimuamar/Swissironik_Deploy_Contract_Proxy.git
    cd Swissironik_Deploy_Contract_Proxy
    ```

2. Run

    ```bash
    npm install --save-dev @nomicfoundation/hardhat-toolbox
    npm install dotenv
    npm install @swisstronik/utils
    npm install @openzeppelin/contracts
    ```

## Create File .env for Private Key (Keep Safe for this)

1. Create .env File

```bash
PRIVATE_KEY=YOUR-PRIVATE-KEY
```

## Running

1. Compile

 ```bash
    npx hardhat compile
```

2. Deploy Proxy

```bash
npx hardhat run scripts/deploy.js --network swisstronik
```

```bash
npx hardhat run scripts/getMessage.js --network swisstronik
```

```bash
npx hardhat run scripts/setMessage.js --network swisstronik
```

