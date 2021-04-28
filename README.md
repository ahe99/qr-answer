# QRanswer

課程專案
掃描(紙本)QR code會進入英文單字介紹頁面, 主要設計給手機端
Vue單頁模板、基於webRTC的instascan.js在前端完成掃描QR code

[---> LINK <---](https://ahe99.github.io/QRanswer/#Apple)

> 在json裡找到單字的engName
>
> `https://ahe99.github.io/QRanswer/#engName`
>
> 修改上面engName丟進[QRcode產生器](http://www.quickmark.com.tw/cht/qrcode-datamatrix-generator/default.asp?qrLink), 並印出來作為單字卡

---

新增資料如:

* 新增圖片至`assets\img`副檔名限制`.jpg` ex.`dog.jpg`

* 新增音訊至`assets\audio`副檔名限制`.mp3` ex.`dog.mp3`

* 開啟`data.json`

        {
            "answers": [
                {
                    "name": "貓咪",
                    "engName":"cat",
                    "description": "喵喵！",
                }
            ]
        }

* 更改`data.json`如下

        {
            "answers": [
                {
                    "name": "貓咪",
                    "engName":"cat",
                    "description": "喵喵！",
                },
                {
                    "name": "狗狗",
                    "engName":"dog",
                    "description": "旺旺！",
                }
            ]
        }

* 發PR
