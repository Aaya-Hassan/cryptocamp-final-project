# cryptocamp-final-project

## Dependencies
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Step 1. Install dependencies
```
$ npm install
```

## Step 2. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 3. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 4. Configure Metamask
- Unlock Metamask.
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 5. Run the Front End Application
`$ npm run dev`
Open URL in your browser: http://localhost:3000

## Step 6. What does project do
Voting Smart Contract :

Create an voting smart contract that operates on Ethereum on the blockchain

- There are a list of candidates that the administrator of elections.
- Anyone with an Ethereum address can vote for a candidate using metamask. Each person can only vote once form of the vote will hide when vote until use another Ethereum address.

## Step 7. Application demo
![Voting Smart Contract Demo](src/images/Media1.gif)