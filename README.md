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

# 2. 部屬 Chaincode 代碼

區塊鍊應用程式通常會將其核心代碼運行在區塊鍊網路中，以區塊鍊來保護核心代碼所存取的帳本資料。

開發者可將撰寫完成的 Chaincode 代碼上傳到 SChain 開發者中心。SChain 會將 Chaincode 代碼部屬到一個全拖管的區塊鍊網路中。目前，SChain 支援 [Hyperledger Fabric](https://www.hyperledger.org/projects/fabric) 的 Chaincode 格式。

### 資料儲存樣板

[資料儲存樣板](https://github.com/issbgkh/simple-store) 是最簡單的 Chaincode 代碼範例。

其中定義了 **set**, **get** 和 **delete** 函數，讓開發者可以在分散式帳本中管理多個 key-value 鍵值組。

### 部署 Chaincode 代碼

1. 造訪開發者中心儀表板，在應用程式區塊中點選 **智能合約設定** 按鈕。
2. 在對話框中選擇 **資料儲存樣板** (你也可以上傳自行撰寫的 Chaincode 代碼)。
3. 點選 **設定** 按鈕。

SChain 會為你在區塊鍊網路中部署一個資料儲存樣板的 Chaincode 代碼。

# 3. SDK

SChain 提供了 [Javascript 版本的 SDK](https://github.com/issbgkh/schain-sdk)。

開發者可使用 SDK 來存取區塊鍊中的 Chaincode 代碼。

# 其他資源

### ICO Chaincode

[schain-ico](https://github.com/issbgkh/schain-ico) 是另一個 Chaincode 代碼範例，其中我們展示了 [ERC-20](https://en.wikipedia.org/wiki/ERC-20) 的介面函數的實作。

### ICO 錢包應用程式

我們也提供了一個 [ICO 錢包](https://github.com/issbgkh/schain-wallet) 應用程式，其代碼展示了與 ICO Chaincode 函數互動的方法。
