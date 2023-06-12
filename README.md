# Kennel Club Graph Indexer
Link to backend: https://github.com/StroupZ/Kennel-Club-Backend
<br>
Link to frontend: https://github.com/StroupZ/Kennel-Club
<br><br>
This is the 'The Graph' protocol indexer portion for the Kennel Club NFT Marketplace... a dApp which enables the buying, listing, managing, browsing, and selling of NFTs. As an indexer, The Graph protocol stores information on the blockchain in a decentralized, transparent, and immutable way. In this case, the chain being utilized is the Goerli Testnet. Furthermore, the Kennel Club NFT Marketplace uses GraphQL, a query language to pull information that has been stored on chain, when needed. 
<br><br>
## Tech Stack
- TypeScript for primary language
- The Graph protocol for indexing
- GraphQL for querying
<br><br>
## Use
1. Follow the steps [here](https://github.com/StroupZ/Kennel-Club-Backend) for initializing the backend.
2. Follow the steps [here](https://github.com/StroupZ/Kennel-Club) for initializing the frontend.
3. Clone this repo.
4. Run `yarn add` to install all dependencies.
5. Add the ABI for your marketplace contract in the `abis` folder.
6. Add the address for your marketplace to `networks.json`.
7. In `networks.json` and `subgraph.yaml` make sure the startBlock is set to one block before the block your marketplace was deployed (can be viewed in Etherscan).
8. Create a subgraph for your marketplace [here.](https://thegraph.com/)
9. Run `graph init --studio YOUR_SUBGRAPH_NAME` to initialize your subgraph.
10. Run `graph codegen && graph build` to build your subgraph.
11. Run `graph deploy --studio YOUR_SUBGRAPH_NAME` to deploy your subgraph.
<br><br>
## Faucet
- [Goerli ETH](https://goerlifaucet.com/)
