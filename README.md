「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)
===
「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)是將多媒體經由素材、規劃與處理三項元素融合製作而成，但以程式腳本的方式描述多媒體產生的方式。

核心
===
MPDL是將 **多媒體** 、 **敏捷軟體開發宣言** 、 **版本控制** 與 **敏捷軟體開發解決方案** 融合的語言，也就是將「多媒體」(Multimedia)、「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)、Git版本控制、「開發與運維」(DevOps, Development Operations)、「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)等多種技術融合，此語言是為了達到創新融合各項技術的「多媒體製作解決方案」，達到多媒體可以不斷的製作、修正的循環，以下依序講解所提到的專有名詞並最後講解如何融合。  

## 多媒體
「多媒體」(Multimedia)一詞出現在 1950 年代，由於每個時代的環境不同，所以對於多媒體的解釋也有些許差別。  
多媒體從字面上來看，就是「多」(Multi)和「媒體」(Media)的結合。  

其中「媒體」(medium)一詞來自於拉丁文「medius」一字，為「中介的」、「中間的」意思。韋伯字典中「medium」一詞之義為「立於中間或中介的某種東西」。因此，人與人之間所賴以溝通的觀念、思想或意見的中介物便可稱之為媒體。  

媒體是一種傳播資訊的媒介，所以多媒體最基本的解釋應該是「結合多種傳播資訊媒介的媒體」，而「多」媒體的「多」字，包含的媒體如文字(text)、圖片(picture)、圖形(graphic)、影像(image)、影片(video)、動畫(animation)、音樂(music)、聲音(sound)等[3]。  

## 敏捷軟體開發宣言
「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)

### 核心
藉著親自並協助他人進行軟體開發，我們正致力於發掘更優良的軟體開發方法。透過這樣的努力，我們已建立以下價值觀:  
- **個人與互動** 重於 流程與工具  
- **可用的軟體** 重於 詳盡的文件  
- **與客戶合作** 重於 合約協商  
- **回應變化** 重於 遵循計劃  

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

## Git版本控制
Git版本控制

## 敏捷軟體開發解決方案
「開發與運維」(DevOps, Development Operations)、「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)

### 開發與運維
「開發與運維」(DevOps, Development Operations)

### 持續整合與持續發佈
「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)

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
    - 販賣
    - 授權  
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
    - 語音自動翻譯
    - 語音自動產生字幕  
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
==
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
