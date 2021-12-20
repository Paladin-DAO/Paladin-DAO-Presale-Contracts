# Paladin-DAO-Presale-Contracts

The contracts are written by industry experts who has knowledge on the best practices in blockchain development.

![This is an image](https://miro.medium.com/max/1400/1*pG2kVdA8V4eLLPXJzDqn-g.png)

## Launch Phases

### Phase 1 :
**Whitelisted Presale**: This phase will provide the purchase access to the Whitelisted Members (whitelist Role) in this Discord and this phase is launched on BSC Networks, and the $Paladins tokens can be bought using $BUSD on BSC Network. $Paladins Token price at this phase will be $10 per token. Each whitelisted member can purchase a maximum of 100 $Paladins Tokens ($1000).

### Phase 2 : 
**Public Presale**: This phase will exist only if the Whitelisted Presale didn’t achieve the target fundraising goal ($700,000). The tokens and chains at this phase will be the same as Phase 1. $Paladins Token price at this phase will be $16 per token.

### Phase 3 : 
**Public Launch**: This is the major Public Launch of Staking, Bonding Pancake Swap. Staking will have a huge Initial APY to incentivize the early Stakers, and Bonding will have huge discounts initially to incentivize early Bonders. We’ll make use of Bridging Protocols to equalize the price of tokens between different chains. The users who bought $Paladin at Phase 1 or Phase 2 can claim their tokens for $Paladin at this phase.

## Gnosis Multisign Wallet

### Gnosis Proxy
![This is an image](https://i.stack.imgur.com/THTlh.png)

### Gnosis Multisgn Process
![This is an image](https://miro.medium.com/max/765/1*OymI4OIm23KYTXwrUwJFeA.png)

The Safe is a smart contract wallet with multi-signature functionality at its core. It enables the following features:

## High Security
Safe's multi-signature functionality allows you to define a list of owner accounts and a threshold number of accounts required to confirm a transaction. Once the threshold of owner accounts have confirmed a transaction, the Safe transaction can be executed. Owners can either be EOAs or other smart contract accounts.

## Advanced execution logic
It is possible to make use of different Safe Library contracts to perform complex transactions. A very common example of this is batched transactions where multiple simple Ethereum transactions are combined and executed at once. That means instead of having to sign several transactions sequentially, a user just needs to sign one batched transaction.

## Advanced access management
You can add Safe Modules to your Safe. Thereby it is possible to implement more fine-grained access management. For instance, it is possible to define a module that can only be used to recover access to a Safe under specific circumstances. A popular version of this is the Social Recovery Module. A different example is allowance modules that allow owners of a Safe to grant limited execution permission, such as a daily limit to external accounts.

## Token callback support
Many new tokens require wallet contracts to implement callbacks. Token standards like ERC721 and ERC1155 allow contracts to immediately react to receiving tokens through these and make it even possible to reject the transfer completely.

## Ether-less accounts
Another core functionality of the Safe is token payment. Generally, Ethereum transactions require ETH for paying transaction fees (“gas”). With the Safe, users can pay transaction fees in a number of supported ERC20 tokens. This is realized via a transaction relay service that accepts those tokens and submits the transactions to the blockchain, therefore paying the gas fee in ETH. With the same functionality, Ether-less transactions can be implemented, where a 3rd party pays transaction fees on behalf of a Gnosis Safe via the same relay service.
