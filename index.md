<center>
    <h1 style="font-size:40px;font-weight:bold;">雪霸國家公園</h1></center>
<p>

    <style>
        html {
            height: 100%;
        }
        
        body {
            background-image: url("https://png.pngtree.com/thumb_back/fw800/back_pic/04/08/98/405814a2ba920b1.jpg");
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            background-size: cover;
        }
        
        p {
            font-size: 18px;
            font-family: Microsoft JhengHei;
        }
        
        h2 {
            font-family: "微軟正黑體";
            font-weight: bold;
        }
        
        td {
            font-family: "微軟正黑體";
            font-size: 18px;
        }
        
        .button {
            background-color: #a0fdff;
            border: 2px solid black;
            color: ;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            display: block;
        }
        
        .button:hover {
            background-color: #A1D0FF;
        }
        
        #flip {
            background-color: #a0fdff;
            border: 2px solid black;
            color: black;
            padding: 15px 50px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            display: block;
        }
        
        .button-bar {
            position: fixed;
            top: 1%;
            right: 5%;
        }
        
        .flip-box {
            background-color: transparent;
            width: 300px;
            height: 200px;
            border: 1px solid #f1f1f1;
            perspective: 1000px;
        }
        
        .flip-box-inner {
            position: relative;
            width: 100%;
            height: 100%;
            text-align: center;
            transition: transform 0.8s;
            transform-style: preserve-3d;
        }
        
        .flip-box:hover .flip-box-inner {
            transform: rotateY(180deg);
        }
        
        .flip-box-front,
        .flip-box-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
        }
        
        .flip-box-front {
            background-color: #bbb;
            color: black;
        }
        
        .flip-box-back {
            background-color: dodgerblue;
            color: white;
            transform: rotateY(180deg);
        }
    </style>

    <html>

    <head>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
        <script>
            $(document).ready(function() {
                $('#top').click(function() {
                    $('html, body').animate({
                        scrollTop: 0
                    }, 1000);
                });
                $('#bottom').click(function() {
                    $('html, body').animate({
                        scrollTop: $(document).height() - $(window).height()
                    }, 1000);
                });
                $('#a').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#A").offset().top
                    }, 1000);
                });
                $('#b').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#B").offset().top
                    }, 1000);
                });
                $('#c').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#C").offset().top
                    }, 1000);
                });
                $('#d').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#D").offset().top
                    }, 1000);
                });
                $('#e').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#E").offset().top
                    }, 1000);
                });
                $('#f').click(function() {
                    $('html, body').animate({
                        scrollTop: $("#F").offset().top
                    }, 1000);
                });
                $("#flip").click(function() {
                    $(".button").slideToggle("slow");
                });
            });
        </script>
    </head>

    <h2 class="header-level-2" id="A">基本資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <ol>
            <li>
                <p>建立時間 : 1992 年7 月1 日 </p>
            </li>
            <li>
                <p>面積大小 : 769 平方公里 </p>
            </li>
            <li>
                <p>地理位置 : 從北邊的樂山到邊吉岩山之稜線為界，到南邊的宇羅尾山和大甲溪中游
                </p>
            </li>
        </ol>
    </div>

    <h2 class="header-level-2" id="B">國家公園標示意涵:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <img align="left" style="width: 100px; height: 100px;" src="https://www.spnp.gov.tw/Content/image/logo-round.png" data-type="image">
        <center>
            <p>
                <p>山岳表示以雪山及大霸尖山為代表的山岳型國家公園；蜿蜒連綿的 綠水取源遠流長的意義；櫻花鉤吻鮭則是突顯出國家公園生態保育的 重責大任；而青山綠水是環保的理想園地，亦顯現國家公園百年大計的事業。
                </p>
            </p>
        </center>
    </div>

    <h2 class="header-level-2" id="C">公園特色介紹:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

        <p>1.地質地形:大霸尖山是雪霸國家公園最重要的兩座山之一。大霸尖山的形狀很特殊，好像一個很大的岩石酒桶，這個岩石酒桶是變質砂岩所構成，山頂則以厚層變質砂岩為主，此層即白冷層頂部的青山段砂岩。在大霸頂部的砂岩層其位態近乎水平，主要是因此岩層恰位於雪霸背斜的軸部位置;而大霸尖山山形呈桶狀之原因，主要受砂岩中節理的發育所控制，於地層平緩疊置之箱型背斜軸部發育形成。</p>

        <p>2.動物資源:</p>
        <p>鳥類:冠羽畫眉為園區內常見的特有種鳥類，全區已紀錄有154種鳥類，包括台灣山鷓鴣、黑長尾雉、台灣噪眉、冠羽畫眉、台灣叢樹鶯等台灣特有種。</p>
        <p>魚類:在大安溪系、大甲溪系、蘭陽溪系、德基水庫等地共調查發現了17種魚類。大甲溪是台灣魚類分布的海拔最高點，一般溪魚分布的上限約為1,800公尺，分布於大甲溪上游的櫻花鉤吻鮭則可達1,800公尺以上。台灣石賓、台灣間爬岩鰍、櫻花鉤吻鮭、台灣纓口鰍、明潭吻蝦虎魚、短吻紅斑蝦虎魚為已紀錄到的台灣特有種。</p>
        <p>哺乳動物:園區的哺乳動物共紀錄58種，大型的有台灣黑熊、台灣野山羊、台灣野豬、台灣水鹿；中型的有台灣獼猴、山羌、石虎、白鼻心；小型的則有穿山甲、食蟹獴、鼬獾、黃喉貂、各種鼠類及蝙蝠。其中，台灣黑熊為野生動物保育法所列瀕臨絕種保育類動物，台灣水鹿在野外的族群量亦極低，台灣野山羊亦屬珍貴稀有保育類動物</p>
        <p>3.植物資源:大多屬於東亞植物地區之特有屬，推測其於冰河時期並未受北方大陸冰河蔓延之破壞，使大霸尖山、雪山稜線附近高山留存了許多地質年代以來的孑遺植物，如自第三紀上新世(距今約180萬年)留存至今的臺灣檫樹，主要產於園內的大鹿林道、大雪山林道、雪見等地區，而檫樹屬植物全世界僅有三種，分別產於北美、大陸及臺灣，故有其特殊之學術地位。</p>
        <p>4.人文資源:雪見鄰近地區具有十分豐富薈萃的人文史蹟資源。其原住民文化主要為泰雅族之北勢群，分布於大安溪中游兩岸。雪見地區瀰漫著濃厚的文化特色，其中以北坑溪古道最具盛名，原為大甲溪泰雅族原住民遷移遊獵的山徑，古道中泰雅族原住民及日治時期所遺留下來的歷史事件與遺址，是瞭解日治時期竹苗地區樟腦採集與理蕃政策的最佳地點。</p>

        <body>

            <div class="flip-box">
                <div class="flip-box-inner">
                    <div class="flip-box-front">
                        <img style="width:300px;height:200px" src="https://image.cache.storm.mg/styles/smg-800x533-fp/s3/media/image/2019/03/15/20190315-055241_U9180_M506085_b5ed.jpg?itok=OXKypYWw" title="櫻花鉤吻鮭">
                    </div>
                    <div class="flip-box-back">
                        <img style="width:300px;height:200px" src="http://np.cpami.gov.tw/images/com_fwgallery/files/516/Photo_V6Y9E.jpg" title="冠羽畫眉" title="冠羽畫眉">
                    </div>
                </div>
            </div>

            <div class="flip-box">
                <div class="flip-box-inner">
                    <div class="flip-box-front">
                        <img style="width:300px;height:200px" src="http://www.herpera.com/images/fcivet3.jpg" title="白鼻心">
                    </div>
                    <div class="flip-box-back">
                        <img style="width:300px;height:200px" src="https://s.yimg.com/ny/api/res/1.2/A7zq9ob.LdgorO1dwZYqow--~A/YXBwaWQ9aGlnaGxhbmRlcjtzbT0xO3c9NzAzO2g9NTcx/http://media.zenfs.com/en/homerun/feed_manager_auto_publish_494/5409c727781755e0bbe35d393696ee13" title="台灣獼猴">
                    </div>
                </div>
            </div>

    </div>

    </div>

    <h2 class="header-level-2" id="D">交通資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="20%">客運公司 </th>
                        <th width="55%"> 路程</th>

                        <th width="25%">聯絡電話</th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>國光客運</td>
                        <td>宜蘭 → 武陵農場 07:00、12:40 武陵農場 → 宜蘭 09:20、14:05</td>

                        <td>(08)0001-0138</td>
                    </tr>

                    <tr>
                        <td>豐原客運台中</td>
                        <td>來: 台中--梨山 08:00 梨山--武陵 16:00 回: 武陵--梨山--台中6:30-14:30</td>

                        <td>(04) 2523-4175 #228 </td>
                    </tr>

                </tbody>
            </table>
        </p>

    </div>

    <h2 class="header-level-2" id="E">住宿資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="31%">名稱 </th>
                        <th width="48%">地址 </th>
                        <th width="18%">聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>雪霸休閒農場</td>
                        <td>新竹縣五峰鄉桃山村民石380號</td>
                        <td>(03)585-6192</td>
                    </tr>

                    <tr>
                        <td>觀霧加草雪霸休閒農場　</td>
                        <td>新竹縣五峰鄉桃山村民石365號</td>
                        <td>(09)1209-8508</td>
                    </tr>

                    <tr>
                        <td>錦水溫泉飯店</td>
                        <td>苗栗縣泰安鄉錦水村橫龍山72號</td>
                        <td>(03)794-1333</td>
                    </tr>

                    <tr>
                        <td>愛上喜翁民宿</td>
                        <td>新竹縣五峰鄉竹林村4鄰忠興93號</td>
                        <td>(09)2125-4250</td>
                    </tr>

                </tbody>
            </table>
        </p>
    </div>

    <h2 class="header-level-2" id="F">美食資訊:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

        <p>
            <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="31%">店名</th>
                        <th width="48%">地址 </th>
                        <th width="18%">聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>山度窯烤麵包</td>
                        <td>苗栗縣南庄鄉蓬萊村11鄰八卦力16-8號</td>
                        <td>(09)3646-6779</td>
                    </tr>

                    <tr>
                        <td>南庄抹茶冰</td>
                        <td>苗栗縣南庄鄉文化路6號</td>
                        <td>(09)3340-2346</td>
                    </tr>

                    <tr>
                        <td>向天湖738文創餐坊</td>
                        <td>台灣南庄鄉東河村16鄰向天湖25號</td>
                        <td>(03)782-3922</td>
                    </tr>

                    <tr>
                        <td>坪溪河畔咖啡屋</td>
                        <td>台灣竹東鎮瑞峰里1鄰5之8號</td>
                        <td>(03)594-9063</td>
                    </tr>

                </tbody>
            </table>
        </p>

    </div>

    <h2 class="header-level-2">資料來源:</h2>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <ul>
            <li><a href="http://np.cpami.gov.tw/">台灣國家公園</a></li>
            <br>
            <li><a href="https://www.spnp.gov.tw/Site/Conservation">雪霸國家公園</a></li>
            <br>
            <li><a href="https://www.tripadvisor.com.tw/Restaurant_Review-g13808870-d7890852-Reviews-It_s_Alice_Cafe_Food-Zhudong_Hsinchu_County.html"> tripadvisor</a></li>
            <br>
            <li><a href="https://www.booking.com/searchresults.zh-tw.html?aid=359627;label=a-no-xdKAxEc2lFYkNsZg1VPVOQS308735400373%3Apl%3Ata%3Ap1%3Ap2%3Aac%3Aap1t1%3Aneg%3Afi%3Atiaud-297601666995%3Akwd-610371119756%3Alp1012825%3Ali%3Adec%3Adm;sid=fabd237e6184d11bf9506341efb96361;city=-287493;hyb_red=1;keep_landing=1;redirected=1;redirected_from_city=1;source=city;src=city&gclid=EAIaIQobChMI_cKn0tyI4gIVTQUqCh2JsgN6EAAYASAAEgKp5_D_BwE&">Booking.com</a></li>
        </ul>
    </div>

    <div class="button-bar">
        <a id="flip">選單</a>
        <a class="button" id="a" href="#">基本資訊</a>
        <a class="button" id="b" href="#">標示意涵</a>
        <a class="button" id="c" href="#">特色介紹</a>
        <a class="button" id="d" href="#">交通資訊</a>
        <a class="button" id="e" href="#">住宿資訊</a>
        <a class="button" id="f" href="#">美食資訊</a>
        <a class="button" id="top" href="#">回頂端</a>
        <a class="button" id="bottom" href="#">回底部</a>
        <a class="button" id="home" href="#">返回主頁</a>
    </div>

    </html>

