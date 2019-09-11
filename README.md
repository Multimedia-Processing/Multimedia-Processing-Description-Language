「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)
===
「多媒體處理描述語言」(MPDL, Multimedia Processing Description Language)是將多媒體經由素材、規劃與處理三項元素融合製作而成，但以程式腳本的方式描述多媒體產生的方式。

核心
===
MPDL是將 **多媒體** 、 **敏捷軟體開發宣言** 、**版本控制** 與 **敏捷軟體開發解決方案** 融合的語言，也就是將「多媒體」(Multimedia)、「[敏捷軟體開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)」(Manifesto for Agile Software Development)、Git版本控制、「開發與運維」(DevOps, Development Operations)、「持續整合與持續發佈」(CI/CD, Continuous Integration / Continuous Delivery)等多種技術融合，此語言是為了達到所融合的技術，也就此語言是創新的多媒體解決方案，達到多媒體可以不斷的製作、修正這兩個裡面循環，以下依序講解所提到的專有名詞並最後講解如何融合。  

## 多媒體

## 敏捷軟體開發宣言
### 核心
**個人與互動** 重於 流程與工具  
**可用的軟體** 重於 詳盡的文件  
**與客戶合作** 重於 合約協商 
**回應變化** 重於 遵循計劃  

### 原則

## 融合

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
