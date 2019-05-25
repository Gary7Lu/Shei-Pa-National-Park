<html>
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
        /*button*/
        .button {
            background-color: #a0fdff;
            border: 2px solid black;
            color: ;
            padding: 8px 24px;
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
            padding: 8px 42px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
            display: block;
        }
        
        .button-bar {
            position: fixed;
            top: 5%;
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
        /*light box*/
         * {
            box-sizing: border-box
        }
        
        body {
            font-family: Verdana, sans-serif;
            margin: 0
        }
        
        .mySlides {
            display: none
        }
        
        img {
            vertical-align: middle;
        }
        /* Slideshow container */
        
        .slideshow-container {
            max-width: 1000px;
            position: relative;
            margin: auto;
        }
        /* Next & previous buttons */
        
        .prev,
        .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            padding: 16px;
            margin-top: -22px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            transition: 0.6s ease;
            border-radius: 0 3px 3px 0;
            user-select: none;
        }
        /* Position the "next button" to the right */
        
        .next {
            right: 0;
            border-radius: 3px 0 0 3px;
        }
        /* On hover, add a black background color with a little bit see-through */
        
        .prev:hover,
        .next:hover {
            background-color: rgba(0, 0, 0, 0.8);
        }
        /* Caption text */
        
        .text {
            color: #f2f2f2;
            font-size: 15px;
            padding: 8px 12px;
            position: absolute;
            bottom: 8px;
            width: 100%;
            text-align: center;
        }
        /* Number text (1/3 etc) */
        
        .numbertext {
            color: #f2f2f2;
            font-size: 12px;
            padding: 8px 12px;
            position: absolute;
            top: 0;
        }
        /* The dots/bullets/indicators */
        
        .dot {
            cursor: pointer;
            height: 15px;
            width: 15px;
            margin: 0 2px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.6s ease;
        }
        
        .active,
        .dot:hover {
            background-color: #717171;
        }
        /* Fading animation */
        
        .fade {
            -webkit-animation-name: fade;
            -webkit-animation-duration: 1.5s;
            animation-name: fade;
            animation-duration: 1.5s;
        }
        
        @-webkit-keyframes fade {
            from {
                opacity: .4
            }
            to {
                opacity: 1
            }
        }
        
        @keyframes fade {
            from {
                opacity: .4
            }
            to {
                opacity: 1
            }
        }
        /* On smaller screens, decrease text size */
        
        @media only screen and (max-width: 300px) {
            .prev,
            .next,
            .text {
                font-size: 11px
            }
        }
        
        
        /*tabs*/
     body {
        font-family: Arial;
    }
    /* Style the tab */
    
    .tab {
        overflow: hidden;
        border: 1px solid #ccc;
        background-color: #f1f1f1;
    }
    /* Style the buttons inside the tab */
    
    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 12px;
        transition: 0.3s;
        font-size: 17px;
    }
    /* Change background color of buttons on hover */
    
    .tab button:hover {
        background-color: #ddd;
    }
    /* Create an active/current tablink class */
    
    .tab button.active {
        background-color: #ccc;
    }
    /* Style the tab content */
    
    .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
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
    
    <p></p>
    <body>

<div class="tab">
    <button class="tablinks" onclick="openCity(event, '氣候水文')" id="defaultOpen">氣候水文</button>
    <button class="tablinks" onclick="openCity(event, '地質地形')">地質地形</button>
    <button class="tablinks" onclick="openCity(event, '動物資源')">動物資源</button>
    <button class="tablinks" onclick="openCity(event, '植物資源')">植物資源</button>
    <button class="tablinks" onclick="openCity(event, '戰役古蹟')">戰役古蹟</button>
    <button class="tablinks" onclick="openCity(event, '人文史蹟')">人文史蹟</button>
    <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
</div>

