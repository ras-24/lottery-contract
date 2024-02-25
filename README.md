# lottery-contract
Lottery Smart Contract

## Getting Started
This is an example of how you can set up this project locally.
To get a local copy up and running, follow these steps.

## Installation
1. Clone the repo
   ```sh
   git clone https://github.com/ras-24/lottery-contract.git
   ```
2. Go to lottery contract directory
   ```sh
   cd lottery-contract
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. On deploy.js file, please change to your seed phrase and infura endpoint
   ```sh
   const provider = new HDWalletProvider(
     "YOUR_MNEMONIC",
      // remember to change this to your own phrase!
      "YOUR_INFURA_URL"
      // remember to change this to your own endpoint!
   );
   ```
5. Deploy lottery contract
   ```sh
   node deploy.js
   ```
6. Copy **Contract Deployed Address** and **Contract ABI** to [lottery contract frontend](https://github.com/ras-24/lottery-react-contract/blob/main/src/lottery.js)

