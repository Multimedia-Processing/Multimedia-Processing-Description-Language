「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)
===
「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)是為了實現 **「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)** 的製作模式，將多媒體處理方式劃分成素材、規劃與處理三項元素融合製作而成，但以程式腳本的方式描述多媒體產生的方式。

核心
===
MPDL是為了實現將 **多媒體** 、 **敏捷軟體開發宣言** 、 **分散式版本控制** 與 **敏捷軟體開發解決方案** 融合的語言，也就是將 **「多媒體」(Multimedia)** 、 **「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)** 、**Scrum**、 **Git版本控制** 、 **「開發與運維」(DevOps, Development Operations)** 、 **「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)** 等多種概念與技術融合，為了達到創新融合各項技術的「多媒體製作解決方案」，達到多媒體可以不斷的製作、修正的循環，以下依序講解所提到的專有名詞並最後講解如何融合。  

## 多媒體
「多媒體」(Multimedia)一詞出現在 1950 年代，由於每個時代的環境不同，所以對於多媒體的解釋也有些許差別。  
多媒體從字面上來看，就是「多」(Multi)和「媒體」(Media)的結合。  

其中「媒體」(medium)一詞來自於拉丁文「medius」一字，為「中介的」、「中間的」意思。韋伯字典中「medium」一詞之義為「立於中間或中介的某種東西」。因此，人與人之間所賴以溝通的觀念、思想或意見的中介物便可稱之為媒體。  

媒體是一種傳播資訊的媒介，所以多媒體最基本的解釋應該是「結合多種傳播資訊媒介的媒體」，而「多」媒體的「多」字，包含的「媒體如文字」(text)、「圖片」(picture)、「圖形」(graphic)、「影像」(image)、「影片」(video)、「動畫」(animation)、「音樂」(music)、「聲音」(sound)等[3]。  

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

## 敏捷軟體開發解決方案
隨著「敏捷軟體開發宣言」的發佈後的興起與流傳，其中符合「敏捷軟體開發宣言」的Scrum模式因為易學簡單而快速流通，軟體開發的文化也持續改變。  

雖然「開發」得以解決，但卻在「運維」這方面遇到了卡關，因為大多公司賣的不是軟體而是軟體產生的服務，使得系統在開發、更新與安全、可靠性上遇到了衝突，因此整體系統的開發、測試、維護便成為三方面的衝突與隔閡。  

因此有人提出了「開發與運維」(DevOps, Development Operations)這項概念，透過文化、實務與工具來解決三方的隔閡，達到程式開發的快速迭代、更新與自動化，目前Microsoft、GitHub、GitLab與Google等著名的大型企業都在運作的模式，並且世界各地也持續舉辦DevOpsDay[?]。  

### Scrum
有人於1990年左右提出提出了Scrum，核心思想就是「全體一起前進，把求傳來傳去」，其中的概念來自於橄欖球，橄欖球中不同的角色與職位在各階段的互相重疊完成。  

此方式將過去「瀑布式開發流程」:需求規格、系統分析、系統設計、實作、測試、部署與維護，必須依照這個開發，當有問題時就會往後一步驟重新來，瀑布式開發流程造成開發過程無法快速應變需求與改變，在Scrum的概念出現後狀況得以改變，這個想法也剛好很符合「敏敏捷軟體開發宣言」所提到的訴求與想法。  

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

##### 任務
「任務」(Task)是「開發團隊」(Dev Team, Development Team)針對物件所列出的任務;任務的分配是開發團隊自己分配的。  

##### 產品待辦清單
「產品待辦清單」(Product Backlog)是專案的文檔，大概的描述內容、產生的東西、特性、概念等。  

內容產品負責人負責調整、製作，以「項目」(Item)為單位，製作的時間長度以天為單位，順序由上而下。

##### 衝刺待辦清單
「衝刺待辦清單」(Sprint Backlog)是「開發團隊」向產品負責人承諾這個「衝刺」(Sprint)會盡力完成的「項目列表」(Item List)，以「任務」(Task)為單位，時間以小時為單位，並在16小時內完成，超過就會再分解。  

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
- 自動化程序:「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)、「管道」(Pipelines)、虛擬機器、容器技術、無伺服器運算與微型服務等。

大致講解兩項，「工作流程看板」(Boards)、「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)。

### 工作流程看板
「工作流程看板」(Boards)

### 持續整合與持續發佈
「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)是為了可以達到專注開發與運作維護所設計的工具，利用多項的技術與工具達到靜態檢查、動態檢查、修改項目、風格化檢查、除錯等。  

「持續整合」(CI, Continuous Integration)是針對Git的每一次的提交、拉請求、系統變動，能夠持續且自動地進行驗證。意思就是將開發環境、修改項目、靜態檢查、動態檢查、風格化檢查與相依性檢查等不斷的整合，達到最佳的工作流程，減少人力參與，達到專注、快速與減少錯誤。  

持續發佈就是在上述都達到與通過後，自動化的發佈不同版本、平台與系統，讓人們在使用上可以有一定的程度上有品質。

因此在DevOps與CI/CD的融合與貫通，達到了現在可以達到敏捷軟體開發宣言，從而減少開發週期並因應需求

## 融合
將上述技術做融合，已達到新的多媒體製作解決方案。

語法概念
===
語法靈感來自Python，因此如果熟悉Python會輕鬆使用，三項元素分別是:

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
    ...

2. 處理  
  多媒體經過處理產生影片，如下常見處理方式:
    - 剪輯
    - 特效
    - 合成
    - 字幕
    - 轉場  
    - 翻譯
    - 字幕  
    ...

語法
===
## 匯入素材、特效、合成
匯入素材的方式必須以SHA3或SHA2先將數位檔案經過雜湊後產生對應的數位指紋來對應所要的素材，會有一個檔案紀錄雜湊值對應的檔案，名稱不限制。
```
from .file.directory import hash_vlue as vlase
import hash_vlue
```

目錄匯入設定
- `file_directory/` = `file_directory`
- `file_directory/file_directory/` = `file_directory.file_directory`
- `./file_directory/` = `.file_directory`  
- `./file_directory/file_directory` = `.file_directory.file_directory`  
- `../file_directory` = `..file_directory`
- `../file_directory/file_directory` = `..file_directory.file_directory`


## 軌道
定義軌道，
```
track(sequence):
    track()
```
## 素材設定
```
clip()
```

## 特效
```
effects()
```

## 合成
```
composite()
```

## 輸出
```
export(export_movie_settings)
```

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

參考文獻
===
[1][a](https://funevo.com/2015/05/27/scrum-beginner-introduce-guide-dao-ru-zhi-nan/)  
https://tuna.to/agile-2-73856205bc9e  
https://funevo.com/2015/06/06/scrum-shi-he-shui-for-who/  
https://zh.wikipedia.org/wiki/Scrum  
https://zh.wikipedia.org/wiki/%E6%95%8F%E6%8D%B7%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91  
https://zh.wikipedia.org/wiki/%E7%87%83%E5%B0%BD%E5%9B%BE  
https://zh.wikipedia.org/wiki/%E6%8C%A3%E5%80%BC%E7%AE%A1%E7%90%86  
https://aws.amazon.com/tw/devops/what-is-devops/  
https://zh.m.wikipedia.org/zh-tw/DevOps  
https://ithelp.ithome.com.tw/m/articles/10184557  
https://www.ithome.com.tw/news/96861  
https://kojenchieh.pixnet.net/blog/post/434643017  
https://azure.microsoft.com/zh-tw/overview/what-is-devops/  
https://ithelp.ithome.com.tw/m/articles/10184841  
https://devopsdays.tw/  
