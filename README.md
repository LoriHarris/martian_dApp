# Martian Market Decentralized Application
### Note: Must connect to MetaMask Ropsten network to use

Application can be found [here](https://www.dataplayconsulting.com/martian_dApp/).

This system is a combination of an ERC721 contract and an Auction contract combined to form the MartianMarket contract, designed for the 
fictional _Martian Development Foundation_. They want a system that raises funds for Martian land development.

With this contract, the foundation will be able to register new landmarks with their account, minting and creating a new auction for the landmark.
When the `endAuction` function is called, the auction will complete and the token will be transferred to the highest bidder.

The functions of the contract can be designed to have the foundation pay for the most expensive functions like`safeTransferFrom`.
This can be done by putting the token transfer in the `endAuction` function that only the foundation can call.

Each landmark is a unique ERC721 token, with its own metadata including the landmark `name` and `image` URL.

