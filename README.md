# FunKart
## Problem Statement
Current warranty systems rely mostly on papers and thus management of the same is poor and results in poor customer experience, while also creating hassles for the organization issuing warranties. Also, the management of warranty-related data like the history of claims is a tedious process. Even though some organizations use centralized systems to address these problems, they are not always reliable due to issues pertaining to authenticity and security. 

Hence, there is a need for a Blockchain-based E-Commerce Warranty System to cater to all of these issues. The blockchain smart contract should allow users to prove ownership and provide the purchasing history, warranty period, and other item information.

## Project Overview
The basic process of registering for the warranty itself is cumbersome for today’s customers. It's a laborious process that relies on paper. For this very reason, customers frequently cancel their Warranty registrations. When the customer later discovers that a warranty is necessary, he won't know how to file a warranty claim effectively. 78\% of customers have backed out of purchase due to a negative customer experience.

Some of the difficulties that organizations experience are chances for them to demonstrate their abilities. How can customer issues be monitored? How can you tell the persistent problems apart from the others? Therefore, it is necessary to store historical data.

Data is collected from and stored on various platforms and is attributed to various sources. This results in a high number of touches, slowing the process and increasing the possibility of errors.

Blockchain technology is being used in the industry to replace middlemen with smart contracts. All parties involved have access to the contract as a code. It is an automated computerized protocol used to avoid middlemen and directly validate a contract over a decentralized platform in order to digitally facilitate, verify, or enforce the negotiation or performance of a legal contract.

Smart Contracts are distributed and immutable. It can be used to exchange money, property, shares, or anything of value in a transparent, conflict-free manner without the need for a third party. In our case, we use smart contracts to define the rules for the transfer of digital assets, which happen to be Warranty NFTs (Tokens).
As a result, Blockchain-based E-commerce warranty systems based on NFTs will allow users to prove ownership, store historical data and warranty period along with other item information in a tamper-proof, trusted, and consistent manner that will be simple to verify.

## Objective

The objective is to replace the physical warranty and have block chain based warranty using NFT which will ensure authenticity and security.

* Converting ownership authenticity and product warranty cards into decaying NFTs.
* For instance, allow brands and retailers to introduce an NFT for each of their products, which allows customers to receive the physical product along with a digital version of it.
* Customers can then use the digital NFT to verify the authenticity of their product, prove their ownership of their product, and transfer ownership of them upon resale.
* The brand/retailer should also be able to tie the digital NFT to its warranty program, allowing owners to track repairs and replacements to the original item.
* Decay the NFT once the warranty is over.

## Feature Mapping

* Ownership: The NFT Smart Contract implemented takes care of ownership of a token (Warranty)
* Claim History: The NFT Smart Contracts consist of a mapping from tokenID to a list of historical records associated with it.
* Item Data: The NFTSmart Contract maps the tokenID to the actual itemID or serial number and therefore, one can conveniently get the same.
* Expiry Date: Each token structure stores the expiration date of a Warranty. If someone tries to claim a warranty post this date, it will not be considered. Apart from that, the token is flagged invalid and burnt.

## Goals Accomplished
* The entire smart contract for Warranty NFTs is implemented, including the ability to store claim history, burning of NFTs, fetching user warranties, etc.
* A simple user interface is developed using NextJS which demonstrates warranty ownership on the purchase of an item, warranty information, and Web3 wallet integration.
* The relevant information about a warranty is stored in IPFS using Infura Blockchain APIs.

## Limitations
* The current implementation of the smart contract consists of limited data that is sufficient for the implementation of the system and efficient working. More data may be stored on the smart contract based on requirements.
* The project is currently implemented locally and is yet to be deployed on a public blockchain.
* The system is currently integrated with a custom E-Commerce site. Although the blockchain code is independent of the frontend, more variations may require testing.

## Future Plans
* Use REST API based approach instead of the modular approach.
* Full-fledged E-Commerce Integration.
* Email and SMS notifications with Warranty NFT Details.
* UI for managing Warranty Claim History.
* UI for burning NFTs in case of return of product or invalidating under specific warranty claims.
* Gamification or other forms of engagement.

## Contributors
This project is developed by [Umang Thadani](https://github.com/thadaniumang/ "Umang Thadani"), [Sahil Changlani](https://github.com/sahilchanglani/ "Sahil Changlani") and [Anurag Singh](https://github.com/heyanurag/ "Anurag Singh") from K. J. Somaiya College of Engineering, Mumbai for Flipkart Grid 4.0.
