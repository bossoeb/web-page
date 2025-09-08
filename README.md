<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的第一個網頁</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
        }
        .left-half {
            background-color: rgb(15, 92, 101);
            width: 25%;
            height: 100%;
        }
        .right-half {
            background-color: rgb(255, 255, 255);
            width: 75%; /*調整右側寬度*/
            height: 100%; /*調整右側高度*/
        }
        .content {
            position: absolute;
            top: 30%; /*高度*/
            left: 60%; /*寬度*/
            transform: translate(-50%, -50%);
            color: black; /*文字顏色*/
            text-align: center;
            font-size: 24px; /*調整文字大小*/
            max-width: 900px; /*限制文字寬度*/
        }
        .content2 {
            position: absolute;
            top: 20%; /*高度*/
            left: 12%; /*寬度*/
            transform: translate(-50%, -50%);
            color: rgb(255, 247, 98); /*文字顏色*/
            text-align: center;
            font-size: 26px; /*調整文字大小*/
            max-width: 200px; /*限制文字寬度*/
        }
        .content3 {
            position: absolute;
            top: 20%; /*高度*/
            left: 70%; /*寬度*/
            transform: translate(-50%, -50%);
            color: rgb(255, 247, 98); /*文字顏色*/
            text-align: center;
            font-size: 26px; /*調整文字大小*/
            max-width: 200px; /*限制文字寬度*/
        }
        .button-container {
            position: absolute; /*按鈕位置*/
            bottom: 50%; /*高度*/
            right: 85%; /*寬度*/
        }
        .button-container .button {
            background-color: rgb(15, 92, 101); /*按鈕背景顏色*/
            color: rgb(255, 200, 0); /*按鈕文字顏色*/
            border: none; /*按鈕邊框透明*/
            padding: 10px 20px;
            font-size: 16px; /*按鈕文字大小*/
            cursor: pointer; /*滑鼠指標變成手型*/
            margin: 5px; /*按鈕間距*/
        }
        .button-container .button:hover {
            color: rgb(255, 200, 0); /*滑鼠懸停時的文字顏色*/
        }
        .button-container1 {
            position: absolute; /*按鈕位置*/
            bottom: 44%; /*高度*/
            right: 85%; /*寬度*/
        }
        .button-container1 .button {
            background-color: rgb(15, 92, 101); /*按鈕背景顏色*/
            color: white; /*按鈕文字顏色*/
            border: none; /*按鈕邊框透明*/
            padding: 10px 20px;
            font-size: 16px; /*按鈕文字大小*/
            cursor: pointer; /*滑鼠指標變成手型*/
            margin: 5px; /*按鈕間距*/
        }
        .button-container1 .button:hover {
            color: rgb(255, 200, 0); /*滑鼠懸停時的文字顏色*/
        }
        .button-container2 {
            position: absolute; /*按鈕位置*/
            bottom: 38%; /*高度*/
            right: 85%; /*寬度*/
        }
        .button-container2 .button {
            background-color: rgb(15, 92, 101); /*按鈕背景顏色*/
            color: rgb(255, 255, 255); /*按鈕文字顏色*/
            border: none; /*按鈕邊框透明*/
            padding: 10px 20px;
            font-size: 16px; /*按鈕文字大小*/
            cursor: pointer; /*滑鼠指標變成手型*/
            margin: 5px; /*按鈕間距*/
        }
        .button-container2 .button:hover {
            color: rgb(255, 200, 0); /*滑鼠懸停時的文字顏色*/
        }
        .button-container3 {
            position: absolute; /*按鈕位置*/
            bottom: 32%; /*高度*/
            right: 85%; /*寬度*/
        }
        .button-container3 .button {
            background-color: rgb(15, 92, 101); /*按鈕背景顏色*/
            color: white; /*按鈕文字顏色*/
            border: none;
            padding: 10px 20px;
            font-size: 16px; /*按鈕文字大小*/
            cursor: pointer; /*滑鼠指標變成手型*/
            margin: 5px; /*按鈕間距*/
        }
        .button-container3 .button:hover {
            color: rgb(255, 200, 0); /*滑鼠懸停時的文字顏色*/
        }
    </style>
</head>
<body>
     <div class="left-half"></div>
     <div class="right-half"></div>
     <div class="content">
        <h1>歡迎來到成員介紹</h1>
        <p>這裡是介紹家族成員的地方</p>
     </div>
     <div class="content2">
        <h2>這是第二個內容</h2>
        <p>這是第二個內容的描述</p>
    </div>
    <div class="content3">
        <h2>這是第三個內容</h2>
        <p>這是第三個內容的描述</p>
    </div>
    <div class="button-container">
        <a href="1-1.html">
            <button class="button">首頁</button>
        </a>
    </div>
    <div class="button-container1">
        <a href="1-2.html">
            <button class="button">家族</button>
        </a>
    </div>
    <div class="button-container2">
        <a href="1-3.html">
            <button class="button">成員</button>
        </a>
    </div>
    <div class="button-container3">
        <a href="1-4.html">
            <button class="button">幹部</button>
        </a>
    </div>
</body>
</html>

