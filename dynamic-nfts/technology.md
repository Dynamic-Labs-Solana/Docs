---
description: Dynamic NFT; the underlying technology
---

# Technology

The ability to create dynamic NFTs is our bread and butter. It is a new way of creating NFTs so that the underlying metadata and even the visual representation can be modified after the NFT has been created.

> An NFT that is dynamically mutable, meaning its underlying information and appearance can change based on outside influences and triggers.



In order to accomplish this we built upon the well established Metaplex Candy Machine, making two major upgrades to allow for dynamic NFTs.



1. The appearance of the NFT will be based on an HTML file instead of a PNG file.
2. Changeable Metadata will be stored with Aleph instead of Arweave



### Ad 1. HTML based NFTs

Because a PNG file is always static and cannot change in appearance, we had to adapt and use the HTML file format. An HTML file can look up the current metadata and render the correct image for the current state.

The most simple application for this is a trait swap utility...

### Ad 2. Aleph.im for dynamic metadata&#x20;

The metadata of an NFT is not stored on-chain but as a separate JSON file on Arweave. The on-chain NFT simply references the external data. Even though we could technically update the reference to a different metadata file, it is not at all efficient since we would need to upload a new file to the Arweave Network; this can become very costly.

Instead we are using Aleph.Im which is a fully decentralized database that allows us to alter single fields of information and store dynamic data very efficiently.



## The future of Dynamic NFTs

NFTs in general are still in its infancy stage. Only with continued development we’ll be able to fully tap into the power of NFTs with dynamic functionalities. At the current moment we are still limited by how we store an NFT’s data effectively and most importantly fully decentralized.

While Aleph offers a good way it still has its flaws and we are permanently exploring other ways and keeping our eyes open for what’s to come. One thing we are especially excited about is the SHDW Network by GenesisGo who are building raw fast storage directly into the Solana L1 itself.
