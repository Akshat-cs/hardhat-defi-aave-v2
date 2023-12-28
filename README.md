Programmatically depositing ETH, then borrowing DAI and then repaying the loan DAI on the forked Ethereum mainnet.
To run the project:
1) `yarn install`
2) Change the `.env.example` file to `.env` and then fill the `.env` file
3) Run `yarn hardhat compile`
4) Run `yarn hardhat run script/aaveBorrow.js --network hardhat`
