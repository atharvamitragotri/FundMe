# FundMe
Using the brownie framework to deploy a smart contract that lets anyone deposit ETH into this contract.
Only the owner can withdraw the ETH from the contract.
Uses the AggregatorV3Interface from Chainlink to get the ETH/USD price feed for the required network.
We also deploy a AggregatorV3Interface mock to use with the mainnet-fork locally.
