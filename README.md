# schain-get-started

SChain is a blockchain application platform.

With SChain, your apps can be easily deployed on a fully managed blockchain network.

We will show you how to deploy a sample ICO wallet app below.

# Developer console

You can manage your apps on the [developer console](http://ec2-13-231-26-144.ap-northeast-1.compute.amazonaws.com/).

## Create your first app

1. On the dashboard, click the **Create App** button.
2. In the popup window, type **ICO** in the app name field.
3. Click the **Create** button.

Your app will be created in just a few seconds. Once done, you can find a new app block on the dashboard.

## App ID

Look into the app block, there is an ID similar to **app-9656e5a8-cff5-4629-93a2-a066e7c9aff7**.

It's the unique identifier of your app, which you will need later.

## API Key

On the profile page, you can find an API key.

It's the unique idetifier of your developer account, which you will need later also.

# Chaincode

The core functions of a blockchain app are typically executed on a blockchain network.

SChain supports core functions written in Hyperledger Fabric chaincode format.

## The sample ICO chaincode

We've implemented an ERC20-like chaincode, you can simply download [here](https://github.com/issbgkh/schain-ico).

## Deploy the chaincode

1. On the developer console, click the **Upload Contract** button inside the app block.

2. In the popup window, click the **Select file** button, and select **chaincode.zip** in the sample chaincode directory.

3. Clear all arguments.

4. Add one argument **admin**, it is the coinbase account.

5. Click the **Update** button.

6. The chaincode will be deployed to SChain in just a few seconds. It's super easy, isn't it?

# Wallet

We've also provided a [NodeJS wallet](https://github.com/issbgkh/schain-wallet) implementation to interact with the just deployed ICO chaincode.
