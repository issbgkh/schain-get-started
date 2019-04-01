# SChain - Get Started

SChain is a blockchain application platform.

With SChain, your apps can be easily deployed onto a fully managed blockchain network.

# 1. Create your first app

### Visit the Developer Console

The [Developer Console](http://ec2-13-231-26-144.ap-northeast-1.compute.amazonaws.com/app) is a web-based tool that helps you manage your apps.

### Create your first app

1. On the console dashboard, click the **建立新 App** button.
2. In the popup window, type **My First App** as the app name.
3. Click the **Create** button.

Your app will be created in a few seconds. Once everything is done, a new app block will appear on the dashboard.

### APP ID

Look into the app block, there is an ID similar to **app-9656e5a8-cff5-4629-93a2-a066e7c9aff7**.

It's the unique identifier of your app. It is required when using SDK to access your chaincode.

### API KEY

On the profile page, you can find an API key.

It's the unique identifier of your developer account. It is required when using SDK to access your chaincode.

# 2. Deploy a Chaincode

The core functions of a blockchain app are typically executed on a blockchain network.

Developers can upload their chaincode onto the SChain, the uploaded chaincode then start working on a fully managed blockchain network.

Currently, the SChain supports core functions written in Hyperledger Fabric chaincode format.

### The simple store chaincode template

[Simple store template](https://github.com/issbgkh/simple-store) is the most basic chaincode example.

With its **set**, **get** and **delete** functions, you can manage a set of key-value pairs on the SChain.

### Deploy a chaincode

1. On the console dashboard, click **智能合約設定** inside the app block.

2. In the popup window, select **資料儲存樣板**.

3. Click **設定**.

A simple store chaincode will then be deployed onto the SChain.

# 3. SDK

The SChain provides [Javascript SDK](https://github.com/issbgkh/schain-sdk) so developers can write Javascript apps to access their deployed chaincode.

# More resources

### ICO chaincode

[schain-ico](https://github.com/issbgkh/schain-ico) is another chaincode example that provides ERC20 ICO interfaces.

### ICO Wallet App

We've also provided a [NodeJS wallet](https://github.com/issbgkh/schain-wallet) implementation to interact with the ICO chaincode.
