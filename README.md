# build-erc20-token-and-launch-ico
Build ERC20 Token and Launch a Token Sale

The goal of this exercise is to build your own Ethereum-based ERC20 token and start a token sale campaign (ICO).
The code of token will be written in Solidity. Before we get started, you must have installed MetaMask. Throughout this project, we will use Ropsten TestNet. 
These exercise is based on projects: https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793 and https://hashnode.com/post/how-to-build-your-own-ethereum-based-erc20-token-and-launch-an-ico-in-next-20-minutes-cjbcpwzec01c93awtbij90uzn. Thanks to the original authors.
You will need MetaMask installed.
1.	Understand the Code
Open your favorite code editor or use Remix directly and paste the parts of the following code in one file with name for example: TokenCode.sol. The idea is to build a simple ERC20 token. For example, we will name our token BlockchainDevCoin (BDC). 
1.	First, is the contract Token which contains the necessary elements of standard ERC20 token. ERC-20 came about as an attempt to provide a common set of features and interfaces for token contracts in Ethereum, and has proved to be very successful. ERC-20 has many benefits, including allowing wallets to provide token balances for hundreds of different tokens and creating a means for exchanges to list more tokens by providing nothing more than the address of the token’s contract. Most of the major tokens on the Ethereum blockchain are ERC20-compliant. This contract is fundamental and will be inherited by the next contracts. Carefully read the comments and understand the code logic.
