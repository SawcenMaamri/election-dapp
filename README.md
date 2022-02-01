# Election DAPP

##### Created by Sawcen Maamri (GLSI-3-P) & Lassaad Aissa (GLSI-3-N)

<br>

This a DAPP application called election that let people vote for their desired candidates in elections.
Voting on the blockchain app costs Ethereums (a small fee), but just seeing a list of candidates does not.

<br>
____________________________________

<br>

## Dependencies

Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

<br>
____________________________________

<br>

## Step 1. Install dependencies

```
$ cd election
$ npm install
```

<br>
____________________________________

<br>

## Step 2. Start Ganache

Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.

<br>
____________________________________

<br>

## Step 3. Compile & Deploy Election Smart Contract

`$ truffle migrate --reset` <br>
You must migrate the election smart contract each time your restart ganache.

<br>
____________________________________

<br>

## Step 4. Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

<br>
____________________________________

<br>

## Step 5. Run the Front End Application

`$ npm run dev`
