# QRanswer

課程專案
掃描紙本QR code會進入此頁面, 主要設計給手機端

[---> LINK <---](https://ahe99.github.io/QRanswer)

要新增資料如:

* 新增圖片至`assets\img`

* 新增音訊至`assets\audio`

* 開啟`data.json`

        {
            "answers": [
                {
                    "name": "貓",
                    "desciption": "我是喵喵！",
                    "image":"cat.jpg",
                    "audio":"cat.mp3"
                }
            ]
        }

* 更改`data.json`如下

        {
            "answers": [
                {
                    "name": "貓",
                    "desciption": "我是喵喵！",
                    "image":"cat.jpg",
                    "audio":"cat.mp3"
                },
                {
                    "name": "狗",
                    "desciption": "我是旺旺！",
                    "image":"dog.jpg",
                    "audio":"dog.mp3"
                }
            ]
        }
