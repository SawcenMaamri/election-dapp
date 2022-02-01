# Election DAPP

##### Created by Sawcen Maamri (GLSI-3-P) & Lassaad Aissa (GLSI-3-N)

<br>

This a DAPP application called election that let people vote for their desired candidates in elections.
Voting on the blockchain app costs Ethereums (a small fee), but just seeing a list of candidates does not.

<br>
____________________________________

<br>

## Dependencies

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
$ npm install -g truffle
```

<br>
____________________________________

<br>

## Step 2. Start Ganache

We open the Ganache GUI client that you we downloaded and installed. This will start our local blockchain instance.

<br>
____________________________________

<br>

## Step 3. Compile & Deploy Election Smart Contract

`$ truffle migrate --reset` <br>
We must migrate the election smart contract each time we restart ganache.

<br>
____________________________________

<br>

## Step 4. Configure Metamask

- We Unlock Metamask 

- We connect metamask to our local Etherum blockchain provided by Ganache. 

- We import an account provided by ganache. 

<br>
____________________________________

<br>

## Step 5. Run the Front End Application

`$ npm run dev`
