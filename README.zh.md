# SChain - Get Started

SChain 是一個區塊鍊應用程式平台。

只要幾個步驟，你的應用程式就能被佈署到一個全拖管的 SChain 區塊鍊網路中。

# 1. 創建你的第一個應用程式

### 造訪 SChain 開發者中心

你可以在 [SChain 開發者中心](http://ec2-13-231-26-144.ap-northeast-1.compute.amazonaws.com/app) 管理你的應用程式。

### 創建一個應用程式

1. 在開發者中心儀表板，點選 **建立新 App** 按鈕。
2. 在對話框中輸入 **我的應用程式** 作為應用程式名稱。
3. 點選 **Create** 按鈕。

只要幾秒鐘的時間，你的應用程式就會被創建完成。一旦創建完成，你可以在儀表板上看到一個新的應用程式區塊。

### APP ID

檢視你的應用程式區塊，其中顯示了一段 ID 序列號，看起來像是 **app-9656e5a8-cff5-4629-93a2-a066e7c9aff7**。

此序列號為應用程式的唯一識別碼，當使用 SDK 存取 Chaincode 時需要此唯一識別碼。

### API KEY

在開發者中心的開發者資訊頁面中，你可以找到一段 API Key 序列號。

此序列號為開發者帳號的唯一識別碼，當使用 SDK 存取 Chaincode 時需要此唯一識別碼。

# 2. 部屬 Chaincode

區塊鍊應用程式通常會將其核心代碼運行在區塊鍊網路中，以區塊鍊來保護核心代碼所存取的帳本資料。

開發者可將撰寫完成的 Chaincode 代碼上傳到 SChain 開發者中心。SChain 會將 Chaincode 代碼部屬到一個全拖管的區塊鍊網路中。目前，SChain 支援 [Hyperledger Fabric](https://www.hyperledger.org/projects/fabric) 的 Chaincode 格式。

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

We also implemented a [NodeJS wallet](https://github.com/issbgkh/schain-wallet) that demonstrates using SDK to interact with the ICO chaincode.