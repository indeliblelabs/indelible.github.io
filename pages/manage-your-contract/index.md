---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Manage Your Contract
description: Interact with your contract to manage different aspects of your minting process and more.

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Deploying
        url: '/pages/deploying'
---

# Overview

Your contract deployed successfully! After this happens, there are some crucial things you need to manage in your contract in order for the world to start minting your tokens.

For quick reference, here are the interactions you need to do with your contract before anyone can mint:

- Upload all layers.
- If you declared any "Link traits", upload the link traits.
- If you enabled “Allow list” for your contract, you must upload the "Allow list" to your contract.
- Toggle the desired minting option.

# Uploading the layers

After the deployment is successful, you will immediately be taken to the specific page to manage your contract and be presented with the ability to upload your layers to your contract that is now in the Ethereum blockchain. Prior to proceeding, it is essential to finish the upload of your layers. No other actions can be taken until this upload is completed. To manage heavy transactions and avoid uploading too much data into the Ethereum blockchain all at once, your art is not immediately uploaded to the contract upon deployment.

What you will see right after succesfully deploying is the following:

![upload-layers.png](./assets/upload-layers.png)

At this stage, you should click on the "Upload To Contract" button for each individual layer, thereby effectively writing all the traits for that layer into your contract. Once all uploads are successfully completed, your art will be fully on-chain.

# General Management

Indelible Labs provides a user-friendly interface that simpliefies contract management. Let's look at the possible interactions available to you.

After all your layers have been uploaded, you'll gain access to the following options for managing your contract:

![general-manage-contract.png](./assets/general-manage-contract.png)

## Upload Linked Traits

If you used the "Linked trait" feature on any of the traits in your collection, you **MUST** click and upload your linked traits to the smart contract **prior** to any minting if you do not want undesired outcomes on the art.

## Upload Allow List

Use this button to upload your list. Currently the allow list does not automatically upload along with the contract. Therefore, you must interact with this feature to enable those wallets on the allow list to perform minting.

## Enable/Disable Allow List Mint

After uploading your allow list to your contract, you can click this button to enable minting for the allowed wallets. If needed, you can disable it later to close access again. 

## Enable/Disable Public Mint

Toggle this to open minting to anyone.

## Allow List Price

Controls the allow list price per token to be minted.

## Allow List Max Per Address

This section controls the max amount of tokens a single allow list address can mint.

## Mint

This features allows you to exclusively mint from the contract. There are several reasons you might want to choose this option, such as airdropping, minting the first N number of tokens, or simply seeing your art on the mainnet first.

## Withdraw

For any collection that earns ETH on mint, you can trigger the withdraw method with this button to collect your share from the contract’s available balance at any given time.

## Enable Off-Chain Rendering

Toggle this on to let token owners eneable off-chain rendering for their particular token. 

Presently, Indelible Labs offers free hosting for the images of your collection if it is desired. Note that this is subject to change.

If this feature is enabled by the owner of the token, you contract is designed to offer either the on-chain image or an off-chain URL through the `tokenURI` method. The primary purpose of enabling this feature, at this current time, is to allow the display of the NFT in Twitter PFP. 

## Verify

Upon deployment, the process of contract verification is automated. However, but due to our integration with various external services and APIs, successful verification is not guaranteed.

In such cases, you can try verifying it again here. To check if your contract is verified by Etherscan, visit your contract on their platform and click on the contract tab. If your contract is **NOT** verified, you should see this statuts.

![etherscan-unverified.png](./assets/etherscan-unverified.png)