<div id="氣候水文" class="tabcontent">
    <h2>氣候</h2>
    <p>四面無高山屏障，風力強勁，冬季乾冷，春季多霧，年降雨量大於年蒸發量 ，使島上出現半乾旱的現象，不宜耕作，故島上農作以耐旱性雜糧為主。</p>
    <h2>水文</h2>
    <p>以平均狀況來看，五、六月類似內地梅雨季節，經常降雨不止是唯一降雨量超過蒸發量的季節，七月、八月夏季雷雨或颱風，雨量豐但無法截用而流失，並甚至帶來災害，十月至翌年二月則為旱季。由於受地形影響，金門地區主要水源以人工湖庫及地下水為主。</p>
</div>

<div id="地質地形" class="tabcontent">
    <h2>地質</h2>
    <p> 以瓊林尚義一帶將金門本島分成東西兩半部，東半部明顯地大量出露花崗片麻岩，西半部則是以紅土層為主體。</p>
    <h2>地形</h2>
    <p> (一)丘陵地形 : 以花崗片麻岩為主。</p>
    <p> (二)臺地地形 : 金門和烈嶼的花崗岩地區臺地高度要比紅土層高度為高，原因為西部早期環境有利於大規模、厚層的紅土生成。</p>
    <p> (三)低地、窪地 : 以中山紀念林與白乳山附近出現的雨蝕溝最為顯著，其成因與第四紀以來的環境變遷有密切關係，在景觀及環境教育上皆有價值。</p>
    <p> (四)水體 : 金門地區陸上之水體除少數天然湖外，多為人工開發或築堤而成之湖庫，提高了此地環境的負載力，也為生物提供良好棲息和覓食地點。</p>
    <p> (五)沙丘、沙灘、海岸 : 金門東北、東南及烈嶼的東北至東南，為花崗片麻岩丘陵地被海水侵蝕而成之崖面，並且露出花崗片麻岩被岩脈侵入的景象。</p>
</div>

<div id="動物資源" class="tabcontent">
    <h2>(一)鳥類 </h2>
    <p>鳥類是金門最具特色的野生動物資源，於鹹淡水溼地、潮間 帶以及陸地田野、樹林、灌叢間，均可看到多樣且豐富的鳥類資源，其中過境鳥佔45%為最大宗。金門地區冬候鳥中以鸕鶿、赤頸鴨、小水鴨等為主要鳥種，留鳥以白頭翁、麻雀、八哥、珠頸斑鳩及喜鵲等族群量較多；夏候鳥則以家燕、杜鵑科鳥類及栗喉蜂虎 等最具特色。</p>
    <h2>(二)哺乳類</h2>
    <p>陸域哺乳動物中，除歐亞水獺體型較大外，其餘均為小型野生動物。歐亞水獺同時列名於國際與國內之保育類野生動物名錄，目前金門地區各主要溼地水體，如前埔溪流域、雙鯉湖及慈湖周邊、后豐港地區、金沙溪流域均可發現水獺活動痕跡，族群尚稱穩定，仍需與野生動物保育主管機關合作加強其動態調查及棲所之保護。</p>
</div>

 <div id="植物資源" class="tabcontent">
    <h2>特色比較</h2>
    <p>金門與台灣在植群組成上差異性仍甚大，如殼斗科(Fagaceae)在台灣為相當重要之一科，約產五十餘種，然在金門迄今未發現；金門之植物種類另一與台灣差異甚大堵，為樟科之潺槁樹，此種為目前金門自生木本植物中蓄積量最豐者。惟未見於台灣。</p>
</div>


<div id="戰役古蹟" class="tabcontent">
    <h2> 翟山坑道 </h2>
    <p>戰時供登陸小艇搶灘運補用，坑內並有停靠碼頭。一進入坑道內即可感受它的震撼力，靠著新架設的欄杆，望著深遂的倒影。在金門國家公園管理處重新整建後，翟山坑道於八十七年七月正式對外開放。</p>
    <h2> 毋忘在莒 </h2>
    <p>太武山上至三分之二處的途中，您就可發現由先總統 蔣公親頒題字的「毋忘在莒」四字的石塊矗立於上，誠然有提高士氣的精神在，勒石下有中興亭，旁有太武亭。</p>
    <h2> 八二三戰史館 </h2>
    <p>館內陳設有參與八二三戰役時期的各式武器、文物及圖片等，館外並陳列曾經參戰之飛機、戰車、榴彈砲兵器等。</p>
    
