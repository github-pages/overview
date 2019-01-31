---


copyright:
  years: 2016, 2019
lastupdated: "2019-01-02"


---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.cloud_notm}} 的名詞解釋
{: #glossary}

本名詞解釋提供 {{site.data.keyword.cloud_notm}} 的術語和定義。
{:shortdesc}

本名詞解釋使用下列交互參照：

- *請參閱* 可讓您從非偏好的術語參照到偏好的術語，或從縮寫參照到拼出的格式。
- *另請參閱* 可讓您參照相關或對照術語。

<!--If you do not want letter links at the top of your
glossary, delete the text between these comment tags.
[A](#glossa)
[B](#glossb)
[C](#glossc)
[D](#glossd)
[E](#glosse)
[F](#glossf)
[G](#glossg)
[H](#glossh)
[I](#glossi)
[J](#glossj)
[L](#glossl)
[M](#glossm)
[N](#glossn)
[O](#glosso)
[P](#glossp)
[R](#glossr)
[S](#glosss)
[T](#glosst)
[U](#glossu)
[V](#glossv)
[W](#glossw)

-->

[二劃](#glossa)
---
---
### 入門範本 (starter)
{: #x7470511}

一種範本，其中包含預先定義的服務，以及利用特定建置套件進行配置的應用程式碼。入門範本可以是用特定程式設計語言撰寫的應用程式碼，也可以是應用程式碼和一組服務的組合。另請參閱[運行環境 (runtime)](#x2391929)。

[三劃](#glossa)
---
---
### 子網域 (subdomain)
{: #x2040080}

構成更大網域一部分的網域。另請參閱[自訂網域 (custom domain)](#x5728384)、[網域 (domain)](#x2021210)、[主機 (host)](#x2002243)、[路徑 (route)](#x2037338)、[統一資源定位器 (Uniform Resource Locator)](#x2042491)。

### 子網路 (subnet)
{: #x4282974}

請參閱[子網路 (subnetwork, subnet)](#x2040149)。

### 子網路 (subnetwork, subnet)
{: #x2040149}

分成較小獨立子群組的網路，彼此之間仍然交互連接。

### 工作區 (workspace)
{: #x2096037}

一種環境定義，其中包含具有適當權限的使用者可以修改的構件集合。

[四劃](#glossa)
---
---
### 中繼憑證 (intermediate certificate)
{: #x3753781}

由授信主要憑證管理中心 (CA) 發出的子層憑證，專門用於發出持卡實體伺服器憑證。結果會形成一條憑證鏈，從授信主要憑證管理中心開始、通過中繼憑證，最後以發給組織的 SSL 憑證結束。另請參閱[憑證管理中心 (certificate authority)](#x2016383)、[授信主要憑證 (trusted root)](#x2042234)。

### 元件 (component)
{: #x2017871}

在原始檔控制管理中，是指串流或儲存庫工作區中的一組相關構件。一個元件可以包含任意數量的資料夾和檔案。

### 內部部署 (on-prem)
{: #x6969434}

請參閱[內部部署 (on-premises, on-prem)](#x4561212)。

### 內部部署 (on-premises, on-prem)
{: #x4561212}

與在使用者或組織的本端電腦上安裝並執行的軟體有關。

### 公用雲端 (public cloud)
{: #x4585370}

一種雲端運算環境，其中可根據每次使用付款來訂閱標準化資源（例如基礎架構、多方承租戶硬體及服務）的存取權。另請參閱[無界限 (borderless)](#x8439189)、[專用雲端 (private cloud)](#x4585362)。

### 公用資源 (public resource)
{: #x9439040}

IBM Cloud 型錄中每個人都能看到的項目。公用資源可由任何提供者（IBM 或協力廠商提供者）建置。另請參閱[專用資源 (private resource)](#x9439035)。

### 公用閘道 (public gateway)
{: #x9594389}

子網路對網際網路的連線，並已連接所有虛擬伺服器實例。公用閘道使用多對一的網址轉換 (NAT)，這表示數以千計具有專用位址的虛擬伺服器實例，可以使用一個公用 IP 位址與公用網際網路通訊。

### 反親緣性 (anti-affinity)
{: #x8888040}

在不同網路節點上執行的兩個以上容器群組實例，以確保應用程式具有較高可用性。另請參閱[親緣性 (affinity)](#x2149238)。

[五劃](#glossa)
---
---
### 主映像檔 (parent image)
{: #x8439210}

提供另一個映像檔基礎的映像檔。例如，Ubuntu Linux 是 IBM Liberty 映像檔的母項映像檔。另請參閱[基礎映像檔 (base image)](#x5366487)、[映像檔 (image)](#x2024928)。

### 主要讀取 (read-mostly)
{: #x7470468}

與動態變更的資料有關。

### 主機 (host)
{: #x2002243}

連上網路並為該網路提供存取點的電腦。主機可以是用戶端、伺服器或同時為這兩者。另請參閱[用戶端 (client)](#x2000644)、[自訂網域 (custom domain)](#x5728384)、[網域 (domain)](#x2021210)、[路徑 (route)](#x2037338)、[子網域 (subdomain)](#x2040080)、[統一資源定位器 (Uniform Resource Locator)](#x2042491)。

### 可用性區域 (availability zone)
{: #x7018171}

地區內 IBM Containers 在其中執行的位置。


### 平台即服務 (platform as a service, PaaS)
{: #x2029786}

在以雲端為基礎的環境中提供運算平台，包括應用程式、最佳化的中介軟體、開發工具以及 Java 和 Web 2.0 運行環境。

### 本端雲端 (local cloud)
{: #x8439194}

用戶端資料中心內的雲端運算環境。本端雲端是內部部署的，並提供改良的延遲及安全。另請參閱[無界限 (borderless)](#x8439189)。


### 用戶端 (client)
{: #x2000644}

向伺服器要求服務的軟體程式或電腦。另請參閱[主機 (host)](#x2002243)。

[六劃](#glossa)
---
---
### 名稱空間 (namespace)
{: #x2031005}

唯一名稱，可識別 IBM Cloud 登錄內貴組織的映像檔儲存庫。另請參閱[映像檔 (image)](#x2024928)、[專用映像檔儲存庫 (private image repository)](#x8439215)。

### 地區 (region)
{: #x2091391}

已定義的地理區域。地區可以是特定的郵遞區號區域、鄉鎮、縣/市、州/省、一組州/省，甚至是一組國家/地區。每一個地區本身可以是一組其他地區，或是一組形成地區的郵遞區號。

### 存取記號 (access token)
{: #x2113001}

消費者使用的值，用於代表使用者取得受保護資源的存取權，而不是利用使用者的服務提供者認證。

### 存取控制清單 (access control list)
{: #x2012793}

透過使用規則，以無狀態方式管理子網路入埠及出埠資料流量的清單。存取控制清單能協助提供子網路層次的安全。

### 自訂網域 (custom domain)
{: #x5728384}

使用者所選取 URL 中的自訂部分，可以將要求導向到應用程式。自訂網域會構成路徑的一部分。自訂網域可以是共用網域、共用子網域或共用網域與主機。另請參閱[網域 (domain)](#x2021210)、[主機 (host)](#x2002243)、[路徑 (route)](#x2037338)、[子網域 (subdomain)](#x2040080)、[統一資源定位器 (Uniform Resource Locator)](#x2042491)。


### 行動後端即服務 (mobile backend as a service, MBaaS)
{: #x7044858}

用於將行動應用程式連接到雲端運算服務的一種運算模型，該模型提供多種特性（例如，使用者管理、推送通知，以及透過統一的 API 和 SDK 與社交網路整合）。

### 行動雲 (mobile cloud)
{: #x4585344}

一種基礎架構，在其中儲存和處理應用程式資料將從行動裝置卸載移至雲端上。利用行動雲端運算，應用程式不再侷限於特定營運商，而是透過 Web 進行存取。


### 行動應用程式 (mobile app)
{: #x7636517}

請參閱[行動應用程式 (mobile application)](#x4258535)。

### 行動應用程式 (mobile application, mobile app)
{: #x4258535}

針對行動平台所設計的應用程式。與 Web 應用程式類似，行動應用程式除了靜態顯示資訊以外，還提供一些功能，例如，讓使用者即時過濾新聞。另請參閱[應用程式 (app)](#x4281528)。

[七劃](#glossa)
---
---
### 私密金鑰 (private key)
{: #x2034701}

一種用來加密訊息的演算型樣，只有對應的公開金鑰可以解密。另外，私密金鑰也用來將相對應公開金鑰所加密的訊息解密。私密金鑰保存在使用者系統上，受到密碼保護。

[八劃](#glossa)
---
---
### 使用者階層
{: #userhierarchy}

將其他使用者邀請加入帳戶的標準基礎架構使用者的使用者管理關係。然後，這些使用者會邀請其他使用者加入帳戶，依此類推。當標準基礎架構使用者邀請另一位使用者加入帳戶時，標準基礎架構使用者會變成母項使用者。當母項使用者的子項使用者邀請其他使用者加入該帳戶時，這些使用者會變成原始母項（現在被視為上代）的後代。


### 具象狀態傳輸 (Representational State Transfer, REST)
{: #x3220976}

分散式超媒體系統（如全球資訊網）的軟體架構樣式。這個術語通常也用來說明任何透過 HTTP 使用 XML（或 YAML、JSON、純文字），且沒有其他傳訊層（如 SOAP）的簡單介面。

### 協力廠商 (third-party)
{: #x2877945}

與由 IBM 以外的公司所提供的產品或服務有關。

### 呼叫 (invoke)
{: #x2057232}

啟動動作。另請參閱[動作 (action)](#x2012974)。

### 服務 (service)
{: #x2038343}

一種雲端延伸，用於提供資料庫、傳訊和 Web 軟體等現成功能以執行程式碼、應用程式管理或監視功能。服務通常不需要安裝或維護，並且可以透過結合來建立應用程式。

### 物聯網 (Internet of Things, IoT)
{: #x6714341}

可以擷取或產生資料之端點的全球網路。例如，智慧型手機、智慧型手錶及後端伺服器可能彼此通訊、來回傳送資料，甚至是傳送給網路內的其他裝置。

### 空間 (space)
{: #x2039442}

IBM Cloud 組織中的子群組。身為組織成員的使用者會被授與一個以上組織空間的存取權，以及與特定角色（例如，開發人員、管理員或審核員）相關聯的權限。空間的任何成員都可以檢視應用程式，但只有具有開發人員角色的成員才能建立應用程式，以及將服務實例新增至該空間。應用程式和服務實例與空間相關聯。另請參閱[組織 (organization)](#x2032585)。

[九劃](#glossa)
---
---
### 建置套件 (buildpack)
{: #x7233925}

Script 的集合，用於準備好程式碼以便在 IBM Cloud 上執行。建置套件會檢查已部署的應用程式，然後下載並配置所有相依應用程式。


### 指令行介面 (command-line interface, CLI)
{: #x2051424}

輸入及輸出皆以文字為基礎的電腦介面。

### 映像檔 (image)
{: #x2024928}

檔案系統及其執行參數，用來在容器運行環境內建立容器。檔案系統包含一系列的層，這些層在執行時結合，且會在連續更新建置映像檔時建立。映像檔不會在容器執行時保留狀態。另請參閱[基礎映像檔 (base image)](#x5366487)、[容器 (container)](#x2010901)、[層 (layer)](#x2028320)、[名稱空間 (namespace)](#x2031005)、[母項映像檔 (parent image)](#x8439210)、[專用映像檔儲存庫 (private image repository)](#x8439215)、[登錄 (registry)](#x2064940)。

### 架構 (framework)
{: #x2023472}

一種應用程式架構，用於提供應用程式及一般性可延伸功能的標準結構。架構能促成並簡化對於應用程式開發之複雜技術的一致性實作。


### 段落 (stanza)
{: #x2094743}

套裝軟體的一部分，用於定義要在該套裝軟體上執行的特定動作，或者在套裝軟體上執行動作時要符合的一組條件。整個套裝軟體也是一個段落，其中包含由許多不同段落組成的階層。

### 紅黑部署 (red-black deployment)
{: #x8439181}

一種部署技術，透過啟用同步化測試、開發及部署來推動持續交付。一開始，開發是在非作用中環境中進行（黑色），而作用中環境會持續取得資料流量（紅色）。部署啟動之後，在先前作用中舊版環境上停用遞送之前，兩個環境都會變成進行中（紅-紅），隨後予以移除（黑），而新的環境會作為唯一的作用中環境。另請參閱[藍綠部署 (blue-green deployment)](#x7807335)。

### 重量型 API 呼叫 (heavy API call)
{: #x7690468}

寫入、刪除或插入資料的用戶端作業。重量型 API 呼叫所耗用的資源高於輕量型 API 呼叫，因為它們會影響資料。另請參閱[輕量型 API 呼叫 (light API call)](#x7690463)。

[十劃](#glossa)
---
---
### 容器 (container)
{: #x2010901}

一種系統建構，容許使用者同步執行個別邏輯作業系統實例。容器使用檔案系統各層來最小化映像檔大小，並推動重複使用。另請參閱[映像檔 (image)](#x2024928)、[層 (layer)](#x2028320)、[登錄 (registry)](#x2064940)。

### 浮動 IP 位址 (floating IP address)
{: #x6326428}

公用且可路由的 IP 位址，它利用一對一的網址轉換 (NAT)，以便伺服器能與公用網際網路和雲端環境內的專用子網路通訊。浮動 IP 位址藉由虛擬網路介面卡 (vNIC) 與實例相關聯，例如虛擬伺服器實例、負載平衡器或 VPN 閘道。

### 記錄系統 (system of record, SOR)
{: #x6735061}

一種資訊儲存系統（例如，資料庫或應用程式），用於儲存商業記錄和自動執行標準處理程序。另請參閱[參與系統 (system of engagement)](#x6528306)。


[十一劃](#glossa)
---
---
### 動作 (action)
{: #x2012974}

可以明確地呼叫或因回應事件而執行的程式碼 Snippet。另請參閱[資訊來源 (feed)](#x3129185)、[呼叫 (invoke)](#x2057232)。

### 區域 (zone)
{: #x2070723}

獨立的錯誤網域。區域是一種抽象化，其設計是要藉由改善容錯及縮短延遲而提供協助。
### 參與系統 (system of engagement)
{: #x6528306}

一種資訊技術 (IT) 系統，其中包含多種技術，用於鼓勵使用者透過電子郵件、協同作業系統和網路進行互動。參與系統通常使用雲端技術來延伸記錄系統的實用性。另請參閱[記錄系統 (system of record)](#x6735061)。

### 基礎映像檔 (base image)
{: #x5366487}

沒有母項映像檔的映像檔。另請參閱[映像檔 (image)](#x2024928)、[母項映像檔 (parent image)](#x8439210)。

### 基礎架構即服務 (infrastructure as a service, IaaS)
{: #x4585332}

以外包服務的形式提供電腦基礎架構（包括伺服器功能、網路功能、資料中心功能及儲存空間功能）。

### 專用服務 (private service)
{: #x7690456}

只有所指定 IBM Cloud 組織的成員才能看到的服務。

### 專用映像檔儲存庫 (private image repository)
{: #x8439215}

組織的 IBM Cloud 登錄及其名稱空間的組合。在指令中參照映像檔時，會使用專用映像檔儲存庫。另請參閱[映像檔 (image)](#x2024928)、[名稱空間 (namespace)](#x2031005)。

### 專用雲端 (dedicated cloud)
{: #x8439199}

一種專用雲端運算環境，提供具有單一承租戶硬體的基礎架構。另請參閱[無界限 (borderless)](#x8439189)。

### 專用雲端 (private cloud)
{: #x4585362}

一種雲端運算環境，僅限由企業與合作夥伴網路的成員進行存取。另請參閱[公用雲端 (public cloud)](#x4585370)。

### 專用資源 (private resource)
{: #x9439035}

只有帳戶擁有者及其包含帳戶才能看到的項目。建立資源時，它們依預設是專用資源。另請參閱[公用資源 (public resource)](#x9439040)。

### 常駐程式 (daemon)
{: #x2019215}

這是會自動執行以執行連續或定期功能（如網路控制）的一種程式。

### 推送 (push)
{: #x2035465}

將資訊從伺服器傳送到用戶端。伺服器推送內容時，會由伺服器主動起始交易，而不是因為來自用戶端的要求而起始交易。

### 推送通知 (push notification)
{: #x5599582}

行動應用程式圖示上的警示，用於指示變更或更新。


### 授信主要憑證 (trusted root)
{: #x2042234}

由授信憑證管理中心 (CA) 簽署的憑證。另請參閱[憑證管理中心 (certificate authority)](#x2016383)、[中繼憑證 (intermediate certificate)](#x3753781)。


### 授權 (authorization, AuthZ)
{: #x2014653}

在電腦安全中，授與使用者和電腦系統通訊或利用電腦系統的權限。

### 混合式雲端 (hybrid cloud)
{: #x4585327}

包含多個公用及專用資源的雲端運算環境。

### 統一資源定址器 (Uniform Resource Locator, URL)
{: #x2042491}

可在網路（例如，網際網路）上存取之資訊資源的唯一位址。URL 包括用來存取資訊資源的通訊協定縮寫名稱，以及通訊協定用來尋找資訊資源的資訊。另請參閱[自訂網域 (custom domain)](#x5728384)、[網域 (domain)](#x2021210)、[主機 (host)](#x2002243)、[路徑 (route)](#x2037338)、[子網域 (subdomain)](#x2040080)。

### 統一資源識別碼 (Uniform Resource Identifier, URI)
{: #x2116436}

用來識別 Web 內容的唯一位址。URI 最常見的形式是網址，這是 URI 的一種特定形式或子集，稱為「統一資源定址器 (URL)」。一般而言，URI 會說明如何存取資源、含有該資源的電腦，以及該資源在該電腦上的位置。

### 組織 (org)
{: #x7470494}

請參閱[組織 (organization, org)](#x2032585)。

### 組織 (organization, org)
{: #x2032585}

這是指 IBM Cloud 中對使用者進行分組的方法。組織可用於管理配額。組織中的使用者會共用記憶體和服務實例配額。另請參閱[網域 (domain)](#x2021210)、[空間 (space)](#x2039442)。


### 規則 (rule)
{: #x2037526}

- 一個準則，可建立一個觸發程式與一個動作的關聯，而每次發動觸發程式都會呼叫將觸發程式事件作為輸入的對應動作。
- 一組條件式陳述式，可讓電腦系統能夠識別關係並相應地執行自動化回應。

### 軟體即服務 (software as a service, SaaS)
{: #x4585386}

一種軟體部署模型，其中軟體（包括商業處理程序、企業應用程式和協同作業工具）將以服務的形式透過雲端提供給客戶。

### 連結 (bind)
{: #x2000361}

使用經過協議的通訊協定，在網路上的軟體元件之間建立連線。在 Web 服務中，當服務要求者在執行時，透過使用服務說明中的連結詳細資料來尋找、聯絡和呼叫服務的方式，呼叫或起始與服務的互動時，就會進行連結作業。

### 部署 (deployment)
{: #x2104544}

一個處理程序，用於擷取建置輸出、包裝輸出（含配置內容），以及在預先定義的位置中安裝套件，以進行測試或執行。另請參閱[編譯打包 (stage)](#x2067189)。

[十二劃](#glossa)
---
---
### 單一登入 (single sign-on, SSO)
{: #x2213318}

一種鑑別處理程序，在該處理程序中，使用者可輸入單一使用者 ID 和密碼，來存取多個系統或應用程式。

### 測試版服務 (beta service)
{: #x7470455}

尚未準備好進入正式作業且目前處於開發試用階段的服務。另請參閱[實驗性服務 (experimental service)](#x7470450)。

### 無界限 (borderless)
{: #x8439189}

相關的開放式非專屬開發平台，其中包括公用雲端、專用雲端及本端雲端部署模型。另請參閱[專用雲端 (dedicated cloud)](#x8439199)、[本端雲端 (local cloud)](#x8439194)、[公用雲端 (public cloud)](#x4585370)。

### 登錄 (registry)
{: #x2064940}

公用或專用容器映像檔儲存及配送服務。另請參閱[容器 (container)](#x2010901)、[映像檔 (image)](#x2024928)。

### 發動 (fire)
{: #x2239904}

啟動觸發程式。

### 虛擬 (virtual)
{: #x2043123}

是指實體上不存在，而是由軟體造成看似存在。

### 虛擬伺服器 (virtual server)
{: #x2455638}

一部與其他伺服器共用資源以支援應用程式的伺服器。另請參閱[虛擬機器 (virtual machine)](#x2043165)。

### 虛擬私密網路 (virtual private network, VPN)
{: #x2043188}

這是企業內部網路透過現有公用或私密網路架構的延伸。VPN 可以確保在連線兩端點之間傳送的資料會保持安全。

### 虛擬機器 (virtual machine, VM)
{: #x2043165}

像實體機器一樣執行程式之機器的軟體實作。另請參閱[虛擬伺服器 (virtual server)](#x2455638)。

### 超文字傳送通訊協定安全 (Hypertext Transfer Protocol Secure, HTTPS)
{: #x2237225}

一種網際網路通訊協定，供 Web 伺服器和 Web 瀏覽器用來在網際網路上安全地傳送和顯示超媒體文件。


### 階段作業 (session)
{: #x2004539}

在行動裝置上啟動應用程式，且通知品質保證產品開始收集應用程式行為和問題之後的一段時間。

### 雲端可攜性 (cloud portability)
{: #x4585297}

跨公用或專用雲端運算環境移動應用程式及服務，或從不同的雲端提供者移動應用程式及服務的能力。

### 雲端運算 (cloud computing)
{: #x3877850}

一種運算平台，在這個平台上，使用者可以透過已連接的裝置，從任何地方存取服務形式的應用程式或運算資源。簡化的使用者介面及（或）應用程式設計介面 (API)，能讓使用者不必察覺支援此類服務的基礎架構。

[十三劃](#glossa)
---
---
### 資料儲存庫 (data store)
{: #x2052849}

儲存資料的位置（例如，資料庫系統、檔案或目錄）。

### 資訊來源
{: #x3129185}

可配置外部事件來源來發動觸發程式事件的程式碼片段。另請參閱[動作 (action)](#x2012974)。

### 資源 (resource)
{: #x2004267}

可以針對應用程式或服務實例佈建或保留的實體或邏輯元件。資源的範例包括資料庫、帳戶，以及處理器、記憶體和儲存空間限制。

### 資源群組 (resource group)
{: #x2161955}

所包含資源實例遵循的環境及限制。使用者可以與資源群組相關聯，以啟用協同作業。

### 路徑 (route)
{: #x2037338}

用來將要求導向至應用程式的 URL。路徑包含在推送應用程式時所指定的選用性主機（或子網域）和網域。例如，在路徑 myapp.example.com 中，myapp 是主機，而 example.com 是網域。路徑可與一個以上的應用程式相關聯。除非指定自訂網域，否則 IBM Cloud 會在您的應用程式路徑中使用預設的共用網域。另請參閱[自訂網域 (custom domain)](#x5728384)、[網域 (domain)](#x2021210)、[端點 (endpoint)](#x2026820)、[主機 (host)](#x2002243)、[子網域 (subdomain)](#x2040080)、[統一資源定位器 (Uniform Resource Locator)](#x2042491)。

### 運行環境 (runtime)
{: #x2391929}

用來執行應用程式的資源集。另請參閱[入門範本 (starter)](#x7470511)。


[十四劃](#glossa)
---
---
### 實例 (instance)
{: #x2002531}

一種實體，由保留給特定應用程式或服務的資源所組成。

### 實驗性服務 (experimental service)
{: #x7470450}

一種服務，尚未準備好用於正式作業，並且可以隨時從正式作業移除。另請參閱[測試版服務 (beta service)](#x7470455)。


### 構件 (artifact)
{: #x2262995}

軟體或系統開發處理程序所使用或產生的實體。構件的範例包括設計、需求、原始檔、計劃、Script、模擬、模型、測試計劃和二進位執行檔。在 HTTP 環境定義中，構件會有一個 URI，且構件會稱為資源。

### 端點 (endpoint)
{: #x2026820}

環境中的 API 或服務的位址。API 會公開端點，同時呼叫其他服務的端點。另請參閱[路徑 (route)](#x2037338)。

### 網址轉換 (network address translation)
{: #x2031199}

用來讓一個 IP 位址能藉由參考表，與數個其他 IP 位址通訊（例如專用子網路上的 IP 位址）的定址方法。網址轉換有兩種主要的類型：一對一，和多對一。


### 網域 (domain)
{: #x2021210}

命名階層的一部分，用於指定路徑。例如，example.com。在 IBM Cloud 中，網域與組織相關聯。網域物件並不直接連結至應用程式。另請參閱[自訂網域 (custom domain)](#x5728384)、[主機 (host)](#x2002243)、[組織 (organization)](#x2032585)、[路徑 (route)](#x2037338)、[子網域 (subdomain)](#x2040080)、[統一資源定位器 (Uniform Resource Locator)](#x2042491)。

### 認證 (credential)
{: #x2018813}

鑑別期間所獲得的資訊，用於說明使用者、群組關聯或其他安全相關的身分屬性，且用來執行如授權、審核或委派等服務。例如，使用者 ID 及密碼是容許存取網路及系統資源的認證。

### 輕量型 API 呼叫 (light API call)
{: #x7690463}

只讀取資料的用戶端作業。輕量型 API 呼叫所使用的資源低於重量型 API 呼叫，因為它們執行單一功能。另請參閱[重量型 API 呼叫 (heavy API call)](#x7690468)。

### 輕量型目錄存取通訊協定 (Lightweight Directory Access Protocol, LDAP)
{: #x2028538}

一種開放式通訊協定，它使用 TCP/IP 來存取支援 X.500 模型的目錄，且它不會引起對更複雜的「X.500 目錄存取通訊協定 (DAP)」的資源需求。例如，LDAP 可用來尋找網際網路或企業內部網路目錄中的人員、組織及其他資源。

[十五劃](#glossa)
---
---
### 儀表板 (dashboard)
{: #x2363941}

一個使用者介面元件，提供使用者各種來源的相關資訊的綜合性摘要。

### 層 (layer)
{: #x2028320}

母項映像檔的已變更版本。映像檔是由層所組成，其中已變更版本是以母項映像檔為基礎層層堆積，以建立新的映像檔。另請參閱[容器 (container)](#x2010901)、[映像檔 (image)](#x2024928)。

### 廣域唯一 ID (globally unique identifier, GUID)
{: #x2390455}

使用演算法決定的號碼，可唯一識別系統內的實體。

### 範本 (template)
{: #x2041200}

預先定義的構件結構。

### 範圍 (scope)
{: #x2037763}

在身分管理中，這是指原則或存取控制項目 (ACI) 可影響到的實體集。

### 編譯打包 (stage)
{: #x2067189}

在部署至正式作業環境之前，先將應用程式、服務或實例部署至預先定義的位置，以執行或測試。另請參閱[部署 (deployment)](#x2104544)。

[十六劃](#glossa)
---
---
### 憑證管理中心 (certificate authority, CA)
{: #x2016383}

受信任的第三方組織或公司，負責發出數位憑證。憑證管理中心通常會驗證被授與唯一憑證之個人的身分。另請參閱[中繼憑證 (intermediate certificate)](#x3753781)、[Secure Sockets Layer](#x2038004)、[授信主要憑證 (trusted root)](#x2042234)。

### 憑證簽署要求 (certificate signing request, CSR)
{: #x3530521}

組織傳送至憑證管理中心 (CA) 以取得憑證的電子訊息。此要求包含公開金鑰，而且是使用私密金鑰進行簽署；CA 會在使用自己的私密金鑰進行簽署之後傳回憑證。

### 磚 (tile)
{: #x2092493}

以視覺化呈現執行中的應用程式，其會在儀表板上提供狀態。

### 親緣性 (affinity)
{: #x2149238}

在相同網路節點上執行的兩個以上容器群組實例。另請參閱[反親緣性 (anti-affinity)](#x8888040)。

[十七劃](#glossa)
---
---
### 應用程式 (app)
{: #x4281528}

一種 Web 或行動裝置應用程式。另請參閱[行動應用程式 (mobile application)](#x4258535)、[Web 應用程式 (web application)](#x2116500)。

### 應用程式設計介面 (application programming interface, API)
{: #x2000186}

一個介面，容許以高階語言撰寫的應用程式使用作業系統或另一個程式的特定資料或功能。

### 檔案共用 (file share)
{: #x2022902}

在 IBM Cloud 環境中，使用者在其中儲存及共用檔案的持續性儲存空間系統。在 IBM Containers 中，使用者可以在檔案共用上裝載 Docker 磁區。

### 聯合 (federate)
{: #x2763229}

合併兩個以上的實體。例如，可以使用 IBM ID 聯合公司的已登錄網域。

[十八劃](#glossa)
---
---
### 擴充 (scale)
{: #x2004442}

透過新增更多應用程式或服務實例的方式，增加平台（或系統）容量

### 藍綠部署 (blue-green deployment)
{: #x7807335}

促成持續交付且將中斷時間減到最少的部署技術，這是藉由執行兩個幾乎相同的正式作業環境，分別稱為 Blue 和 Green。當其中一個環境（例如，Blue）是活躍的正式作業環境時，另一個環境（例如，Green）可以用來進行最終測試及部署。在 Green 中部署應用程式之後，Green 便成為正式作業環境，而 Blue 則開始閒置。另請參閱[紅黑部署 (red-black deployment)](#x8439181)。

[二十劃](#glossa)
---
---
### 觸發、觸發程式 (trigger)
{: #x2005384}

起始動作的機制。使用者可以明確地發動觸發程式，或者由外部事件來源代表使用者發動觸發程式。

[二十二劃](#glossa)
---
---
### 鑑別 (authentication, AuthN)
{: #x2014567}

驗證使用者或伺服器身分的處理程序。

## A
{: #glossa}

### API
{: #x2008805}

請參閱[應用程式設計介面 (application programming interface)](#x2000186)。

### AuthN
{: #x7470446}

請參閱[鑑別 (authentication)](#x2014567)。

### AuthZ
{: #x7470448}

請參閱[授權 (authorization)](#x2014653)。

## B
{: #glossb}

### BLU Acceleration
{: #x7470463}

IBM Db2 技術的集合，其設計主要用於執行主要讀取的商業智慧查詢處理。BLU Acceleration 包含四項主要的先進資料庫設計：動態記憶體內直欄式處理、可行性壓縮、平行向量處理和資料忽略。

### boilerplate
{: #x7233930}

一種範本，包含一個應用程式及其相關聯的運行環境以及特定網域的預先定義服務。

## C
{: #glossc}

### CA
{: #x2015942}

請參閱[憑證管理中心 (certificate authority)](#x2016383)。

### CLI
{: #x2008863}

請參閱[指令行介面 (command-line interface)](#x2051424)。

### compute
{: #x3723424}

在雲端中作為建置應用程式基礎的基礎架構或資源。

### CSR
{: #x2140147}

請參閱[憑證簽署要求 (certificate signing request, CSR)](#x3530521)。

## D
{: #glossd}

### DEA
{: #x2019805}

請參閱 [Droplet Execution Agent](#x7470348)。

### DevOps
{: #x5784896}

一種整合應用程式開發和 IT 作業的軟體方法，讓團隊能夠更快地交付程式碼以進入正式作業，並根據市場意見來持續反覆作業。

### Droplet
{: #x7470343}

Cloud Foundry 中的保存檔，其中包含應用程式及其運行環境和架構相依關係，保存以後才可部署至雲端。

### Droplet Execution Agent (DEA)
{: #x7470348}

負責部署應用程式的 Cloud Foundry 元件。

## G
{: #glossg}

### GB-小時 (GB-hour)
{: #x7470477}

對於特定建置套件，每小時所有應用程式實例執行的累計記憶體量（以 GB 為單位）。

### GUID
{: #x2390457}

請參閱[廣域唯一 ID (globally unique identifier)](#x2390455)。


## H
{: #glossh}

### HTTP 方法 (HTTP method)
{: #x2024674}

「超文字傳送通訊協定」所使用的動作。HTTP 方法包括 GET、POST 和 PUT。

### HTTPS
{: #x2193603}

請參閱[超文字傳送通訊協定安全 (Hypertext Transfer Protocol Secure)](#x2237225)。

## I
{: #glossi}

### IaaS
{: #x4585337}

請參閱[基礎架構即服務 (infrastructure as a service)](#x4585332)。

### IAM
{: #x2193801}

請參閱 [Identity and Access Management](#x7547040)。

### IBM Cloud
{: #x7301758}

一種以雲端為基礎的開放標準平台，用於建置、管理和執行所有類型的應用程式（例如，Web、行動、海量資料和智慧型裝置）。功能包括 Java、行動後端開發、應用程式監視，以及來自生態系統合作夥伴和開放原始碼的特性；全都提供為雲端中的服務。

### Identity and Access Management (IAM)
{: #x7547040}

控制獲授權使用者存取資料及應用程式的程序，同時又協助公司遵守各種法規要求。

### IoT
{: #x6714346}

請參閱[物聯網 (Internet of Things)](#x6714341)。


## J
{: #glossj}

### JAR 檔 (JAR file)
{: #x2406009}

Java 保存檔。

### JavaScript 物件表示法 (JavaScript Object Notation, JSON)
{: #x3292165}

一種以 JavaScript 的物件/文字表示法為基礎的輕量型資料交換格式。JSON 與程式設計語言無關，但使用各種語言的使用慣例。

### JSON
{: #x4267096}

請參閱 [JavaScript 物件表示法 (JavaScript Object Notation)](#x3292165)。


## L
{: #glossl}

### LDAP
{: #x2481619}

請參閱[輕量型目錄存取通訊協定 (Lightweight Directory Access Protocol, LDAP)](#x2028538)。

## M
{: #glossm}

### MBaaS
{: #x7044865}

請參閱[行動後端即服務 (mobile backend as a service)](#x7044858)。

## O
{: #glosso}

### OAuth
{: #x6013335}

以 HTTP 為基礎的授權通訊協定，它透過在資源擁有者、用戶端與資源伺服器之間建立核准互動的方式，代表資源擁有者授與應用程式對於受保護資源的範圍存取權。

## P
{: #glossp}

### PaaS
{: #x2029790}

請參閱[平台即服務 (platform as a service)](#x2029786)。

## R
{: #glossr}

### REST
{: #x3220987}

請參閱[具象狀態傳輸 (Representational State Transfer, REST)](#x3220976)。

## S
{: #glosss}

### SaaS
{: #x4585391}

請參閱[軟體即服務 (software as a service)](#x4585386)。

### Secure Sockets Layer (SSL)
{: #x2038004}

提供通訊隱私權的安全通訊協定。主從式應用程式可以透過 SSL，利用專為防止竊聽、竄改及訊息偽造而設計的方法進行通訊。另請參閱[憑證管理中心 (certificate authority)](#x2016383)。

### SOR
{: #x2214822}

請參閱[記錄系統 (system of record, SOR)](#x6735061)。

### SSL
{: #x2483907}

請參閱 [Secure Sockets Layer](#x2038004)。

### SSO
{: #x3456450}

請參閱[單一登入 (single sign-on, SSO)](#x2213318)。

## U
{: #glossu}

### URI
{: #x2116461}

請參閱[統一資源識別碼 (Uniform Resource Identifier)](#x2116436)。

### URL
{: #x2042718}

請參閱[統一資源定址器 (Uniform Resource Locator)](#x2042491)。

## V
{: #glossv}

### VM
{: #x2043253}

請參閱[虛擬機器 (virtual machine)](#x2043165)。

### VPN
{: #x2484351}

請參閱[虛擬私密網路 (virtual private network)](#x2043188)。


## W
{: #glossw}

### WAR
{: #x2844389}

請參閱 [Web 保存檔 (web archive)](#x2116506)。

### WAR 檔 (WAR file)
{: #x2406005}

請參閱 [Web 保存檔 (web archive)](#x2116506)。


### Web 保存檔 (web archive, WAR)
{: #x2116506}

這是 Java EE 標準所定義的一種壓縮檔格式，用來將安裝和執行 Web 應用程式時所需的所有資源儲存在單一檔案中。

### Web 應用程式 (web app)
{: #x7636628}

請參閱 [Web 應用程式 (web application, web app)](#x2116500)。

### Web 應用程式 (web application, web app)
{: #x2116500}

可供 Web 瀏覽器存取的應用程式，除了靜態顯示資訊，還提供一些功能，例如可讓使用者查詢資料庫。Web 應用程式的常見元件包括 HTML 頁面、JSP 頁面及 Servlet。另請參閱[應用程式 (app)](#x4281528)。
