<html>

    <style>
        
        
        body {
            background-image: url("https://www.taiwan2go.com/upload/Article/32262/2-2.jpg");
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            background-size: cover;
        }
        
        p {
            font-size: 18px;
            font-family: Microsoft JhengHei;
        }
        h1{
            font-family:"微軟正黑體";
            font-weight:bold;
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
        /*video*/
    .video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    height: 0;
    overflow: hidden;
    }

    .video-container iframe,
    .video-container object,
    .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
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
    
     <body> 
    <div id="google_translate_element"></div>

    <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({pageLanguage: 'zh-tw', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
    }
    </script>

<script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit" ></script>

<center>
    <h1 style="font-size:40px;font-weight:bold;">雪霸國家公園</h1></center>
    <h1 id="A">基本資訊:</h1>
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

    <h1 id="B">國家公園標示意涵:</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
        <img align="left" style="width: 100px; height: 100px;" src="https://www.spnp.gov.tw/Content/image/logo-round.png" data-type="image">
        <center>
            <p>
                <p>山岳表示以雪山及大霸尖山為代表的山岳型國家公園；蜿蜒連綿的 綠水取源遠流長的意義；櫻花鉤吻鮭則是突顯出國家公園生態保育的 重責大任；而青山綠水是環保的理想園地，亦顯現國家公園百年大計的事業。
                </p>
            </p>
        </center>
    </div>

    <h1 id="C">公園特色介紹:</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    
    <p></p>
        <body>

    <div class="tab">
        <button class="tablinks" onclick="openCity(event, '氣候水文')" id="defaultOpen">氣候水文</button>
        <button class="tablinks" onclick="openCity(event, '地質地形')">地質地形</button>
        <button class="tablinks" onclick="openCity(event, '動物資源')">動物資源</button>
        <button class="tablinks" onclick="openCity(event, '植物資源')">植物資源</button>
        <button class="tablinks" onclick="openCity(event, '人文史蹟')">人文史蹟</button>
        <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
    </div>

    <div id="氣候水文" class="tabcontent">
        <h2>氣候</h2>
        <p>雪霸園區的初春時分的春雨及梅雨季，使得山區的天氣常細雨霏霏或鎮日水霧瀰漫；夏季有颱風及對流性驟雨的侵襲；雖是秋高氣爽，但若有大陸的冷氣團南下時，氣溫會急遽下降，偶有降雪的可能；嚴寒的冬季使山區積雪通行不易，常形成冰雪封山的狀況，故四季的氣候變化十分鮮明。</p>
        <h2>水文</h2>
        <p>山區天氣的日變化也很大，夏日縱然上午晴空萬里，午後多半雲霧蔽空，下雨機率在50％以上。夜晚氣溫驟降，尤其是3,000公尺以上的地區更是在0℃左右，在最熱的七月亦有零下3.2℃的記錄。</p>
    </div>

    <div id="地質地形" class="tabcontent">
        <h2>地質</h2>
        <p> 雪山山脈由始新世至中新世之板岩及變質砂岩為主之岩系構成，出露之岩層為始新世至中新世的輕度變質岩，變質程度由東南向西北漸減，因此雪霸國家公園區內的岩類主要以變質砂岩、硬頁岩及板岩為主。</p>
        <h2>地形</h2>
        <p>雪山遺留豐富的冰河地形，其中冰斗密集分布在雪山主峰周圍，雪山主峰周圍九個圈谷中，八個是古冰斗遺跡。位在雪山北側坡面的一號圈谷是規模全台最大，二號圈谷則為全台海拔最高。 </p>

       
    </div>

    <div id="動物資源" class="tabcontent">
        <h2>(一)魚類 </h2>
        <p>大甲溪是台灣魚類分布的海拔最高點，一般溪魚分布的上限約為1,800公尺，但是分布於大甲溪上游的櫻花鉤吻鮭則可達1,800公尺以上!</p>
        <h2>(二)哺乳類</h2>
        <p>雪見地區大型動物資源豐富，尤其以大安溪與雪山溪匯流口至北坑溪匯流口之間，尚可見大量而新鮮之台灣野山羊、台灣野豬、山羌、台灣獼猴等動物痕跡。其中，台灣黑熊為野生動物保育法所列瀕臨絕種保育類動物，台灣水鹿在野外的族群量亦極低，台灣野山羊亦屬珍貴稀有保育類動物。</p>
    </div>
    
     <div id="植物資源" class="tabcontent">
        <h2>特色植物</h2>
        <p>雪霸園區的植物種類繁多，其中棣慕華鳳仙花特產於觀霧地區，全世界僅一產地，族群亦小，須嚴加保護。 </p>
        <h2>特色植物</h2>
        <p>雪霸的植物種類大多屬於東亞植物地區之特有屬，自第三紀上新世(距今約180萬年)留存至今的臺灣檫樹，主要產於園內的大鹿林道、大雪山林道、雪見等地區，而檫樹屬植物全世界僅有三種，分別產於北美、大陸及臺灣，故有其特殊之學術地位。</p>
    </div>
    
    
    <div id="人文史蹟" class="tabcontent">
        <h2> 原住民文化 </h2>
        <p>泰雅族與賽夏族雖聚居於雪霸園區的範圍外，但本國家公園的全域，古來是他們的生活舞台，生活習俗已與雄偉的大自然渾為一體。而許多步道的形成，可追溯至原住民族的獵徑、姻親道路系統，路徑向高山、溪流、高山水池，甚至山峰的絕頂伸展，都遺留著這些山岳民族的足跡與智慧。廣大山區裡的各據點都有原來的稱謂與傳說，許多山岳名都是依照泰雅族語的原稱而命名的，如聖稜線中的凱蘭崑特山、穆特勒布山及武陵四秀中的喀拉業山等。</p>
    </div>
    
    <div id="相關影音" class="tabcontent">
    <div class="video-container">
       <iframe width="560" height="315" src="https://www.youtube.com/embed/UAnvm9XaOmc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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

</body>

        <p></p>
            <div class="slideshow-container">

        <div class="mySlides fade">
            <div class="numbertext">1 / 4</div>
            <img style="width:100%;height:400px" src="http://i.epochtimes.com/assets/uploads/2013/03/1303120149481758-600x400.jpg">
            <div class="text"> 櫻花鉤吻鮭 </div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">2 / 4</div>
            <img style="width:100%;height:400px" src="http://np.cpami.gov.tw/images/com_fwgallery/files/516/33.jpg" >
            <div class="text"> 台灣獼猴 </div>
        </div>

        <div class="mySlides fade">
            <div class="numbertext">3 / 4</div>
            <img style="width:100%;height:400px" src="http://g.udn.com.tw/upfiles/B_AA/AAC3343/PSN_PHOTO/623/f_18833623_1.jpg">
            <div class="text"> 棣慕華鳳仙花 </div>
        </div>
        
        <div class="mySlides fade">
            <div class="numbertext">4 / 4</div>
            <img style="width:100%;height:400px" src="https://cdntwrunning.biji.co/800_8341cc285c2234a7c530d1df1d994d1c.png">
            <div class="text"> 台灣黑熊 </div>
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

    </div>


    <h1 id="D">交通資訊:</h1>
    <div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    
     <body>

    <div class="tab">
        <button class="tablinks" onclick="openCity(event, '觀霧遊憩區')">觀霧遊憩區</button>
        <button class="tablinks" onclick="openCity(event, '雪見遊憩區')">雪見遊憩區</button>
        <button class="tablinks" onclick="openCity(event, '武陵遊客中心')">武陵遊客中心</button>

    </div>

    <div id="觀霧遊憩區" class="tabcontent">
        <h2 style="color:#FF8800;font-weight:bold;">自行開車</h2>
        <p>交通：前往觀霧旅遊行程路線，可行駛國道三號高速公路，於竹林交流道下後往竹東方向前進，接新竹縣122縣道，經五峰往清泉至土場後前行大鹿林道主線至觀霧。另由國道一號中山高速公路新竹公道五交流道，銜接台68線東西向快速道路可快速到達竹東接竹縣122縣道。 </p>
    </div>

    <div id="雪見遊憩區" class="tabcontent">
        <h2 style="color:#FF8800;font-weight:bold;">方式一:</h2>
        
        <p> 從苗栗、大湖地區進入由北部地區南下之車輛，可由國道１號高速公路下苗栗交流道接台72號快速道路，或經台6、台3線經汶水雪霸國家公園管理處進入大湖，再沿苗61線經中興檢查哨接司馬限林道經二本松進入雪見遊憩區，行程約35公里，車程約1.5小時。大湖→中興派出所（入山證）→二本松解說站→松林景觀台→國家公園界碑（盡尾山登山口）→雪見遊客中心暨管理站→東洗水山登山口→北坑山登山口</p>
        
        <h2 style="color:#FF8800;font-weight:bold;">方式二:</h2>
        
        <p> 從東勢、卓蘭地區進入由中南部出發之遊客，可利用台３線由台中的東勢鎮接中47線或由苗栗的卓蘭鎮苗58線經白布帆大橋接中47線，經達觀、桃山部落（雪山坑）進入泰安鄉，至永安、大安過梅象大橋進入梅園、天狗接司馬限林道經二本松進入雪見遊憩區，行程約45公里，車程約2小時。 東勢→雙崎部落→士林攔河堰→（士林部落）→象鼻部落→永安部落→大安部（入山證）→梅園部落→天狗部落→二本松鞍部→二本松解說站。 </p>
        
    </div>

    <div id="武陵遊客中心" class="tabcontent">
        <h2 style="color:#FF8800;font-weight:bold;">公車客運:</h2>
         <table border="1" cellpadding="5" cellspacing="0" width="90%">
                <thead>
                    <tr>
                        <th width="20%"> 路程 </th>
                        <th width="15%"> 時間 </th>
                        <th width="%">乘車時間</th>
                        <th width="%"> 聯絡電話 </th>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <td>宜蘭國光客運站 → 武陵農場</td>
                        <td>07:00、12:40</td>
                        <td>2小時45分</td>
                        <td>0800-010-138</td>
                    </tr>

                    <tr>
                        <td>武陵農場 → 宜蘭國光客運站</td>
                        <td>09:20、14: 05</td>
                        <td>2小時45分</td>
                        <td>0800-010-138</td>
                    </tr>
                    
                    <tr>
                        <td>台中--梨山--武陵</td>
                        <td>08:00-16:00 </td>
                        <td>6小時</td>
                        <td>(04)2523-4175#228 </td>
                    </tr>

                    <tr>
                        <td>武陵--梨山--台中 </td>
                        <td>6:30-14:30</td>
                        <td>6小時</td>
                        <td>(04)2523-4175#228 </td>
                    </tr>
                </tbody>
            </table>
    
        
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

        // Get the element with id="defaultOpen1" and click on it
        document.getElementById("defaultOpen1").click();
    </script>

</body>

    </div>

    <h1 id="E">住宿資訊:</h1>
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

    <h1 id="F">美食資訊:</h1>
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

    <h1>資料來源:</h1>
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
    </body>
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
