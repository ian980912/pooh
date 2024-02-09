<!DOCTYPE html>
<html>
    <head>
        <meta charser="UTF-8-sig"></meta>
        <meta name="description" content="蜂蜜相關網站" />
        <meta name="author" content="陳米奇" />
        <meta name="keywords" content="蜂蜜, 米奇, 小熊維尼" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>mic0725</title>
    </head>
    <body>
        <style>
            .top {
                width: 50%;
                margin: 20px 0 0 0;
            }
            .low {
                width: 50%;
                margin: 15px 0 0 0;
            }

            .custom-link {
            width: 300px;  /* 或使用 max-width: 300px; */
            display: inline-block;  /* 讓連結以區塊元素方式顯示，從而能夠設定寬度 */
            text-decoration: none;  /* 移除連結的底線 */
            padding: 10px;  /* 可選：添加內邊距以增加點擊區域 */
            border: 1px solid #ccc;  /* 可選：添加邊框效果 */
            margin: 5px;  /* 可選：添加外邊距以控制連結之間的間距 */
            }
            .subscribe-button{
                color:white;
                background-color: black;
                width: 60px;
                height: 36px;
                border-radius: 18px;
                border-style: none;
                cursor: pointer;

            }
            .subscribe-button:hover{
                background-color: rgb(31, 31, 31);
            }

            .subscribe-button:active{
                background-color: rgb(61,61,61);
            }

            .thumb-button{
                color:black;
                background-color: white;
                width: 60px;
                height: 36px;
                border-radius: 18px;
                border-style: solid;
                border-color: rgb(195, 195, 195);
                border-width: 1px;
                cursor: pointer;
            }
            .thumb-button:hover{
                background-color: rgb(219, 219, 219);
            }

            .thumb-button:active{
                background-color: rgb(173,173,173);
            }
            .share-button{
                color:black;
                background-color: rgb(242, 242, 242);
                width: 60px;
                height: 36px;
                border-radius: 18px;
                border-style: none;
                cursor: pointer;

            }
            .share-button:hover{
                background-color: rgb(219, 219, 219);
            }

            .share-button:active{
                background-color: rgb(173, 173, 173);
            }

            #title{
                color:rgb(103, 189, 11);
            }
            /* 基本表格樣式 */
            table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            }

            /* 表頭樣式 */
            th {
            background-color: #f2f2f2;
            }

            /* 單數行樣式 */
            tr:nth-child(odd) {
            background-color: #f9f9f9;
            }

            /* 雙數行樣式 */
            tr:nth-child(even) {
            background-color: #ffffff;
            }

            /* 單元格樣式 */
            td, th {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
            }

            /* 鼠標懸停效果 */
            tr:hover {
            background-color: #e0e0e0;
            }
            /* 列表樣式 */
            ul, ol {
                padding: 0;
                list-style: none;
            }

            /* 無序列表樣式 */
            ul {
                background-color: #f5f5f5;
                border-radius: 10px;
                padding: 10px;
            }

            ul li {
                padding: 5px;
                margin: 5px 0;
                background-color: #ffffff;
            }

            /* 有序列表樣式 */
            ol {
                background-color: #f0f0f0;
                border-radius: 10px;
                padding: 10px;
            }

            ol li {
                padding: 5px;
                margin: 5px 0;
                background-color: #ffffff;
            }


        </style>
        <!-- 影片標題用h1標籤 -->
        <h1 id="title">【Pooh】熊之介紹</h1>
        <!-- 頻道名稱用h2標籤 -->
        <h2>Orientationer: Mic</h2>
        <!-- 3個按鈕標籤 -->
        <button class="subscribe-button">訂閱</button>
        <button class="thumb-button">按讚</button>
        <button class="share-button">分享</button>
        <!-- 分隔線 -->
        <br/>
        <hr class = top>
        <!-- 4行文字段落 -->
        <p>
        2018年07月25日<br/>
        嗨，我是小熊維尼，一隻愛吃蜂蜜的笨熊。我住在百畝林裡，和我的朋友們一起玩耍。</br>
        我最好的朋友是跳跳虎，他比我聰明多了，所以我總是聽他的話。</br>
        我還有其他的朋友，像是小豬、屹耳、瑞比等，他們都很喜歡我，因為我很可愛，也很樂觀。</br>
        我不怕任何困難，只要有蜂蜜，我就能解決一切。我覺得你也應該多吃點蜂蜜，這樣你的頭腦才會變得像我一樣靈光。</br>
        你看起來很無聊，要不要和我一起去找蜂蜜呢？我保證你會很開心的，只要你不介意被蜜蜂叮一下下。</br>
        </p>
        <hr class = low>
        <br/>
        <!--連結&圖片--> <!--進入資料夾： {資料夾名/}, 跳出資料夾： {../} -->
        <a href="https://google.com" class="custom-link">google</a>
        <a href="IMG_058.jpeg" class="custom-link">熊圖</a>
        <br/>
        <br/>
        <img src="IMG_058.jpeg" width= "250"/>

        <!--影片-->
        <video src="123.mp4" width= "600" controls>失敗</video>
        <br/>

        <!--youtube-->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/-SwWL5xCzhM?si=RJ-Ta5W1m0_2FiaT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

        <!--列表 表格-->
        <ul>
            <li>新米</li>
            <li>米瑞</li>
            <li>新熊</li>
            <li>檸檬</li>
        </ul>
        <ol type="A">
            <li>brownies</li>
            <li>松鼠</li>
            <li>piglet</li>
            <li>tiger</li>
        </ol>

        <table width="400">
            <tr>
                <td>姓名</td>
                <td>生日</td>
                <td>年紀</td>
                <td>來自</td>
            </tr>
            <tr>
                <td>small bear</td>
                <td>02/08</td>
                <td>25</td>
                <td>富邦</td>
            </tr>
            <tr>
                <td>mic</td>
                <td>07/25</td>
                <td>5</td>
                <td>夏威夷</td>
            </tr>
        </table>
        <!--html容器 div & span--> <!--span: 寬度多少佔多少, div:直接佔一整行-->
        <div style="color: pink">
            <table width="400">
                <tr>
                    <td>姓名</td>
                    <td>生日</td>
                    <td>年紀</td>
                    <td>來自</td>
                </tr>
                <tr>
                    <td>small bear</td>
                    <td>02/08</td>
                    <td>25</td>
                    <td>富邦</td>
                </tr>
                <tr>
                    <td>mic</td>
                    <td>07/25</td>
                    <td>5</td>
                    <td>夏威夷</td>
                </tr>
            </table>
        </div>

        <input type="text" placeholder="請輸入帳號"/>
        <br/>
        <br/>
        <input type="password" placeholder="熊"/>
        <input type="date" placeholder="生日"/>
        <input type="file" placeholder="熊圖"/>
        <input type="range" placeholder="欠扁程度"/>
        
        <label>
            <input type="checkbox" class="styled-checkbox" title="是否欠扁"/>
            是否欠扁
        </label>

        <br/>
        <textarea></textarea>
    </body>
</html>
