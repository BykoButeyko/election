# Election Dapp

You can vote easily for your candidate in a trusted way with this Dapp using the blockchain, more precisely via Ethereum network.

The special feature of this Dapp is that you can vote from once per address.


## Dependencies

Install these prerequisites.

    - NPM: https://nodejs.org
    - Truffle: https://github.com/trufflesuite/truffle
    - Ganache: http://truffleframework.com/ganache/
    - Metamask: https://metamask.io/

## Step 1. Clone the project

`git clone https://github.com/BykoButeyko/election`

## Step 2. Install dependencies

```
$ cd election
$ npm install
```

## Step 3. Start Ganache

Open the Ganache GUI client that you downloaded and installed. Start your local blockchain.

## Step 4. Compile & Deploy Election Smart Contract

`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask

    -Unlock Metamask
    -Connect metamask to your local Etherum blockchain provided by Ganache.
    -Import an account provided by ganache.


## Step 6. Run the Front End Application

`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

## Step 7. Vote for a candidate 