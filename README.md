# schain-get-started

SChain is a blockchain application platform.

With SChain, your apps can be easily deployed on a fully managed blockchain network.

# 1. Create your first app

### Visit the Developer Console

The [Developer Console](http://ec2-13-231-26-144.ap-northeast-1.compute.amazonaws.com/app) is a web-based tool that helps you manage your apps.

### Create your first app

1. On the console dashboard, click the **Create App** button.
2. In the popup window, type **My First App** in the app name field.
3. Click the **Create** button.

Your app will be created in just a few seconds. Once everything is done, a new app block appears on the dashboard.

### APP ID

Look into the app block, there is an ID similar to **app-9656e5a8-cff5-4629-93a2-a066e7c9aff7**.

It's the unique identifier of your app. It is required when you use SDK to access your chaincode.

### API KEY

On the profile page, you can find an API key.

It's the unique identifier of your developer account. It is also required when you use SDK to access your chaincode.

# Deploy a Chaincode

The core functions of a blockchain app are typically executed on a blockchain network.

Developers can upload their chaincode onto SChain, the uploaded chaincode then start working on a fully managed blockchain network.

Currently, SChain supports core functions written in Hyperledger Fabric chaincode format.

### The simple store chaincode template

[Simple store template](https://github.com/issbgkh/simple-store) is the most basic chaincode.

With its **set**, **get** and **delete** functions, you can manage a set of key-value pairs in the SChain.

### The sample ICO chaincode

We've implemented an ERC20-like chaincode, you can simply download [here](https://github.com/issbgkh/schain-ico).

### Deploy the chaincode

1. On the developer console, click the **Upload Contract** button inside the app block.

2. In the popup window, click the **Select file** button, and select **chaincode.zip** in the sample chaincode directory.

3. Clear all arguments.

4. Add one argument **admin**, it is the coinbase account.

5. Click the **Update** button.

6. The chaincode will be deployed to SChain in just a few seconds. It's super easy, isn't it?

# Wallet

We've also provided a [NodeJS wallet](https://github.com/issbgkh/schain-wallet) implementation to interact with the just deployed ICO chaincode.
