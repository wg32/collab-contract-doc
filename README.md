# collab-contract-doc

Documentation for the collaborative revenue sharing feature proposed for Hic Et Nunc (HEN) as part of 2021's #hicathon.

## MVP components

### 1. Collab proxy smartcontract
URL: https://github.com/ztepler/hic-contract-proxy

This smart-contract defines collaborators and their relative share for reward sharing. Currently any amount of XTZ received by the smartcontract will be automatically re-distributed by its collaborators according to their relative share.


See the Wiki for further (not yet) detailed documentation.

### 2. HEN UI with collab MVP UI
URL: https://github.com/ztepler/hicetnunc

This UI fork allows the picking of an existing collab contract when minting an OBJKT, making the contract the de-facto NFT creator. Hence any revenues received by the creator contract will be distributed amongst the collaborators, including future second-market royalties.


![splash](images/hen-collab-splash.png)

