# MrsBlackhornNFT – ERC721 Token Demo

![Mrs. Blackhorn's First Mint][def]

> **Name:** Mrs. Blackhorn's First Mint  
> **Description:** The official ERC721 token from the Crypto Conversation Starter series.  
> **Edition:** Genesis  
> **Origin:** Crypto Conversation Starter  
> **Metadata URL:** [View JSON Metadata](https://green-capitalist-bovid-159.mypinata.cloud/ipfs/bafybeihluqfczg3jue3mcs5xmzqwxf3nxlumqpp3s4onfef5revo6vtnkq)

This is a live example of an ERC721 token created by Mrs. Blackhorn from the Crypto Conversation Starter series.

## Contract Features

- Built on OpenZeppelin’s `ERC721URIStorage`
- Owner-only minting
- Metadata hosted on IPFS
- Fully compatible with platforms like OpenSea and third-party marketplaces

## How to Deploy This Contract

1. Open [Remix IDE](https://remix.ethereum.org)
2. Paste the contents of `MrsBlackhornNFT.sol` into a new file
3. Compile the contract using Solidity 0.8.x
4. Deploy using **Remix VM (Cancun)** or MetaMask on Sepolia
5. Call `createNFT()` with your metadata URL

## Sample Metadata

```json
{
  "name": "Mrs. Blackhorn's First Mint",
  "description": "The official ERC721 token from the Crypto Conversation Starter series.",
  "image": "https://green-capitalist-bovid-159.mypinata.cloud/ipfs/bafybeihluqfczg3jue3mcs5xmzqwxf3nxlumqpp3s4onfef5revo6vtnkq",
  "attributes": [
    {
      "trait_type": "Origin",
      "value": "Crypto Conversation Starter"
    },
    {
      "trait_type": "Edition",
      "value": "Genesis"
    }
  ]
}
