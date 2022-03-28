# Decentralized Blog with CMS

This is an example of decentralized blog application using solidity scripting lanuage. Essentially, an frontend dev's exploration into using blockchain for something other than cryptocurrency. Why not a Blog?

Initial observations about decentralized apps:
1) So far dApps are slow but that is the known limitation being focused on by the computer industry as of 2022.
2) Shouldn't have a huge impact on frontend development as we are still using React and GraphQL (The Graph) to interact with the application binary interface. Frontend data provided by API or ABI.


```
npx hardhat node
```

use Localhost:8545

Add Account to MetaMask

Use Private Key with MetaMask - chrome extension

```
npx hardhat run scripts/deploy.js --netowrk localhost
```

```
yarn dev
```
or
```
yarn build
yarn start
```

Deploy to the graph

```
cd /blogcms
yarn deploy
```