</div>

<div id="人文史蹟" class="tabcontent">
    <h2> 文臺寶塔 </h2>
    <p>金門有三大古塔，一是太武山倒影塔，二是水頭村的矛山塔，三是舊金城的文台寶塔，相傳皆是西元1387年江夏侯周德興建築金門城時，衡度水陸形勢所建，以做為航海之標誌。而太武山的倒影塔，毁於大地震；水頭的矛山塔，又因軍事緣故而拆毁。唯一僅存的是文台寶塔。</p>
    <h2> 風獅爺 </h2>
    <p>由於東北季風旺盛，金門的居民自清朝時期，就開始設立鎮風的辟邪物來 鎮風驅邪，而在金門最多的鎮風辟邪物就是風獅爺。</p>
    <h2> 羅厝媽祖公園 </h2>
    <p>烈嶼羅厝媽祖公園臨近九宮碼頭，位在羅厝後山制高點，可俯瞰羅厝漁港與東林濱海公園，公園裡最引人注目的是一尊高聳的媽祖石像，為羅厝新地標，這尊媽祖聖像材質為花崗岩。</p>
</div>

<div id="相關影音" class="tabcontent">
<div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/n3eVALwyMEU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>




<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
</script>

            <p></p>
            <div class="slideshow-container">

        <div class="mySlides fade">
            <div class="numbertext">1 / 4</div>
            <img style="width:100%;height:400px" src="https://image.cache.storm.mg/styles/smg-800x533-fp/s3/media/image/2019/03/15/20190315-055241_U9180_M506085_b5ed.jpg?itok=OXKypYWw">
            <div class="text">櫻花鉤吻鮭</div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">2 / 4</div>
            <img style="width:100%;height:400px" src="http://np.cpami.gov.tw/images/com_fwgallery/files/516/Photo_V6Y9E.jpg" >
            <div class="text"> </div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">3 / 4</div>
            <img style="width:100%;height:400px" src="http://www.herpera.com/images/fcivet3.jpg">
            <div class="text"> </div>
        </div>
        
        <div class="mySlides fade">
            <div class="numbertext">4 / 4</div>
            <img style="width:100%;height:400px" src="https://s.yimg.com/ny/api/res/1.2/A7zq9ob.LdgorO1dwZYqow--~A/YXBwaWQ9aGlnaGxhbmRlcjtzbT0xO3c9NzAzO2g9NTcx/http://media.zenfs.com/en/homerun/feed_manager_auto_publish_494/5409c727781755e0bbe35d393696ee13">
            <div class="text"> 台灣獼猴</div>
        </div>
    
        
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>

    </div>
    <br>

    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
    </div>

    <script>
        var slideIndex = 1;
        showSlides(slideIndex);

        function plusSlides(n) {
            showSlides(slideIndex += n);
        }

        function currentSlide(n) {
            showSlides(slideIndex = n);
        }

        function showSlides(n) {
            var i;
            var slides = document.getElementsByClassName("mySlides");
            var dots = document.getElementsByClassName("dot");
            if (n > slides.length) {
                slideIndex = 1
            }
            if (n < 1) {
                slideIndex = slides.length
            }
            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            for (i = 0; i < dots.length; i++) {
                dots[i].className = dots[i].className.replace(" active", "");
            }
            slides[slideIndex - 1].style.display = "block";
            dots[slideIndex - 1].className += " active";
        }
    </script>
        
        
        
        <p></p>
 

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
        <a class="button" id="top" href="#">網頁頂端</a>
        <a class="button" id="bottom" href="#">網頁底部</a>
        <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
    </div>

    </html>

