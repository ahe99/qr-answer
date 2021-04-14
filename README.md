# QRanswer

課程專案
掃描紙本QR code會進入此頁面, 主要設計給手機端

[---> LINK <---](https://ahe99.github.io/QRanswer)

> 在json裡找到單字的engName
> `https://ahe99.github.io/QRanswer/#engName`
> 修改上面engName丟進[QRcode產生器](http://www.quickmark.com.tw/cht/qrcode-datamatrix-generator/default.asp?qrLink), 並印出來作為單字卡

---

新增資料如:

* 新增圖片至`assets\img`

* 新增音訊至`assets\audio`

* 開啟`data.json`

        {
            "answers": [
                {
                    "name": "貓咪",
                    "engName":"Cat",
                    "description": "我是喵喵！",
                    "image":"cat.jpg",
                    "audio":"cat.mp3"
                }
            ]
        }

* 更改`data.json`如下

        {
            "answers": [
                {
                    "name": "貓咪",
                    "engName":"Cat",
                    "description": "我是喵喵！",
                    "image":"cat.jpg",
                    "audio":"cat.mp3"
                },
                {
                    "name": "狗狗",
                    "engName":"Dog",
                    "description": "我是旺旺！",
                    "image":"dog.jpg",
                    "audio":"dog.mp3"
                }
            ]
        }

* 發PR
