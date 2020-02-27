# 目錄
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [多媒體處理描述語言](#多媒體處理描述語言)
- [目錄](#目錄)
- [概念](#概念)
	- [多媒體](#多媒體)
	- [敏捷軟體開發宣言](#敏捷軟體開發宣言)
		- [核心](#核心)
		- [原則](#原則)
		- [目的](#目的)
	- [Git版本控制](#git版本控制)
	- [敏捷軟體開發解決方案](#敏捷軟體開發解決方案)
		- [Scrum](#scrum)
			- [角色](#角色)
				- [開發團隊](#開發團隊)
				- [產品負責人](#產品負責人)
				- [Scrum專家](#scrum專家)
			- [物件](#物件)
				- [項目](#項目)
				- [任務](#任務)
				- [產品待辦清單](#產品待辦清單)
				- [衝刺待辦清單](#衝刺待辦清單)
				- [潛在可交付產品增量](#潛在可交付產品增量)
				- [燃盡圖](#燃盡圖)
			- [活動](#活動)
				- [衝刺](#衝刺)
				- [每日站立會議](#每日站立會議)
				- [衝刺規劃會議](#衝刺規劃會議)
				- [產品待辦清單精煉會議](#產品待辦清單精煉會議)
				- [衝刺檢視會議](#衝刺檢視會議)
				- [衝刺回顧會議](#衝刺回顧會議)
		- [DevOps](#devops)
			- [持續整合與持續發佈](#持續整合與持續發佈)
				- [持續整合](#持續整合)
				- [持續發佈](#持續發佈)
		- [總結](#總結)
	- [融合](#融合)
		- [多媒體處理描述語言平台](#多媒體處理描述語言平台)
			- [多媒體資料庫](#多媒體資料庫)
			- [多媒體處理描述語言編輯器](#多媒體處理描述語言編輯器)
			- [多媒體處理描述語言伺服器](#多媒體處理描述語言伺服器)
		- [版本的控制](#版本的控制)
		- [個人創作](#個人創作)
		- [大型多人協作](#大型多人協作)
		- [線下線上](#線下線上)
		- [流程與自動化](#流程與自動化)
		- [授權與販賣](#授權與販賣)
		- [一條龍製作](#一條龍製作)
- [語法](#語法)
	- [語法概念](#語法概念)
	- [呼叫與繼承](#呼叫與繼承)
		- [物件與方法](#物件與方法)
		- [縮排與換行](#縮排與換行)
	- [影片](#影片)
		- [匯入](#匯入)
		- [素材](#素材)
		- [軌道](#軌道)
		- [剪輯](#剪輯)
		- [特殊效果](#特殊效果)
		- [合成](#合成)
		- [輸出](#輸出)
	- [運算](#運算)
		- [布林運算](#布林運算)
		- [數學運算](#數學運算)
		- [比較運算](#比較運算)
	- [流程控制](#流程控制)
	- [迴圈](#迴圈)
		- [while迴圈](#while迴圈)
		- [for迴圈](#for迴圈)
	- [函式](#函式)
- [參考文獻](#參考文獻)
- [中音對照表、專有名詞對照](#中音對照表專有名詞對照)

<!-- /TOC -->

# 概念
「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)是為了實現將 **多媒體** 、 **敏捷軟體開發宣言** 、 **「分散式版本控管系統」(DVCS; Distributed Version Control System)** 與 **敏捷軟體開發解決方案** 融合的語言，也就是將 **「多媒體」(Multimedia)** 、 **「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)** 、**Scrum**、 **Git版本控制** 、 **「開發與運維」(DevOps, Development Operations)** 、 **「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)** 等多種概念與技術融合，為了達到創新融合各項技術的「多媒體製作解決方案」，達到多媒體可以不斷的製作、修正的循環，以下依序講解所提到的專有名詞並最後講解如何融合。  

## 多媒體
「多媒體」(Multimedia)一詞出現在 1950 年代，由於每個時代的環境不同，所以對於多媒體的解釋也有些許差別。  

多媒體從字面上來看，就是「多」(Multi)和「媒體」(Media)的結合。  

其中「媒體」(medium)一詞來自於拉丁文「medius」一字，為「中介的」、「中間的」意思。韋伯字典中「medium」一詞之義為「立於中間或中介的某種東西」。因此，人與人之間所賴以溝通的觀念、思想或意見的中介物便可稱之為媒體。  

媒體是一種傳播資訊的媒介，所以多媒體最基本的解釋應該是「結合多種傳播資訊媒介的媒體」，而「多」媒體的「多」字，包含的媒體如「文字」(text)、「圖片」(picture)、「圖形」(graphic)、「影像」(image)、「影片」(video)、「動畫」(animation)、「音樂」(music)、「聲音」(sound)等[?]。  

## 敏捷軟體開發宣言
「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)是為了解決瀑布式開發模式無法面對現在快速的需求變化而發展出的模式，其中做著名的方式就是Scrum模式，針對Scrum模式而設計的解決方案如DevOps、CI/CD等，已經被微軟、GitHub與Google等所支持。

### 核心
藉著親自並協助他人進行軟體開發，我們正致力於發掘更優良的軟體開發方法。透過這樣的努力，我們已建立以下價值觀:  

- **個人與互動** 重於 流程與工具  
- **可用的軟體** 重於 詳盡的文件  
- **與客戶合作** 重於 合約協商  
- **回應變化** 重於 遵循計劃  

也就是說，雖然右側項目有其價值，
但我們更重視左側項目。  

### 原則
敏捷宣言背後的原則，我們遵守這些原則:  

- 我們最優先的任務，是透過及早並持續地交付有價值的軟體來滿足客戶需求。
- 竭誠歡迎改變需求，甚至已處開發後期亦然。敏捷流程掌控變更，以維護客戶的競爭優勢。
- 經常交付可用的軟體，頻率可以從數週到數個月，以較短時間間隔為佳。
- 業務人員與開發者必須在專案全程中天天一起工作。
- 以積極的個人來建構專案，給予他們所需的環境與支援，並信任他們可以完成工作。
- 面對面的溝通是傳遞資訊給開發團隊及團隊成員之間效率最高且效果最佳的方法。
- 可用的軟體是最主要的進度量測方法。
- 敏捷程序提倡可持續的開發。贊助者、開發者及使用者應當能不斷地維持穩定的步調。
- 持續追求優越的技術與優良的設計，以強化敏捷性。
- 精簡──或最大化未完成工作量之技藝──是不可或缺的。
- 最佳的架構、需求與設計皆來自於能自我組織的團隊。
- 團隊定期自省如何更有效率，並據之適當地調整與修正自己的行為。

### 目的
簡單來說「敏捷軟體開發宣言」目的如下:
- 積極與樂於改變的態度，以客戶的利益為出發點，盡力做出可用的軟體。
- 天天面對面與人互動，重視團隊成功重於個人成功。
- 持續且短時間交付產品，並能持續追求優越技術與優良設計。
- 定期自我反省並實際做出改善。

## Git版本控制
Git版本控制是一個「分散式版本控管系統」(DVCS; Distributed Version Control System)[?]，以分散式管控、大型的多人協作最為重要，其中軟體到核心概念是「合併」(Merge)，紀錄版本的方式以觀察檔案內容變化而非目錄與檔名變化。  

此軟體的想法來自於Linux之父，目的就是來自於當時全世界都在開發Linux的系統內核，大量的人開發者參與其中，因此需要一個並非是集中式管理機制來解決程式衝突的問題，此機制儼然而生。  

同時Linux之父林納斯·托瓦茲講過以下的話

> 類似什麼在很多人的共同開發下，程式碼的錯誤會在很短的時間內找出來。

因此大型的多人協作與社群參與在未來必為方向。

## 敏捷軟體開發解決方案
隨著「敏捷軟體開發宣言」的發佈後的興起與流傳，其中符合「敏捷軟體開發宣言」的Scrum模式因為易學簡單而快速流通，軟體開發的文化也持續改變。  

雖然「開發」得以解決，但卻在「運維」這方面遇到了卡關，因為大多公司賣的不是軟體而是軟體產生的服務，使得系統在開發、更新與安全、可靠性上遇到了衝突，因此整體系統的開發、測試、維護便成為三方面的衝突與隔閡。  

因此有人提出了「開發與運維」(DevOps, Development Operations)這項概念，透過文化、實務與工具來解決三方的隔閡，達到程式開發的快速迭代、更新與自動化，目前Microsoft、GitHub、GitLab與Google等著名的大型企業都在運作的模式，並且世界各地也持續舉辦DevOpsDay[?]。  

### Scrum
有人於1990年左右提出提出了Scrum，核心思想就是「全體一起前進，把求傳來傳去」，其中的概念來自於橄欖球，橄欖球中不同的角色與職位在各階段的互相重疊完成。  

此方式將過去「瀑布式開發流程」:

- **需求規格**
- **系統分析**
- **系統設計**
- **實作**
- **測試**
- **部署**
- **維護**

必須依照這個開發，當有問題時就會往後一步驟重新來，瀑布式開發流程造成開發過程無法快速應變需求與改變，在Scrum的概念出現後狀況得以改變，這個想法也剛好很符合「敏敏捷軟體開發宣言」所提到的訴求與想法。  

#### 角色
Scrum有三種角色，「開發團隊」(Dev Team, Development Team)、「產品負責人」(PO, Product Owner)、「Scrum專家」(SM, ScrumMaster)，開發團隊負責產生內容，產品負責人負責修正與想出內容的方向，而Scrum專家類似於教練與輔導員的角色，我們稱三者組成的團隊或組織叫做「Scrum團隊」(Scrum Team)或者「團隊」(Team)，如下做詳細解說。  

##### 開發團隊
「開發團隊」(Dev Team, Development Team)是實際產成果的團隊，以完成客戶需求產生有用的軟體作為目標，以如何解決問題作為遇到問題的方式，並以自我管理與持續改善作為遇到問題解決的基石。  

##### 產品負責人
「產品負責人」(PO, Product Owner)決定程式開發方向的，並針對需求與「利益關係人」調整成果的方向，可以一位或者多位組成。所謂的「利益關係人」類似於你的老闆、客戶、主管等，會提出建議、影響程式走向的人。「產品負責人」就負責將這些內容重新的整理並告知開發團隊做調整，讓團隊的開發可以持續的開發與修正。

##### Scrum專家
「Scrum專家」(SM, ScrumMaster)也稱為「Scrum主管」或「Scrum促進者」，是Scrum的教練與輔導員，讓整個團隊可以合理的使用Scrum，並幫助團隊解決實施過程中的問題，並時常的為團隊提出意見做改進，以「我現在的行動可以幫助團隊和組織盡快獨立自主嗎？」這件事情為行為的出發。  

#### 物件
以下是Scrum常見的名稱與物件，也是通用的物件，基本不同的管理系統都會有這個:

##### 項目
「項目」(Item)，也稱作為「描述」(Story)，是產品負責人定義的，「項目」(Item)的大小要剛好可以團隊在平常可以完成3~5個，太多太繁雜，太少沒做完感覺沒有用，都會打擊團隊。

「項目」(Item)在GitHub與GitLab可使用「里程碑」(Milestones)代替。

##### 任務
「任務」(Task)是「開發團隊」(Dev Team, Development Team)針對物件所列出的任務;任務的分配是開發團隊自己分配的。  

「任務」(Task)在GitHub與GitLab可使用「議題」(Issues)代替。

##### 產品待辦清單
「產品待辦清單」(Product Backlog)是「項目」(Item)的文檔，大概描述「項目」(Item)的內容、產生的東西、特性與概念等，同時安排「任務」(Task)。  

內容由「產品負責人」(PO, Product Owner)負責調整、製作，會將「產品待辦清單」(Product Backlog)寫到「項目」(Item)並以「項目」(Item)為單位，製作的時間長度以天為單位，順序由上而下。

「產品待辦清單」(Product Backlog)在GitLab可使用每個「里程碑」(Milestone)內的「議題」(Issues)、「合併請求」(Merge Requests)、「參與者」(Participants)、「標籤」(Labels)、「標題」(Title)與「描述」來代替。

##### 衝刺待辦清單
「衝刺待辦清單」(Sprint Backlog)是「開發團隊」(Dev Team, Development Team)向「產品負責人」(PO, Product Owner)承諾這個「衝刺」(Sprint)會盡力完成的「項目列表」(Item List)，以「任務」(Task)為單位，時間以小時為單位，並在16小時內完成，超過就會再分解。  

由於GitLab並未像Azure DevOps有提供「衝刺待辦清單」(Sprint Backlog)的「項目」(Item)連結「任務」(Task)並條列、拉動與預先創立的功能，可以用幾個方法來代替:
1. 使用Google日曆列出「衝刺」(Sprint)週期，搭配GitLab的「議題看板」(Issue Boards)加上名稱為「衝刺待辦清單」(Sprint Backlog)的「標籤」(Label)並新增「列」(List)後連結此標籤。
2. 為每一個「議題」(Issue)拉動到`To Do`後標註結束時間到「衝刺」(Sprint)結束為止。


##### 潛在可交付產品增量
「潛在可交付產品增量」(Potentially Shippable Product Increment)是「開發團隊」(Dev Team, Development Team)的產出，簡單的說就是「產品負責人」(PO, Product Owner)說要上線就可以馬上上線的東西才算數。  

##### 燃盡圖
「燃盡圖」(Burndown Chart)是一個公開展示的圖表，顯示當前「衝刺」(Sprint)中未完成的「任務」(Task)數目，或在「衝刺待辦清單」(Sprint Backlog)上未完成的「項目」(Item)數目。  

「燃盡圖」(Burndown Chart)在每次的「衝刺」(Sprint)中大部分時間內都維持平坦，但計畫仍然可以按照既定時間進行，也就是說盡量將工作規劃與平均分配好，但又可以完成指定的工作量。  

#### 活動
以下是Scrum常見的活動，每一個活動都有其目的和「時間限制」(Time Boxed)，主要活動如下：

##### 衝刺
「衝刺」(Sprint)是指「開發團隊」向「產品負責人」(PO, Product Owner)承諾在指定的時間內可以完成的「項目」(Item)後，就著手去想辦法在時間內完成「項目」(Item)。  

「衝刺」(Sprint)是以週來做單位計算，通常是1~4週，但盡量不要超過兩週，並且「衝刺」(Sprint)長度應該要保持穩定盡可能不變，這樣才容易讓團隊掌握節奏，也容易預估和比較「衝刺」(Sprint)內的工作量。

大原則是「衝刺」(Sprint)內的「衝刺待辦清單」(Sprint Backlog)不改變，但有原則就有例外。

##### 每日站立會議
「每日站立會議」(Daily Scrum)是每讓團隊資訊同步，會有以下規定:
- 無論「團隊」(Team)的規模大小，會議時間不能超過10~15分鐘。
- 要站著罰站，讓大家長話短說。
- 歡迎任何人加入。
- 只有「開發團隊」(Dev Team, Development Team)的成員可以發言。
- 應在固定時間地點。

「開發團隊」(Dev Team, Development Team)的各成員會有以下發言:
1. 昨天完成哪些工作?
2. 今天要完成哪些工作?
3. 是否遇到困難、問題或挑戰?

「Scrum專家」(SM, ScrumMaster)則負責記錄「開發團隊」(Dev Team, Development Team)遇到的問題。

##### 衝刺規劃會議
「衝刺規劃會議」(Sprint Planning)是指「衝刺」(Sprint)開始時，討論一下這個「衝刺」(Sprint)團隊可以交付哪些「項目」(Item)。  

「項目」(Item)優先順序「產品負責人」(PO, Product Owner)決定，要選多少「項目」(Item)由「開發團隊」(Dev Team)決定。

##### 產品待辦清單精煉會議
「產品待辦清單精煉會議」(PBR, Product Backlog Refinement)是「產品負責人」(PO, Product Owner)跟「團隊」(Team)一起討論近期內會開始施工的「項目」(Item)，主要是從商業和使用者角度切入，盡可能不觸及技術細節。

##### 衝刺檢視會議
「衝刺檢視會議」(Sprint Review)是指「衝刺」(Sprint)結束時針對產品的會議，「產品負責人」(PO, Product Owner)邀請用戶、相關利益者以及經理等相關人員，對目前的進度給意見，是要可用的軟體才算產出。  

不準備PowerPoint或其他簡報，單純就軟體操作或者成果取得回饋。

##### 衝刺回顧會議
「衝刺回顧會議」(Sprint Retrospective)也稱作為Sprint Retro，也可以稱為「自省」會議，會議時間限制4小時內。  

在「衝刺檢視會議」(Sprint Review)取得後，「Scrum團隊」(Scrum Team)所有成員針對這個「衝刺」(Sprint)中團隊的工作模式討論與改善，並定出下個「衝刺」(Sprint)改善事項。

為了創造一個安全的環境，原則上只有「Scrum團隊」(Scrum Team)成員才能參加。

### DevOps
「開發與運維」(DevOps, Development Operations)是為了解決「敏捷軟體開發」中遇到的困境，透過文化、實務與工具提高「開發團隊」(Dev Team, Development Team)與「IT運維人員」之間透明度，使兩者團隊可以融合、合作、溝通與授受，來加快程式在 **開發** 、 **測試** 、**部署** 與 **維護** 的生命週期，達到快速、需求化、高品質、穩定與減少復原時間，因此會分成幾個項目:
- 通訊與協作:「工作流程看板」(Boards)、「電子郵件」(Email)與通訊軟體等。
- 監控和紀錄:Git、監控工具與「燃盡圖」(Burndown Chart)等。
- 自動化程序:「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)、「持續部署」(Continous Deployment)、「管道」(Pipelines)、虛擬機器、容器技術、無伺服器運算與微型服務等。

後續為了實際相關的內容，因此將講解自動化程序中一項重要的技術，「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)。

#### 持續整合與持續發佈
「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)的目的是為了可以 **持續的驗證系統開發結果** ，經由「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)盡量確保每一次小變更正確，讓最後的產品可以更接近需求、產出改進、減少人力與減少重大錯誤，最終達到專注開發、測試與運維。  

##### 持續整合
「持續整合」(CI, Continuous Integration)是針對Git的每一次的提交、拉請求、系統變動，能夠持續且自動地進行驗證，將檢查的人力做最小化或簡單化，讓開發、測試與佈署之間可以透明。  

其中將開發環境、修改項目、套件函式庫檢查、靜態檢查、動態檢查、風格化檢查與相依性檢查等不斷的整合，減少人力達到專注、快速與減少錯誤。  

##### 持續發佈
「持續發佈」(CD, Continuous Delivery)是一切的最終目的，就是讓客戶或者使用者可以用到產品。  

在上述都達到與通過後，自動化的發佈不同版本、平台與系統，讓人們在使用上可以享有快速、持續更新、接近使用者與有品質的程式。

### 總結
其實說了這麼多，最終的重點就是做出一個令客戶或者使用者滿意的軟體，上述這些只是可以接近目的的一個方法，但也是剛好一切的發展過程剛好造就了這歷史，開發者、Git、敏捷、Scrum、DevOps。

## 融合
為了可以達到初衷的想法:

> 大型的多人協作

我們將上述 **多媒體** 、 **敏捷軟體開發宣言** 、 **「分散式版本控管系統」(DVCS; Distributed Version Control System)** 與 **敏捷軟體開發解決方案** 等作融合，簡單說明解釋就是如何做到快速適應、多人協作、版本紀錄與自動化等方式達到快速製作多媒體，將上述技術做融合，已達到新的多媒體製作解決方案。

### 多媒體處理描述語言平台
「多媒體處理描述語言平台」是一個從離線到雲端、大型多人協作、跨媒體、一條龍製作、快速迭代、自動發佈、開放原始碼、多來源匯入、授權明確等為目標的平台，其實中最終的目標是在現代快速變遷的時代中經由大型多人協作達到快速製作。  

因此會由以下單元組成:「多媒體處理描述語言」、「分散式版本控管系統」、「多媒體資料庫」、「多媒體處理描述語言編輯器」、「多媒體處理描述語言伺服器」，這些單元所融合可建構為「多媒體處理描述語言平台」。  

由於有些東西在本章已經講解過了，因此只針對「多媒體資料庫」、「多媒體處理描述語言編輯器」與「多媒體處理描述語言伺服器」三項講解，詳細可以從「[多媒體處理描述語言平台](https://githib.com/)」(目前還未建置好)了解。

#### 多媒體資料庫
多媒體的資料庫最重要的核心:

> 減少因媒體的多元性與多變性而造成媒體的品質下降。

簡而言之就是利用資料庫紀錄多媒體特徵與資訊來減少原始素材不斷被利用製作造成品質下降、內容重複、內容增加等問題，確保產生的影片是最高品質。

詳細內容可以從「[多媒體資料庫](https://githib.com/)」(建置好但還沒編輯)了解。  

#### 多媒體處理描述語言編輯器
「多媒體處理描述語言編輯器」目的是依照「多媒體處理描述語言」的描述呈現出媒體最終樣態，也就是媒體透過腳本的方式製作出來。  

編輯器會內建文字編輯模組、「多媒體處理描述語言」轉譯直譯器、Git版本控制、圖形化剪輯、多媒體資料庫，詳細內容可以從「[多媒體處理描述語言編輯器](https://githib.com/)」(建置好但還沒編輯)了解。

#### 多媒體處理描述語言伺服器
「多媒體處理描述語言伺服器」是一個可以在網頁上面將「多媒體處理描述語言」的描述呈現出媒體的最終樣態，有點是「多媒體處理描述語言編輯器」，但是是在網頁上呈現的伺服器，類似串流平台YouTube但影片是可以透過程式去做改寫跟可分版本。

伺服器會內建文字編輯模組、「多媒體處理描述語言」轉譯直譯器、Git版本控制、圖形化剪輯與多媒體資料庫等，但多出了伺服器的服務在裡面，詳細內容可以從「[多媒體處理描述語言伺服器](https://githib.com/)」(建置好但還沒編輯)了解。

### 版本控制
過去在製作影片的方式是經由剪輯軟體等後製輸出影片，再將影片上傳至指定的平台給他人觀看，因此會出現現在大部分的影音平台在上傳影片後是不能修改與修正，發布後成定局。

這樣會有一個問題，發佈出去的影片無法在做修改，但如果提供原始影片與後製軟體的編輯檔，又會因為編輯檔本身無法像影片播放器一樣普及在每個人之中，因此只有相同後製軟體可以使用。

又因為多媒體本身就是備份、版本管控、處理與分析就是已經一定成本與難度，因此多媒體在版本管控上就已經有困難了，最終導致現在多為發佈定終身，即使要更新也只能撤銷連結重新發布。

因此多媒體處理描述語言從個人後製開始，使用Git版本控制、後製軟體播放器與多媒體資料庫庫，解決版本控制問題。

### 個人創作
在個人創作時候，強大的軟體與工具可以為個人創作發揮很大的幫助，版本管理、持續整合與持續發佈，將協助創作者減少創作過程的所消耗的時間。

### 大型多人協作

### 線下線上

### 流程與自動化

### 授權與販賣

### 一條龍製作

# 語法
## 語法概念
語法靈感來自Python、Markdowb與YAML，但多來自Python，因此如果熟悉Python會較為輕鬆使用，但還是會與原本的Python有所差別，因此

> Python可以在MPDL運作，但MPDL不能在Python執行

運作的方式

> MPDL採用編譯器，MPDL語言會編譯成`.py`，並以Python直接執行此檔案

目前無法以指令模式來執行，未來會希望可以解決這項問題。由於目前針對影片製作提出了製作流程與語法，但目前因為暫定初代語法，未來會針對Python與不同藝術領域結合，所以這邊先提出語法的基本運作原則:

- 輸出的結果是將不同的「物件」一層一層堆疊在一個框架內
- 「物件」的「型態」是定義於「類別」
- 「物件」的「函式」稱為「方法」
- 「方法」只能被指定的「物件」所使用
- 物件的使用可以類似於流程一樣

後續會持續修正，同時建議語法使用flake8等風格化規範，讓撰寫上大家不會有誤會等問題。  

## 呼叫與繼承
影像輸出上為了可以方便的控制輸出的結果，這邊介紹控制的影像輸出的結果，使用上有[物件與方法](#物件與方法)與[縮排與換行](#縮排與換行)兩種方式

### 物件與方法
此參考的是Python在物件導向的使用方式，但並不完全使用一樣。最基本的就是使用`.`去區分層級與呼叫，越前面的函式可以直接影響後面的輸出結果。以下面程式為例，動作的方式代表了先匯入，再來剪輯然後輸出，如以下程式:

```MPDL
from aabbcc import video


export().clip().video()

```

同時也接受分開去使用，來避免重複與長度過長的問題，但必須上一個與下一個都呼叫到才會有效用。例如有`a()`、`b()`與`c()`函式，`c()`的內容要繼承給`b()`，就必須使用`b().c()`方式去讓`b()`呼叫`c()`使`b()`繼承`c()`的內容，但如果要讓`a()`可以繼承`c()`的內容使用上必須使用`a().b().c()`方式讓`a()`可以繼承`c()`。

以下面程式為例，先匯入影片並命名`video1`與`video2`，並且個別放入軌道`track(1)`與`track(2)`，然後再將`track(1)`加上特效`effects()`開啟「去交錯」讓`track(1)`中所有的影片都可以去交錯，然後將影片中所有軌道使用`composite()`合成起來，最後輸出。

```MPDL
from aabbcc import video1
from ddeeff import video2


track(1).clip(1).video1()
track(2).clip(2).video2()

effects(deinterlacing=True).track(1)

composite().track(1)
composite().track(2)

export().composite()

```

### 縮排與換行
此參考的是Python與YAML在縮排與換的方式去控制影響的內容。保留了Python常用的保留字，並參考YAML的方式改善上述的問題，讓閱讀上更加直覺與明瞭。

換行使用`\n`或者`\r\n`，也就是LF與CRLF的換行模式，建議使用`\n`。縮排可以使用Tab或者空白，不限定Tab與空白的次數，只要統一對齊就可以，但建議使用四個空白來控制縮排的對齊。

以[呼叫與繼承](#呼叫與繼承)的第一個範例為例，使用縮排來控制繼承的內容，越內縮的就代表被會被上一個不內縮的呼叫，行數與內容卻比使用物件與方法，程式如下:

```MPDL
from aabbcc import video

export()
  clip()
    video()

```

如果複雜一點使用1的第二個範例為例，使用縮排來控制繼承的內容，`clip()`因為必須使用`.`方式呼叫素材，所以會無法分開。程式因此也比較直觀與易懂，程式如下:

```MPDL
from aabbcc import video1
from ddeeff import video2


export()
  composite()
    effects(deinterlacing=True)
      track(1)
        clip(1).video1()

    track(2)
      clip(2).video2()

```

不過除了縮排，換行也可以控制呼叫與繼承，高的行數可以優先呼叫低的函式，而高的行數也會直接決定每個函式被呼叫的排列，例如:

```MPDL
from aabbcc import video1
from ddeeff import video2


effects(deinterlacing=True)
  track()
    clip().video1()

track()
  clip().video2()

composite()
export()

```

如果函式的排列如果同時使用有參數強制與無參數指定非強制指定，而且對於被呼叫函式並非第一個呼叫，則優先使用使用強制指定的，例如:

```MPDL
from aabbcc import video1
from ddeeff import video2


effects(deinterlacing=True)
  track()
    clip().video1()
    clip().video1()
    clip(2).video1()

track()
  clip().video2()

composite()
export()

```

## 影片
MPDL在影片的處理方式除了語法靈感來自Python、markdown與YAML，處理影像的靈感則來自於剪輯軟體與[FFmpeg](https://ffmpeg.org/ffmpeg.html)，除了上述也針對流程有以下見解。

影片製作流程分三項基本型態:「素材」、「規劃」與「處理」，「規劃」被劃分在「素材」的產生方式、製作流程、工作內容、方法等；「素材」則被劃分在原始的影片、圖片、聲音或其他媒體；「處理」則是劃分在如何處理原始的「素材」並輸出，符合基本流程。  

這些「型態」可以對應以下基本流程:

> 不同的「素材」在「規劃」的限制下經過「處理」所產生的成果。  

> 除了上述基本流程，可以自定義流程、方法或者敘述。  

會依照三種「型態」:「素材」、「規劃」與「處理」做出不同「物件」與「方法」，以下是針對影片在不同「型態」中定義的「物件」與「方法」:

1. 規劃  
影片製作的流程與工作項目，如下常見的流程:
    - 前期製作
    - 劇本
    - 腳本
    - 分鏡
    - 運鏡
    - 後製
    - 殺青  
    - 翻譯
    - 授權  
    - 販賣
    ...

1. 素材  
製作影片的材料，也就是將多媒體的種類、規格、規範等描述出來，如下常見的媒體:
    - 文字
    - 圖片
    - 圖形
    - 影像
    - 影片
    - 動畫
    - 音樂
    - 音效  
    - 特效
    - 字幕
    ...

2. 處理  
多媒體經過處理產生影片，如下常見處理方式:
    - 剪輯
    - 合成
    - 字幕
    - 轉場  
    - 翻譯  
    - 去交錯
    ...

### 匯入
```MPDL
from . import vlase
```
此方法是用於匯入素材、多媒體資料庫與套件，素材必須以指定的數位摘要或者指紋來指定的匯入檔案，以SHA2為例計算出檔案雜湊值最少前六碼來標記，匯入前會將指定的檔案做驗證才會真正使用。  

影像輸出的層級由「輸出」>「合成」>「軌道」>「剪輯」>「素材」>「匯入」。  

基本的不安全匯入:

```MPDL
import aabbcc
```

當然還可以針對相同目錄往下尋找路徑與程式碼等做匯入，安全匯入:

```MPDL
from path import aabbcc
```

當然你也可以針對你的素材對應指定名稱，名稱必須是英文大小寫加上底線。  

```MPDL
import aabbcc as abc
```

那如果你想要使用相對路徑指定檔案所在位置，使用`.`來到達。

```MPDL
from . import aabbcc as abc
```

如果指定上一層指定匯入，那可以使用`..`方式回去上一個目錄。

```MPDL
from .. import aabbcc as abc
```

也可以設定絕對路徑指定目錄方法，來設定指定素材、多媒體資料庫或套件的目錄位置，`...`為Linux根目錄，Windows是指回到比磁碟機槽還前面去尋找磁碟機。

Linux:
```MPDL
from ...home.user import aabbcc as abc
```

Windows:
```MPDL
from ...c.path import aabbcc as abc
```

如果在Linux上，也可以使用`~`來指定回到家目錄。

Linux:
```MPDL
from ~ import aabbcc as abc
```

匯入時會先將指定路徑的媒體計算雜湊值，驗證名稱與內容是否一致後會產生一個快取資料夾，提供預處理或者預覽影像的暫存區。

```
-path-.temp
     |-multimedia
```

範例
```MPDL
from path import aabbcc as abc
```
```
-path- .temp
     |-aabbcc...
```

如果是匯入來源為多媒體資料庫，而且資料路徑是在執行文件同意目錄的底下。

```
-path-.temp
     |-multimedia
     |-video.mpdl
     |-.mmdb
```

如果不是在相同目錄下，並且可直接使用而不需要匯入，預設上是直接可以直接匯入整個或者只指定單一

使用注意事項:
- 可連結媒體資料庫
- 可以使用遠端，也可以使用本地
- 原始多媒體素材匯入必須是雜湊值，但可以使用`as`改成自己易懂的名稱
- 雜湊值最少6位數，以辨別唯一素材。
- 匯入前針對所有素材與內容做雜湊計算驗證
- 可以使用匯入已經是結果的素材，也就是使用語言製作的影片再次匯入，但影片是並未成形的。
- 可以利用影片內再分類別
- 雖然未限制大小寫，但素材是以雜湊值匯入者建議使用小寫

### 素材
```MPDL
material(sequence=1, ss=None, t=None, to=None, high=1080, with=1920, db=False)
```
匯入後可以指定檔案預處理，比如解碼、長寬、大小等，可用於加速在即時預覽的速度或加快輸出輸時的速度，素材設定不會影響輸出時的原始素材。  

原因是素材的設定會暫存在`.temp`的目錄底下，系統會自動為他計算雜湊值並以雜湊值作檔案名稱，預設不會自動從`.temp`轉移與記錄在多媒體資料庫。

使用方式就是直接使用匯入的素材直接作為函式使用，例如直接依照匯入輸出。  

影像輸出的層級由「輸出」>「合成」>「軌道」>「剪輯」>「素材」>「匯入」。  

```MPDL
from .. import aabbcc as abc


abc()

export()
```  

或者可以使用「物件指定方法」一樣可以達到直接輸出的作用。

```MPDL
from .. import aabbcc as abc


abc().export()
```  

還可以設定解析度、長寬比、使用的時間長度等，`t`與`to`是不能同時使用，同時出現時優先使用`to`。

時間單位以「秒」(s)為基本，可以使用「微秒」(ms)、「秒」(s)或者hms制。

```MPDL
from .. import aabbcc as abc


abc(ss=0, t=3600,  high=1080, wide=1920)

export()
```  

如果是多個素材匯入，預設上如果不使用`sequence`的話，播放順序是以越前面的優先使用，但如果有使用`sequence`的話可以不按照順序，不過還是建議按照順序使用。  

```MPDL
from .. import aabbcc as abc

abc(sequence=2, ss=0, t=19,  high=1080, wide=1920)
abc(sequence=1, ss=20, t=29,  high=1080, wide=1920)

export()
```
如果不加上其他物件或方法，單純的輸出，此結果跟運作方式會與第二相同。

第一個輸出方式。
```
from .. import aabbcc as abc
from .. import ddeeff as edf

abc()
edf()

export()
```

第二個輸出方式。
```MPDL
from .. import aabbcc as abc
from .. import ddeeff as edf

composite()
    track()
        abc()
        edf()

export()
```

### 軌道
```MPDL
track(sequence=1, to=None)
```

「軌道」(track)在這裡比較特別，在這邊是指剪輯軟體的「軌道」(track)，也是指[FFmpeg](https://ffmpeg.org/ffmpeg.html#Detailed-description)所提到[「串流」(Stream)](https://ffmpeg.org/ffmpeg.html#Stream-selection)，用於製作影片時用於疊加使用的素材，「軌道」(track)數字越大可以優先覆蓋數字排序較小的「軌道」(track)中的影像。  

影像輸出的層級由「輸出」>「合成」>「軌道」>「剪輯」>「素材」>「匯入」。

```MPDL
from . import aaaaaa as a
from . import bbbbbb as b


composite()
    track(1)
        a(sequence=1, ss=0, t=10)
        b(sequence=2, ss=10, t=20)

    track(2)
        a(sequence=1, ss=20, t=25)
        b(sequence=2, ss=30, t=40)

export(export_movie_settings)
```

軌道`to`預設值`None`是指結束時間為無限，當然你也可以決定軌道時間長度，定義軌道長度就是定義影片長度，如果當有多個軌道但要設定時間長度要在第一個軌道定義時間長度。  

```MPDL
from . import aaaaaa as a
from . import bbbbbb as b


composite()
    track(1, to=40)
        a(sequence=1, ss=0, t=9)
        b(sequence=2, ss=10, t=19)

    track(2)
        a(sequence=1, ss=20, t=25)
        b(sequence=2, ss=30, t=39)

export(export_movie_settings)
```

因此軌道優先於軌道上的素材，當素材的長度超過軌道時間長度時，素材的時間長度會被限制在軌道內。

```MPDL
from . import cccccc as c

composite()
    track(1, to=40)
        c(sequence=1, t=90)

export(export_movie_settings)
```

### 剪輯
```
clip(sequence=1, ss=None, t=None, to=None, high=1080, wide=1920, x=0, y=0)
```
如果不打上任何參數，將以原始素材去做合成並輸出，使用上必須與素材綁定，這裡面設定的參數會影響輸出的內容。

```
from . import aaaaaa as a
from . import bbbbbb as b

composite()
    track(1, to=40)
        a.clip(sequence=1, ss=0, t=9)
        b.clip(sequence=2, ss=10, t=19)

    track(2)
        a.clip(sequence=1, ss=20, t=25)
        b.clip(sequence=2, ss=30, t=39)

export(export_movie_settings)
```

影片分割就是用於剪輯影片，一個軌道可以容下多個且重複的影片，但「禁止」(MUST NOT)在同一個軌道內時間重疊。

```
from . import aaaaaa as a
from . import bbbbbb as b

composite()
    track(1, to=40)
        a.clip(sequence=1, ss=0, t=10)
        b.clip(sequence=2, ss=10, t=20)

    track(2)
        a.clip(sequence=1, ss=20, t=25)
        b.clip(sequence=2, ss=30, t=39)

export(export_movie_settings)
```

但可以透過2~n個軌道讓時間重疊。

```
from . import aaaaaa as a
from . import bbbbbb as b

composite()
    track(1, to=40)
        a.clip(sequence=1, ss=0, t=10)
        b.clip(sequence=2, ss=10, t=20)

    track(2)
        a.clip(sequence=1, ss=10, t=25)
        b.clip(sequence=2, ss=30, t=39)

export(export_movie_settings)
```

### 特殊效果
```MPDL
effects()
```
特殊效果是素材的一種，特效可以用的地方相當廣泛，字幕、翻譯、「解除交錯」(deinterlacing)與轉場等，可以參考[維基百科](https://zh.wikipedia.org/wiki/%E7%89%B9%E6%AE%8A%E6%95%88%E6%9E%9C)所提供的名詞。

其中特殊效果的參數依照不同的套件、模組、類別、函式與程式去使用，而套件、模組、類別、函式與程式的名稱也是依照使用去命名，並不限定只能`effects()`，不過`effects()`是內建可以運作的函式。

```MPDL
from . import bbbbbb as b

composite()
  effects(deinterlacing=True)
    b()

export()
```

使用上必須匯入，此匯入的特效必須「必須」(MUST)是Python、MPDL或者可以提供影像處理調用的套件、模組、類別、函式與程式，但與多媒體類的素材不同的是，「可」選擇是否以數位摘要或指紋的方式匯入。

```MPDL
from effects import Effects as deinterlacing
from . import bbbbbb as b


deinterlacing()

export()
```

特殊效果在這裡定義為素材，因此這裡會比較奇特，在剪輯軟體中是一個特效，不過在FFmpeg中是[濾鏡](https://ffmpeg.org/ffmpeg.html#Detailed-description)，使用濾鏡是在對FFmpeg加入參數。

- 機內特效
- 物理特效
- 光化學特效
- 數字特效
- 繪圖軟體
- 三維動畫軟體
- 合成軟體  

由於特殊效果也是素材的一種，因此在素材疊加時也是佔用一個軌道，但可以通過`def`去群組素材與特效，例如:

```MPDL

```

### 合成
```
composite()
```

所謂的合成，如果以剪輯軟體就是將所有軌道畫面疊加起來所完成最終的結果，那FFmpeg則是濾鏡，透過指定的濾鏡將不同的串流編碼輸出。

### 輸出
```
export()
```
將最終的影片輸出，可以選擇輸出的格式、大小、容器、影片長度、比例與解析度等。


## 運算
### 布林運算
```
True
False
```

### 數學運算
```
+
-
*
/
```

### 比較運算
```
>=
<=
>
<
```

## 流程控制
```
if 1 == 1:
    track()

elif 1 > 2:
    track()

else:
    track()
```

## 迴圈
### while迴圈

```
while True:
    track()
```

### for迴圈
```
for x in xlist:
    track(x)
```

## 函式
```def```
是函式也是群組的功能。

# 參考文獻
[1] [Yves Lin，2015/5/27，Scrum 不包生導入指南，Scrum入門簡介。](https://funevo.com/2015/05/27/scrum-beginner-introduce-guide-dao-ru-zhi-nan/)  
[2] [Yves Lin，2015/6/27，Scrum 懶人包 – 10分鐘讀懂 Scrum Agile 敏捷軟體開發專案入門（含中文英文名詞對照），Scrum入門簡介。](https://funevo.com/2015/06/27/scrum-agile-project-management-software-development/)  
[3] [Yves Lin，2015/6/6，雞犬升天 – Scrum適合所有人嗎？，敏捷開發求生指南。](https://funevo.com/2015/06/06/scrum-shi-he-shui-for-who/)  
[4] [維基媒體基金會，2019/8/11，Scrum，維基媒體基金會。](https://zh.wikipedia.org/wiki/Scrum)  
[5] [維基媒體基金會，2019/7/21，敏捷軟體開發，維基媒體基金會。](https://zh.wikipedia.org/wiki/%E6%95%8F%E6%8D%B7%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91)  
[6] [維基媒體基金會，2018/1/10，燃盡圖，維基媒體基金會。](https://zh.wikipedia.org/wiki/%E7%87%83%E5%B0%BD%E5%9B%BE)  
[7] [維基媒體基金會，2019/7/24，掙值管理，維基媒體基金會。](https://zh.wikipedia.org/wiki/%E6%8C%A3%E5%80%BC%E7%AE%A1%E7%90%86)  
[] [2019, Amazon Web Services, Inc.，什麼是 DevOps？，2019, Amazon Web Services, Inc.。](https://aws.amazon.com/tw/devops/what-is-devops/)  
[] [維基媒體基金會，2018/11/30，DevOps，維基媒體基金會。](https://zh.wikipedia.org/zh-tw/DevOps)  
[] [Miles，2016-12-01，什麼是 DevOps ？，CI 從入門到入坑，電週文化事業股份有限公司。](https://ithelp.ithome.com.tw/articles/10184557)  
[] [王立恒，2015/6/23，為什麼會出現DevOps？，電週文化事業股份有限公司。](https://www.ithome.com.tw/news/96861)  
[] [David Ko，David Ko的學習之旅
，Devops 常見的迷思，PIXNET](https://kojenchieh.pixnet.net/blog/post/434643017)  
[] [2019 Microsoft，什麼是 DevOps？，2019 Microsoft。](https://azure.microsoft.com/zh-tw/overview/what-is-devops/)  
[] [Miles，2016/12/2，還記得第一次寫程式嗎？，CI 從入門到入坑，電週文化事業股份有限公司。](https://ithelp.ithome.com.tw/articles/10184841)  
[] [DevOpsDay](https://devopsdays.tw/)  
[] [Bear熊
，2017/5/3，什麼是 CI / CD ?，Medium。](https://medium.com/@william456821/%E4%BB%80%E9%BA%BC%E6%98%AF-ci-cd-72bd5ae571f1)  
[] [山姆鍋，2013/10/8，山姆鍋對持續整合、持續部署、持續交付的定義，software-development，samkuo。](https://samkuo.me/post/2013/10/continuous-integration-deployment-delivery/)  
[] [Adobe Premiere pro中英文功能表對照](https://sites.google.com/site/hkdigitalarts/home/engtocht/premiere)

# 中音對照表、專有名詞對照
名詞解釋

素材
- MPDL:素材
- 剪輯軟體:素材
- FFmpeg:串流

特殊效果
- MPDL:特效
- 剪輯軟體:特效
- FFmpeg:濾鏡，不過在FFmpeg中濾鏡是參數

合成
- MPDL:合成
- 剪輯軟體:合成
- FFmpeg:編碼

視訊轉換:在剪輯上為了加速剪輯軟體在即時預覽上的速度將素材降低品質以加速運轉。
- MPDL:視訊轉換
- 剪輯軟體:視訊轉換
- FFmpeg:解碼

特效是一個獨立的素材，目前我理解在FFmpeg是濾鏡，針對不同的素材(FFmpeg:串流)進行處理，而聲音也是素材的一種。

目前我是這樣理解的，不過還要再驗證，因為可能我理解錯誤。
