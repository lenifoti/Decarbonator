# Decarbonator
A website and contract for removing the carbon footprint of NFTs minted (and transferred) before the merge.
## Components
### Website:
hosted on IPFS using TBD
uses indexing service for: Account NFTs & ERC20s, and Block/transaction info using TBD
### Decarbonator NFT: 
- Using OpenZeppelin template.
- Acts as a Decarbonation Wrapper for the original NFT.
- Calculates the Carbon foot print based on: NFT mint block, transactions, hashrates, energy factor.
- Calculates price to pay in ETH using DEX tbd.
- Decarbonates NFT by: 
Minting Decarbonation wrapper instance, setting metadata using original NFT, exchanging the input tokens to Klima using TBD, writing a love letter to the Planet using the KlimaDAO contract.
